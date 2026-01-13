# sounds

Various sounds for use with [Strudel](https://strudel.cc/).

## SNES soundfonts

Adapted from sf2 files found [here](https://www.williamkage.com/snes_soundfonts/), using [sf2strudel](https://github.com/lynn/sf2strudel).

```
samples('https://raw.githubusercontent.com/lynn/sounds/main/earthbound/strudel.json')
s("oksuka")
```

```
samples('https://raw.githubusercontent.com/lynn/sounds/main/chrono-trigger/strudel.json?version=3')
setcpm(56)
note("[<e0 g#1 f#1 g#1> g#0 c#1 d#1]").sound("corridor").decay(0.6).jux(x => press(x).gain(0.6)).delay("0.3:0.08")
```

```
samples('https://raw.githubusercontent.com/lynn/sounds/main/yoshis-island/strudel.json')
s("musicbox")
```

## Vocaloid stems

Currently, `teto` is a stem of Kasane Teto singing Jamie Paige's _Strawberry_. I normalized the volume. Jamie's stems are [available under a CC BY-NC-SA license](https://jamies.page/stems).

```
samples('https://raw.githubusercontent.com/lynn/sounds/main/vocaloid/strudel.json')
s("teto")
```
