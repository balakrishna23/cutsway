# MOTION.md: Cutsway, The Raw Pile

Read this in full before designing, generating or animating anything for Cutsway. Sources: `examples/rawpile-poster.jpg`, `examples/rawpile-og.jpg` and the Raw Pile site's `brand.css`. Format: 1080 x 1920, 30 fps, 15 s Instagram Reel.

## 1. Colour

| Hex | Name | Use |
|---|---|---|
| `#07070a` | Night | The ground, every frame. Near-black, never pure `#000`. |
| `#f4f2ec` | Paper | Headlines and the main text. |
| `#c4c4d0` | Soft | Secondary lines and small labels. |
| `#fddf4b` | Yellow | First accent: the one thing to look at, and the call to action. |
| `#fb3b27` | Red | The cut: razor line, rejected clips, the burn's hot edge. |
| `#03c0f4` | Cyan | Second accent, used sparingly (a progress tick, a marker). |
| `#1c4cdd` | Blue | Cool ambient glow only. |
| Spectrum | `#272ed2 #1c4cdd #108ae8 #03c0f4 #5ae2e8 #a9f0dc #e8f8cd #fcf397 #fddf4b #fcb51c #fc8020 #fb3b27 #e21c2f #a81d30 #761a2b` (left to right) | The logo, the 3px foot line under the call to action, and light sweeps. Never on headlines or body text. |

Raw clips are desaturated tiles: dark card faces around `#15151c`, with muted mauve, sage and slate thumbnails. They stay grey until Cutsway touches them.

Ambient light comes from the poster: low, wide radial glows along the bottom edge, blue on the left, yellow-olive in the centre and red on the right, all at low opacity over Night.

## 2. Type

Archivo, embedded locally. Load it before the first frame so frame 0 never draws in a fallback font.

- **Display:** width 125, weight 900, upper case, tracking −0.012em, line height 0.87. It speaks like the wordmark.
- **Hero line:** 200–260px. At most 3 words per line, at most 2 lines.
- **Second line:** 96–128px, same display style.
- **Support text:** Archivo width 100, weight 600, sentence case, 44–56px, Paper or Soft.
- **Smallest anything:** 40px. Below that it can't be read on a phone.
- **Words on screen at once:** 6 at most.

## 3. Timing

The brand is speed, so the edit is fast and decisive.

- **Arrive:** 0.18–0.35 s. A headline lands in one move.
- **Hold:** long enough to read twice, 1.0–1.8 s for a hero line. The call to action holds at least 3 s.
- **Leave:** a hard cut or a razor slice of 0.08–0.15 s. Never a slow fade-out.
- **Scene changes:** on the cut itself. The razor line that slices a clip also wipes to the next scene.
- **Readable by second 2:** a stranger knows by then that this is about editing raw footage.

## 4. Movement

- **Frame rate:** 30 fps.
- **Easing:** `power4.out` or `expo.out` for arrivals, `power2.in` for the rare exit that isn't a cut. Nothing linear except the razor line itself.
- **No bounce, no elastic, no overshoot.** Motion snaps and settles; it never wobbles.
- **The razor:** a thin vertical line, Red or Paper, crosses in about 0.12 s. Whatever it crosses splits along it.
- **The burn:** rejected clips tint toward Red, their edges glow orange `#fc8020`, then they break into embers that rise and die in 0.6–0.9 s.
- **The keepers:** clips that survive snap into place in order, staggered 0.04–0.06 s each, never all at once.
- **The render bar:** the wordmark fills from left to right like an export bar, over a ghost copy at 10% opacity in greyscale. This is the logo reveal.
- **The light sweep:** a soft band of the spectrum passes once across the finished logo bar.
- **Always alive:** in any hold, one small thing still moves (an ember, a slow camera push of 2–3%, the tumbling pile), but only one focus.

## 5. Texture and finish

- Deep dark space, with faint pin-prick stars at very low opacity in the pile scenes.
- Clips are thin cards with slight 3D perspective and tumble, lit softly from the bottom glows.
- Glass panels, if used: `rgb(14 14 22 / 0.46)` with a 1px border of Paper at 24% opacity.
- Clean finish. No film grain, no chromatic aberration, no VHS, no glitch.

## 6. Never

1. Never slow, floaty or soft: no long cross-fades and nothing drifting without purpose.
2. Never bounce or elastic.
3. Never put the spectrum gradient on headlines or body text. It belongs to the logo.
4. Never put text or the logo in Instagram's unsafe zones: keep every word and the logo between y 250 and y 1330, and out of the right 120px. Below 1330 only texture and glow.
5. Never invent a number, testimonial, client logo or result. Never use another brand's logo (YouTube, Twitch, TikTok and so on) unless the file is supplied.

## 7. Done right, shot by shot (15 s)

1. **0.0–2.0, THE PILE.** Hundreds of grey clips tumble out of the dark over the low blue-yellow-red glow. "YOUR RAW PILE." slams in, Paper, 240px, upper case.
2. **2.0–5.0, THE CUT.** A red razor line crosses the frame. Clips split along it; the rejects flush red and burn into rising embers. "WE CUT IT." lands on the second slice.
3. **5.0–9.5, THE KEEPERS.** The surviving clips snap into a vertical stack, one per service, each cut in on the beat: "GAMING", "SHORTS", "PODCASTS". The podcast card shows `assets/mic-2.jpg`.
4. **9.5–11.5, THE SPEED.** The stack compresses into a single thin bar. Support line: "Posted while it's still trending." (A confirmed turnaround figure goes here if one is supplied.)
5. **11.5–15.0, THE LOGO.** The bar becomes the CUTSWAY wordmark, filling left to right like a render bar, then one light sweep. Below it: "cutsway.com" in Paper and "6281301476" in Soft, with the spectrum foot line under the URL. It holds 3+ s and the last frame sits still.
