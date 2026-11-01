# MOTION.md: Cutsway, Night Shift (experiment)

Read this in full before animating anything here. Sources: `examples/nightshift-og.jpg`, `examples/nightshift-poster.jpg` and the Night Shift site. Format: 1080 x 1920, 30 fps, 15 s Instagram Reel.

## 1. Colour

The brand colours are the same as the main reel. Night Shift uses them as light at different hours.

| Hex | Name | Use |
|---|---|---|
| `#07070a` | Night | Ground at night. |
| `#04050c` | Midnight | The sky at 1–4 am. |
| `#0e1236` | Indigo | Sky just after dusk, and the room's walls. |
| `#761a2b` → `#fb3b27` → `#fc8020` | Ember | The dusk sky at 9 pm and the room's lamp glow. |
| `#fcb51c` → `#fddf4b` → `#fcf397` | Dawn | The sunrise, and the flat yellow ground of the ending. |
| `#f4f2ec` | Paper | Type at night. |
| `#c4c4d0` | Soft | Secondary lines. |
| `#fddf4b` | Yellow | The accent at night; the ground in the morning. |
| `#fcb51c` | Window light | Lit windows in the skyline. |
| Spectrum | the logo gradient | The logo only, always on a Night slab. |

## 2. Type

The same as the main reel: Archivo, width 125, weight 900, upper case, tracking −0.012em, line height 0.87. Hero 180–230px. Support Archivo 600 at 48–56px. Nothing under 40px. At most 6 words readable at once. On the yellow ground, type is Night.

## 3. Timing

Speed is still the brand, but this film's one idea is *time passing*. The only long move is the night itself: a single 7-second scene where everything is driven by one clock. Everything else lands in 0.18–0.35s and cuts.

## 4. Movement

- **The clock:** the big readout steps one hour every 0.58s with a slot-machine roll of 0.1s per step. The steps are discrete and never blur into a smear.
- **Sky:** three layers cross over each other on the clock (dusk, then midnight, then dawn), `power2.inOut`. Stars come out after dusk and go at dawn.
- **City:** lit windows switch off one by one through the night, and only a few are left by dawn.
- **Timeline:** clips land on three tracks as the night goes on, each scaling in from its left edge in 0.18s `expo.out`.
- **Colour flood:** the sunrise becomes the yellow ground of the ending in 0.45s `power2.inOut`.
- No bounce. Titles land and hold still.

## 5. Texture and finish

Flat-illustrated studio: a window with a mullion and a 14px frame in `#24242d`, a skyline silhouette in `#0b0b10`, and soft lamp glow from the bottom. No grain, no glitch. The ending is a loud flat poster: yellow ground, a black slab and black type.

## 6. Never

1. Never slow, floaty or soft cross-fades between scenes.
2. Never bounce or elastic.
3. Never put the spectrum on text, and never put the logo directly on yellow (it disappears). The logo sits on a Night slab.
4. Never put words below y 1330 or in the right 120px.
5. Never invent a number, a client or a result.

## 7. Done right

See `SPEC.md`.
