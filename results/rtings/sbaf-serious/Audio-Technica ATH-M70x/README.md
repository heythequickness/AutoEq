# Audio-Technica ATH-M70x

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.9dB
GraphicEQ: 21 0.0; 23 1.5; 25 1.2; 28 0.8; 31 0.6; 34 0.6; 37 0.6; 41 0.7; 45 0.7; 49 0.6; 54 0.5; 60 0.2; 66 -0.1; 72 -0.4; 79 -0.7; 87 -1.0; 96 -1.2; 106 -1.4; 116 -1.5; 128 -1.6; 141 -1.4; 155 -1.2; 170 -1.1; 187 -1.1; 206 -1.1; 227 -1.4; 249 -1.6; 274 -1.7; 302 -1.2; 332 -1.6; 365 -1.4; 402 -0.7; 442 -0.1; 486 0.3; 535 0.6; 588 1.9; 647 2.7; 712 2.4; 783 1.5; 861 0.7; 947 0.2; 1042 -0.1; 1146 -0.2; 1261 -0.4; 1387 -1.0; 1526 -2.0; 1678 -2.9; 1846 -3.6; 2031 -4.3; 2234 -4.3; 2457 -3.9; 2703 -3.0; 2973 -2.7; 3270 -3.4; 3597 -3.2; 3957 -3.7; 4353 -7.4; 4788 -7.2; 5267 -3.5; 5793 0.3; 6373 1.3; 7010 0.2; 7711 -3.2; 8482 -6.9; 9330 -7.5; 10263 -4.7; 11289 -0.3; 12418 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Audio-Technica ATH-M70x GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-29**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Audio-Technica ATH-M70x ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.9dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-3.0dB**.

| Type    | Fc      |    Q | Gain    |
|:--------|:--------|:-----|:--------|
| Peaking | 21 Hz   | 2.12 | 1.8 dB  |
| Peaking | 679 Hz  | 3.48 | 3.2 dB  |
| Peaking | 2195 Hz | 1.51 | -4.3 dB |
| Peaking | 4532 Hz | 5.14 | -8.0 dB |
| Peaking | 9124 Hz | 4.18 | -8.5 dB |
| Peaking | 121 Hz  | 1.63 | -1.6 dB |
| Peaking | 281 Hz  | 1.76 | -1.6 dB |
| Peaking | 5243 Hz | 3.14 | -2.6 dB |
| Peaking | 6151 Hz | 2.82 | 4.3 dB  |
| Peaking | 8133 Hz | 7.67 | -2.5 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/sbaf-serious/Audio-Technica%20ATH-M70x/Audio-Technica%20ATH-M70x.png)