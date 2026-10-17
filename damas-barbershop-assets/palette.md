# Damas Barbershop — Farbpalette

Abgeleitet aus dem echten Laden (Wilhelm-Leuschner-Str. 1, Worms) und dem Eröffnungs-Creative.
Grundbild **hell & warm** (Tag), Akzent **Schwarz & Gold** (Nacht). Jedes Asset bleibt in dieser Palette.

| Name | Hex | Herkunft | Einsatz |
| --- | --- | --- | --- |
| **Salon Weiß** | `#F3F1EC` | Kassettenwände, Decke | Haupt-Hintergrund |
| **Lutherring Marmor** | `#CFCAC4` | heller grauer Marmorboden | Flächen, Karten, Trenner |
| **Eiche** | `#C08A55` | Holzlamellen, Spiegelrahmen | warme Flächen, Lamellen-Muster |
| **Chrom** | `#B8BCC0` | Stuhlsockel, Ringleuchte, Scheren | Linien, Icons, Hover |
| **Chesterfield** | `#141414` | schwarzes Leder, Theke, Stühle | Text, Nav, dunkle Sektionen |
| **Damas Gold** | `#E0A24E` | Logo / Instagram-Creative | Akzent — sparsam (≤ 5 % der Fläche) |

## Regeln

- Fließtext immer **Chesterfield auf Salon Weiß** (Kontrast ≈ 17:1).
- **Damas Gold nie als Text auf hellem Grund** (Kontrast zu niedrig) — nur auf Chesterfield, als dünne Linie, Icon oder Logo.
- Kein Barberpole-Rot/Blau.
- Dunkle „Nacht“-Sektionen (Chesterfield + Gold) höchstens 1–2 pro Seite: Hero-Overlay und Footer / Öffnungszeiten.

## CSS-Tokens

```css
:root {
  --damas-salon:   #F3F1EC;
  --damas-marble:  #CFCAC4;
  --damas-oak:     #C08A55;
  --damas-chrome:  #B8BCC0;
  --damas-leather: #141414;
  --damas-gold:    #E0A24E;
}
```
