# Damas Barbershop: Higgsfield-Befehle (CLI)

Die Prompts sind identisch mit `prompts.md`, wo die Palette eingebaut ist. Für die Weboberfläche nimmst du `prompts.md`, für das Terminal diese Datei.
Das sind 6 × `nano_banana_pro` 2k à 2 Credits, zusammen **12 Credits**, dazu **2 Credits Reserve** für einen Neuversuch.

## So geht's

1. Im Ordner `damas-barbershop-assets/` ausführen, damit die Pfade unter `reference/` stimmen.
2. Optional zuerst den Preis prüfen: `cost` statt `create`. Das ist kostenlos.
3. Danach sagst du mir Bescheid. Ich hole die Ergebnisse mit `higgsfield generate list`/`get` ab, benenne sie und trage alles ins Manifest ein.

## 1 · Banner (`banner/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-reception.webp \
  --image reference/interior-render-floor.webp \
  --prompt 'Website hero photograph, wide 16:9, of a bright modern barbershop. A single empty black leather barber chair (deep black #141414) on a polished chrome base (#B8BCC0) stands on the RIGHT third of the frame, angled slightly toward the camera, in front of a wall of vertical warm oak slats (#C08A55) separated by thin black gaps. Beside it an oak-framed mirror and a matte black wall sconce. The LEFT half of the frame is calm and empty: softly out-of-focus oak slats, warm off-white panelled wall (#F3F1EC) and polished light grey marble floor (#CFCAC4) with soft veining, leaving clean space for a headline. Eye level, 35mm lens, shallow depth of field. Soft bright daylight from recessed ceiling downlights, warm glow in the wood, gentle gloss on the marble, one tiny warm brass-gold glint (#E0A24E) on the chair'\''s footrest. Colour palette strictly limited to warm off-white #F3F1EC, light warm grey marble #CFCAC4, warm oak #C08A55, chrome silver #B8BCC0, deep black #141414 and one tiny gold accent #E0A24E. Photorealistic editorial interior photography, clean and calm. No people, no text, no letters, no logos, no signage, no barber pole, no skulls, no Edison bulbs.'
```

## 2 · Hero „Fade“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt 'Macro close-up of a fresh skin fade being cut. A barber'\''s hand holds a matte black (#141414) and polished chrome (#B8BCC0) hair clipper against the side of a man'\''s head just above the ear, seen from behind and slightly to the side so the face is not visible. Short dark hair blends seamlessly into skin, tiny hair clippings float in the air and catch the light. Background softly blurred: vertical warm oak slats (#C08A55) with thin black gaps and a warm off-white wall (#F3F1EC). 85mm macro lens, shallow depth of field, soft bright daylight from above, warm reflections on the chrome. Colour palette strictly limited to warm off-white #F3F1EC, light warm grey #CFCAC4, warm oak #C08A55, chrome silver #B8BCC0, deep black #141414 and one tiny gold accent #E0A24E. Photorealistic editorial photography, crisp and clean. No text, no letters, no logos, no tattoos, no visible face.'
```

## 3 · Hero „Bart“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt 'Close-up of a precise beard line-up. A barber'\''s hand guides a polished steel straight razor (chrome #B8BCC0) along the cheek line of a full, well-groomed dark beard. Tightly cropped from lower cheek to jaw, the eyes are outside the frame so no face is recognisable. A thin line of white shaving foam at the edge, a deep black barber cape (#141414). Background softly blurred: vertical warm oak slats (#C08A55) and a warm off-white wall (#F3F1EC). 85mm macro lens, shallow depth of field, soft bright daylight, a crisp highlight running along the razor blade, a faint damascus-steel pattern on the blade, one tiny warm gold glint (#E0A24E) on the razor'\''s handle pin. Colour palette strictly limited to warm off-white #F3F1EC, light warm grey #CFCAC4, warm oak #C08A55, chrome silver #B8BCC0, deep black #141414 and one tiny gold accent #E0A24E. Photorealistic editorial photography, clean and calm. No text, no letters, no logos, no blood, no visible eyes or face.'
```

## 4 · Hero „Kids“ (`heroes/`, 1:1)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 1:1 --resolution 2k \
  --prompt 'A young boy of about seven sits in a big black leather barber chair (#141414) with chrome armrests (#B8BCC0), seen from behind: the back of his head with a fresh neat haircut, a black barber cape, his small hand resting on the chrome armrest, his sneakers dangling well above the footrest. The barber'\''s hand gently holds a black comb near his head. Warm, relaxed family atmosphere. In front of him a large oak-framed mirror, its reflection softly blurred and unreadable, surrounded by vertical warm oak slats (#C08A55) and a warm off-white wall (#F3F1EC). 50mm lens, shallow depth of field, soft bright daylight from recessed downlights. Colour palette strictly limited to warm off-white #F3F1EC, light warm grey #CFCAC4, warm oak #C08A55, chrome silver #B8BCC0, deep black #141414 and one tiny gold accent #E0A24E. Photorealistic editorial photography. No text, no letters, no logos, no visible faces, no face visible in the mirror.'
```

## 5 · Detail „Werkzeug“ (`detail/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-floor.webp \
  --prompt 'Top-down styled flat-lay on a polished light warm grey marble countertop (#CFCAC4) with soft, sparse veining. Arranged on the right two thirds: a pair of polished steel barber scissors (chrome #B8BCC0), a matte black and chrome hair clipper (#141414 / #B8BCC0), a black fine-tooth comb, a folded straight razor with a subtle damascus steel pattern on the blade, and one small brass detail (#E0A24E). Generous empty marble on the left third. A thin strip of warm oak wood (#C08A55) enters from the right edge. Soft bright diffused daylight, gentle realistic shadows. Colour palette strictly limited to warm off-white #F3F1EC, light warm grey marble #CFCAC4, warm oak #C08A55, chrome silver #B8BCC0, deep black #141414 and one tiny gold accent #E0A24E. Photorealistic editorial product photography. No text, no letters, no logos, no brand names on the tools, no hair, no people.'
```

## 6 · Textur „Marmor“ (`extras/textures/`, 16:9)

```bash
higgsfield generate create nano_banana_pro \
  --aspect_ratio 16:9 --resolution 2k \
  --image reference/interior-render-floor.webp \
  --prompt 'Flat, perfectly even, straight-on texture of polished light warm grey marble, base colour #CFCAC4, with very soft, sparse, low-contrast veining in pale grey and a hint of warm off-white #F3F1EC. Uniform soft lighting, no reflections, no shadows, no objects, no edges, no tile seams, no perspective. Calm and subtle enough to sit behind dark text as a website section background. Seamless, tileable. No text, no letters, no logos.'
```

## Optional, über dem Budget: Video-Loop (720p 10 Credits, 480p 4 Credits)

```bash
higgsfield generate create seedance_2_0 \
  --mode fast --resolution 720p --duration 4 --generate_audio false --aspect_ratio 16:9 \
  --start-image banner/damas-banner.png \
  --prompt 'Locked-off camera, almost still. Very slow, subtle push-in toward the empty black leather barber chair. Soft daylight gently shifts across the warm oak slats, a few fine dust particles drift in the light and catch a faint gold glint. Colours stay warm off-white, light grey marble, warm oak, chrome and deep black. Calm, premium, seamless loop. No people, no text.'
```
