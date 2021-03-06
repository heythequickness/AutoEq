# Noble PR P Tuning

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -5.0dB
GraphicEQ: 21 0.0; 23 3.5; 25 3.4; 28 3.2; 31 3.0; 34 2.9; 37 2.7; 41 2.5; 45 2.4; 49 2.1; 54 1.8; 60 1.5; 66 1.2; 72 0.8; 79 0.4; 87 0.0; 96 -0.4; 106 -0.7; 116 -1.0; 128 -1.3; 141 -1.6; 155 -1.8; 170 -2.0; 187 -2.1; 206 -2.1; 227 -2.2; 249 -2.1; 274 -2.1; 302 -1.9; 332 -1.8; 365 -1.6; 402 -1.5; 442 -1.1; 486 -1.0; 535 -0.7; 588 -0.2; 647 0.0; 712 0.2; 783 0.4; 861 0.3; 947 0.1; 1042 -0.1; 1146 -0.2; 1261 -0.4; 1387 -0.9; 1526 -1.3; 1678 -1.5; 1846 -1.3; 2031 -1.2; 2234 -1.1; 2457 -0.7; 2703 0.0; 2973 2.2; 3270 4.2; 3597 4.7; 3957 2.3; 4353 -2.0; 4788 -4.9; 5267 -7.1; 5793 -8.7; 6373 -7.3; 7010 -6.2; 7711 -6.7; 8482 -7.5; 9330 -4.3; 10263 -0.2; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 -0.7; 18182 0.0
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Noble PR P Tuning GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-49**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Noble PR P Tuning ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-5.6dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-5.6dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 21 Hz    | 0.34 | 3.6 dB  |
| Peaking | 195 Hz   | 0.63 | -2.5 dB |
| Peaking | 3570 Hz  | 3.66 | 7.6 dB  |
| Peaking | 5691 Hz  | 1.8  | -8.8 dB |
| Peaking | 8377 Hz  | 4.73 | -5.7 dB |
| Peaking | 802 Hz   | 2.11 | 1.0 dB  |
| Peaking | 1864 Hz  | 1.41 | -1.4 dB |
| Peaking | 3088 Hz  | 7.9  | 1.5 dB  |
| Peaking | 10828 Hz | 4.5  | 1.6 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/innerfidelity/sbaf-serious/Noble%20PR%20P%20Tuning/Noble%20PR%20P%20Tuning.png)