# Damas Barbershop — Art Direction

> **Entscheidung:** Logo macht Claude Desktop später. Finales Paket = Option A ohne Logo:
> 6 Bilder × 2 Credits = 12 + 2 Reserve. Befehle: `generate-commands.md`.

## Marke in einem Satz
„Wie zu Besuch beim Cousin“ — familiär und locker, aber präzise und makellos gepflegt.
Vater & Sohn (Hussein & Ali Kishane), Herren- und Kinderhaarschnitte, Bart, ohne Termin, faire Preise.

**Leise Geschichte:** *Damas* ist der arabische/französische Kurzname für Damaskus — und Damaszener Stahl
steht für die besten Klingen. Wir zeigen das nicht als Text, sondern über Klingen-Details und Chrom.

## Bildsprache
- **Licht:** weiches, helles Tageslicht von vorne-oben (Downlights), warme Reflexe im Eichenholz, Glanz auf dem Marmor.
- **Set:** senkrechte Eichenlamellen, heller grauer Marmor, schwarzer Barberstuhl mit Chromsockel, schwarzes Chesterfield-Leder, schwarze Wandleuchten, gerahmte Spiegel.
- **Gold** nur als kleiner Akzent (Messing-Detail, warmer Lichtpunkt), nie dominant.
- **Kein Text in Fotos.** Keine Totenköpfe, kein Barberpole, keine Edison-Glühbirnen, kein Rustikal-Look.
- **Menschen:** Hände, Hinterkopf, Profil — keine erkennbaren Gesichter (keine Model-Rechte nötig).

## Logo
Das bestehende goldene Rund-Badge bleibt. Saubere Neuzeichnung als freigestelltes PNG
(gpt_image_2, Badge als Referenz); dabei „STED 2000“ → „EST. 2000“ korrigieren.
Zusätzlich eine reine Wortmarke „DAMAS“ als SVG (von Hand, 0 Credits) für Nav und Favicon.

## Was ich ohne Credits baue
- Holzlamellen-Muster als CSS (`repeating-linear-gradient` in Eiche/Chesterfield)
- Wortmarke + Favicon als SVG
- „Ken Burns“-Zoom auf dem Banner als Motion-Ersatz (CSS)

## Kosten (gemessen mit `higgsfield generate cost`)
| Modell / Einstellung | Credits |
| --- | --- |
| nano_banana_pro, 2k, beliebiges Format | 2 |
| nano_banana_pro, 4k | 4 |
| gpt_image_2, medium, 1k | 1 |
| gpt_image_2, high, 1k | 3,5 |
| seedance_2_0, fast, 480p, 4 s, ohne Audio | 4 |
| seedance_2_0, fast, 720p, 4 s, ohne Audio | 10 |
| seedance_2_0, std, 720p, 5 s, ohne Audio | 22,5 |

Kontostand: 28 Credits · Budget: **max. 14**

## Option A — „Stills“ (empfohlen) · 13 Credits + 1 Reserve
| # | Asset | Modell | Format | Credits |
| --- | --- | --- | --- | --- |
| 1 | Logo-Badge neu gezeichnet, transparent | gpt_image_2 medium 1k | 1:1 | 1 |
| 2 | Banner: leerer Barberstuhl vor Eichenlamellen, Marmorboden, links Platz für Headline | nano_banana_pro 2k | 16:9 | 2 |
| 3 | Hero „Fade“: Clipper an der Schläfe, Nahaufnahme | nano_banana_pro 2k | 1:1 | 2 |
| 4 | Hero „Bart“: Rasiermesser-Kontur am Bart, Profil | nano_banana_pro 2k | 1:1 | 2 |
| 5 | Hero „Kids“: Kind auf dem Stuhl, Kinderhand am Umhang, von hinten | nano_banana_pro 2k | 1:1 | 2 |
| 6 | Detail: Schere, Chrom-Clipper, Kamm auf Marmor (Flat-Lay) | nano_banana_pro 2k | 16:9 | 2 |
| 7 | Textur: heller Marmor, nahtlos, sehr ruhig | nano_banana_pro 2k | 16:9 | 2 |
|  | Reserve für 1 Neuversuch |  |  | 1 |

## Option B — „Mit Bewegung“ · 13 Credits + 1 Reserve
Logo (1) + Banner (2) + Fade (2) + Bart (2) + Marmor (2) + **Video 4 s, 480p, aus dem Banner (4)**.
Nachteil: 480p wirkt als Vollbild-Hintergrund weich — geht nur mit dunklem Overlay.
