# RepProbe

Public project page for RepProbe, a diagnostic study of repetition counting in video-language models.

Mahsa Khoshnoodi and Sarah Adel Bargal, 2026.

## Local preview

```bash
python3 -m http.server 8900 --bind 0.0.0.0 --directory RepProbe-webpage
```

Then open `http://127.0.0.1:8900/`.

## Assets

- `clips/k4_jumpjack.mp4` — hero: four jumping jacks from RepCount `stu5_18`.
- `clips/k4_situp.mp4` — construction example: four sit-ups from `stu7_56`.
- `clips/k3_situp_{start,middle,end}.mp4` — same source, three 3-rep windows.
- `clips/k6_hammer.mp4` — Coverage: hammer throw, k = 6.
- `clips/k12_rower_dock.mp4` — Coverage: dock rower, k = 12.
- `clips/k20_pommel.mp4` — Coverage: pommel horse, k = 20.
- `clips/synth/*.mp4` — one k = 4 clip from each of the ten synthetic families.
