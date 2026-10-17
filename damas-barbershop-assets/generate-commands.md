# Damas Barbershop: Higgsfield-Befehle für dich

Das sind 6 Bilder mit `nano_banana_pro` in 2k. Jedes kostet 2 Credits, zusammen also **12 Credits**. Damit bleiben **2 Credits Reserve** für einen Neuversuch, und das 14-Credit-Budget wird eingehalten.
Das Logo ist nicht dabei, das kommt später aus Claude Desktop.

## So geht's

1. Repo klonen und in den Ordner `damas-barbershop-assets/` wechseln. Die Referenzfotos liegen dort unter `reference/`.
2. Optional kannst du vorher den Preis prüfen: denselben Befehl mit `cost` statt `create` ausführen. Das kostet nichts.
3. Die Befehle der Reihe nach ausführen. Jeder Befehl gibt eine Job-ID aus.
4. Danach sagst du mir Bescheid. Ich hole die Ergebnisse mit `higgsfield generate list` bzw. `get` ab, lege sie in die Ordner, binde sie ein und aktualisiere `manifest.md`.

**Referenzbilder:** Bei Banner, Detail und Marmor hängen die beiden Innenraum-Renderings als Referenz an. Darauf sind keine Personen zu sehen. So werden Lamellen, Marmor und Möbel zu *eurem* Laden. Willst du ohne Referenz generieren, lässt du die `--image`-Zeilen weg.

## Gemeinsamer Stilblock (in jedem Prompt enthalten)

> Bright modern barbershop interior: wall of vertical warm oak slats with thin black gaps, polished light grey marble floor with soft veining, black leather barber chairs on polished chrome bases, matte black wall sconces, oak-framed mirrors, white panelled walls. Soft bright daylight from recessed ceiling downlights, warm glow in the wood, gentle gloss on the marble. Colour palette strictly limited to warm off-white, light warm grey marble, warm oak, chrome silver, deep black leather and one tiny brass-gold accent. Photorealistic editorial photography, clean and calm. No text, no letters, no logos, no signage, no barber pole, no skulls, no Edison bulbs, no visible faces.

---

## 1 · Banner (`banner/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-reception.webp \
  --image reference/interior-render-floor.webp \
  --prompt "Website hero photograph, wide 16:9. A single empty black leather barber chair on a polished chrome base stands on the RIGHT third of the frame, angled slightly toward camera, in front of a wall of vertical warm oak slats; an oak-framed mirror and a matte black sconce beside it. The LEFT half of the frame is calm and uncluttered: soft out-of-focus oak slats and light marble floor, perfect clean space for a headline. Eye-level, 35mm, shallow depth of field, soft bright daylight from recessed downlights, a faint warm brass highlight on the chair's footrest. Bright modern barbershop interior: wall of vertical warm oak slats with thin black gaps, polished light grey marble floor with soft veining, black leather barber chairs on polished chrome bases, matte black wall sconces, oak-framed mirrors, white panelled walls. Colour palette strictly limited to warm off-white, light warm grey marble, warm oak, chrome silver, deep black leather and one tiny brass-gold accent. Photorealistic editorial photography, clean and calm. No text, no letters, no logos, no signage, no barber pole, no skulls, no Edison bulbs, no people, no visible faces."
```

## 2 · Hero „Fade“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt "Macro close-up of a fresh skin fade being cut: a barber's hand holds a matte black and chrome hair clipper against the side of a man's head just above the ear, seen from behind and slightly to the side so no face is visible. Short dark hair blending seamlessly into skin, tiny hair clippings in the air catching the light. Background softly blurred: vertical warm oak slats and an oak-framed mirror. 85mm macro, shallow depth of field, soft bright daylight from above, warm reflections. Colour palette strictly limited to warm off-white, light warm grey, warm oak, chrome silver, deep black, one tiny brass-gold accent. Photorealistic editorial photography, crisp and clean. No text, no letters, no logos, no tattoos, no visible face."
```

## 3 · Hero „Bart“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt "Close-up of a precise beard line-up: a barber's hand guides a polished steel straight razor along the cheek line of a full, well-groomed dark beard. Cropped tightly from lower cheek to jaw, the eyes are outside the frame so no face is recognisable. A thin layer of white shaving foam on the edge, a black barber cape. Background softly blurred: vertical warm oak slats. 85mm macro, shallow depth of field, soft bright daylight, a crisp highlight running along the razor blade like fine damascus steel. Colour palette strictly limited to warm off-white, light warm grey, warm oak, chrome silver, deep black, one tiny brass-gold accent. Photorealistic editorial photography, clean and calm. No text, no letters, no logos, no blood, no visible eyes or face."
```

## 4 · Hero „Kids“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt "A young boy of about seven sits in a big black leather barber chair with chrome armrests, seen from behind: we see the back of his head with a fresh neat haircut and a black barber cape, his small hand resting on the chrome armrest, his sneakers dangling well above the footrest. The barber's hand gently holds a comb near his head. Warm, relaxed, family atmosphere. In front of him a large oak-framed mirror, reflection softly blurred and unreadable, vertical warm oak slats around it. 50mm, shallow depth of field, soft bright daylight. Colour palette strictly limited to warm off-white, light warm grey, warm oak, chrome silver, deep black, one tiny brass-gold accent. Photorealistic editorial photography. No text, no letters, no logos, no visible faces, face not visible in mirror."
```

## 5 · Detail „Werkzeug“ (`detail/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-floor.webp \
  --prompt "Top-down styled flat-lay on a polished light grey marble countertop with soft veining: a pair of polished steel barber scissors, a matte black and chrome clipper, a black fine-tooth comb, a folded straight razor with a subtle damascus steel pattern on the blade, and one small brass detail, arranged with generous negative space on the left third. A thin strip of warm oak wood enters from the right edge. Soft bright diffused daylight, gentle realistic shadows. Colour palette strictly limited to warm off-white, light warm grey marble, warm oak, chrome silver, deep black, one tiny brass-gold accent. Photorealistic editorial product photography. No text, no letters, no logos, no brand names on the tools, no hair, no people."
```

## 6 · Textur „Marmor“ (`extras/textures/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-floor.webp \
  --prompt "Flat, perfectly even, straight-on texture of polished light warm grey marble (#CFCAC4) with very soft, sparse, low-contrast veining in pale grey and a hint of warm white. Uniform soft lighting, no reflections, no shadows, no objects, no edges, no tile seams, no perspective. Calm and subtle enough to sit behind dark text as a website section background. Seamless, tileable. No text, no letters, no logos."
```

---

## Wenn noch Credits übrig sind (optional, nicht im Budget)

Das ist ein Video-Loop vom Banner, nur sinnvoll, wenn du später mehr Credits hast. Es kostet 4 Credits bei 480p und 10 Credits bei 720p.

```bash
higgsfield generate create seedance_2_0 \
  --mode fast --resolution 720p --duration 4 --generate_audio false --aspect_ratio 16:9 \
  --start-image banner/damas-banner.png \
  --prompt "Locked-off camera, almost still. Very slow, subtle push-in toward the empty barber chair. Soft daylight gently shifts across the oak slats, a few fine dust particles drift in the light. Calm, premium, seamless loop. No people, no text."
```
