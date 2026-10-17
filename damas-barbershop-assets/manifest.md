# Damas Barbershop: Asset-Manifest

Stand: 17.10.2026 · **Status: final** · Higgsfield-Workspace „Private“ · Budget max. 14, verbraucht 12

| Datei (Original-PNG + Web-WebP) | Modell | Format | Credits | Status | Higgsfield-Job | Prompt |
| --- | --- | --- | --- | --- | --- | --- |
| `banner/damas-banner` | nano_banana_pro 2k | 16:9 (2752×1536) | 2 | ✅ fertig | `53fa9124-8977-44a7-8545-ce6612203777` | prompts.md §1 |
| `heroes/damas-fade-1x1` | nano_banana_pro 2k | 1:1 (2048²) | 2 | ✅ fertig | `02fe6f70-e26b-483d-a3ab-d8e69f320fb6` | §2 |
| `heroes/damas-bart-1x1` | nano_banana_pro 2k | 1:1 (2048²) | 2 | ✅ fertig | `fb2c2075-6e0e-472e-a4d8-00cee3073186` | §3 |
| `heroes/damas-kids-1x1` | nano_banana_pro 2k | 1:1 (2048²) | 2 | ✅ fertig | `75ab6d3b-7659-4730-a041-fc8f1658cb88` | §4 |
| `detail/damas-tools-16x9` | nano_banana_pro 2k | 16:9 (2752×1536) | 2 | ✅ fertig | `1983bd52-bf5f-4ae9-b61f-433b01556c7f` | §5 |
| `extras/textures/damas-marble` | nano_banana_pro 2k | 16:9 (2752×1536) | 2 | ✅ fertig | `6e75e03b-b4ca-4fcc-b946-e8d569962417` | §6 |
| **Verbraucht** | | | **12** | Konto 28 → 16 | | |
| **Rest im Budget (14)** | | | **2** | ungenutzte Reserve | | |

Die Jobs wurden am 17.10.2026 zwischen 11:02 und 11:08 ausgeführt. In den Job-Daten habe ich keine Referenzbilder gefunden. Sie wurden also vermutlich ohne Referenz generiert.
Websites nutzen die `.webp`-Dateien (insgesamt ca. 0,9 MB). Die `.png`-Dateien sind die Originale in voller Auflösung (ca. 33 MB) für Druck und Nachbearbeitung.

**Hinweise zur Sichtung:**
- **Banner:** Der Stuhl steht rechts der Mitte. Links bleibt ruhige Fläche mit Kassettenwand und Lamellen im Vordergrund, dort hat die Headline Platz.
- **Fade:** Die Wange des Barbers ist oben links unscharf angeschnitten. Erkennbar ist er nicht.
- **Bart:** Nase und Mund sind im Bild, die Augen nicht. Die Handschuhe wirken leicht dunkelblau statt schwarz.
- **Detail:** Am linken Rand ist ein gerader Streifen in Salon Weiß zu sehen. Auf hellem Seitenhintergrund verschmilzt er, sonst bitte auf 84 % Breite zuschneiden.
- **Marmor:** ruhig, gut als Section-Hintergrund geeignet.
- **Kids:** Der Junge ist von hinten und im Halbprofil zu sehen, nicht erkennbar. Die Hand des Barbers hält den Kamm, der Spiegel bleibt unscharf. Gleiche Eichen-, Chrom- und Lederwelt wie die anderen Bilder.

## Ohne Credits gebaut

| Datei | Inhalt |
| --- | --- |
| `prompts.md` | Alle Prompts mit eingebauter Palette (für die Weboberfläche) |
| `damas-tokens.css` | Farb-Tokens, Holzlamellen-Muster, Marmor-Overlay, Nacht-Sektion, goldene Trennlinie, Ken-Burns-Zoom |
| `palette.md` | Palette mit Hex-Werten und Regeln |
| `embed-guide.md` | HTML/CSS-Snippets für alle Platzierungen |
| `claude-design-brief.md` | Übergabe an Claude Design |
| `reference/` | Original-Fotos (Renderings, Laden, Eröffnungs-Creative) |

## Bewusst nicht enthalten

- **Logo / Favicon:** kommt aus Claude Desktop. Der Platzhalterpfad ist `logo/damas-logo.svg`, der Hinweis „STED 2000“ → „EST. 2000“ steht in art-direction.md.
- **Motion-Loop (seedance_2_0):** liegt über dem Budget. Den Ersatz übernimmt der Ken-Burns-Zoom in CSS, den optionalen Befehl findest du in generate-commands.md.
- **Lifestyle- und Action-Serien aus dem Original-Skill:** bei 14 Credits zusammengefasst in die drei Service-Heroes und den Detail-Shot.

Nach der Generierung trage ich hier Job-IDs und tatsächlich verbrauchte Credits ein.
