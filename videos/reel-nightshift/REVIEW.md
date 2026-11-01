# REVIEW: Cutsway reel, Night Shift v2 (30 s, 1080 x 1920)

## What changed from v1 (owner feedback, 2026-10-29)
- 15 s to 30 s, faster, more information. The night (13 s) cycles a "now cutting" card through all four services with turnaround (8H / 12H / 36H / 48H). Morning adds 2 rounds of notes; a posting beat lists 4 platforms; the poster ends on "SEND IT TONIGHT."
- Music: an original 128 BPM track, warmer keys in D minor, from `../tools/make_music.py nightshift`. The clock steps every 2 beats, cards every 7 beats, scenes on bar lines. Sound effects on the stamp, clock ticks, card swaps, flood, pins and pills.

## Measured
- `hyperframes check`: passes (2 warnings, kept).
- Upload file `renders/cutsway-reel-nightshift-30s-instagram.mp4`: H.264 yuv420p + AAC, -14.1 LUFS, peak -1.5 dBFS.
- Not heard: the mix was checked by meters only.

## v3 (2026-10-29): voiceover and more motion
- Voiceover: local Kokoro (`../tools/make_vo.py`), one line per scene, fitted to its window (speed 1.08 to 1.25), with an EQ, compression and saturation chain; the music is ducked about 7 dB under it (`assets/audio/music-bed.wav`). Voice about 8.5 LU above the bed.
- Motion: a film-wide `compositions/fx.html` layer (embers, kick glow, cut flashes, glitch slices on drops, speed streaks before whips) plus beat punches inside every scene.
- Not heard or transcribed: pronunciation (e.g. "VOD", "Cutsway") is unverified. To use a premium voice, replace synth() in make_vo.py.
