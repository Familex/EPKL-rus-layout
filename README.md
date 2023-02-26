# [EPKL](https://github.com/DreymaR/BigBagKbdTrixPKL.git) extension to support `йцукен` layout

## Setup

- Put `[Йцукен]` folder into `[Layouts]` folder:
```
BigBagKbdTrixPKL
│
└───Layouts
    │
    └───Йцукен
```
- Search for `Йцукен` layout in EPKL app settings or put layout string directly into `EPKL_Layouts_Override.ini`:
```ini
[pkl]
layout = Colemak\Cmk-eD\Cmk-eD_ANS:Colemak-eD (ANS), Йцукен\Йцу-eD2VK_ANS:Йцукен-eD2VK (ANS)
; layout = Йцукен\Йцу-VK_ANS:Йцукен-VK (ANS)
; layout = Colemak\Cmk-eD\Cmk-eD_ANS:Colemak-eD (ANS), Йцукен\Йцу-eD_ANS:Йцукен-eD (ANS)
```

## Issues
- The keyboard shortcuts are not supported on the Russian layout for some reason.
