# Grado SR325e

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 5.9; 34 5.5; 37 4.8; 41 4.0; 45 3.3; 49 2.7; 54 2.1; 60 1.6; 66 1.1; 72 0.7; 79 0.4; 87 0.1; 96 -0.1; 106 -0.4; 116 -0.6; 128 -0.7; 141 -0.8; 155 -0.8; 170 -0.9; 187 -0.8; 206 -0.4; 227 -0.2; 249 -0.3; 274 -0.7; 302 -0.7; 332 -0.6; 365 -0.4; 402 -0.4; 442 -0.6; 486 -0.7; 535 -0.7; 588 -0.5; 647 -0.4; 712 -0.2; 783 -0.1; 861 0.0; 947 0.0; 1042 0.0; 1146 -0.1; 1261 -0.4; 1387 -1.0; 1526 -1.8; 1678 -3.0; 1846 -5.9; 2031 -9.0; 2234 -8.9; 2457 -7.0; 2703 -5.3; 2973 -4.1; 3270 -3.9; 3597 -3.4; 3957 -4.1; 4353 -5.3; 4788 -2.6; 5267 -3.0; 5793 -3.4; 6373 -1.8; 7010 -1.4; 7711 -2.7; 8482 -5.9; 9330 -9.2; 10263 -10.5; 11289 -9.4; 12418 -7.1; 13660 -4.4; 15026 -2.1; 16529 -0.4; 18182 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Grado SR325e GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Grado SR325e ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 26 Hz    | 0.7  | 6.5 dB   |
| Peaking | 113 Hz   | 0.55 | -1.3 dB  |
| Peaking | 2254 Hz  | 1.91 | -8.7 dB  |
| Peaking | 10564 Hz | 1.6  | -10.7 dB |
| Peaking | 24000 Hz | 2.19 | -2.8 dB  |
| Peaking | 1827 Hz  | 1.09 | 1.9 dB   |
| Peaking | 1976 Hz  | 5.28 | -3.6 dB  |
| Peaking | 4259 Hz  | 3.33 | -3.4 dB  |
| Peaking | 7235 Hz  | 6.41 | 2.4 dB   |
| Peaking | 17329 Hz | 2.91 | 1.1 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Grado%20SR325e/Grado%20SR325e.png)