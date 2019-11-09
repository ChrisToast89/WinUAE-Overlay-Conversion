Customized overlays based on work by https://github.com/TreyM/classic-crt-collection for use with WinUAE.

Designed for 1920x1080 displays. 
Preview: https://imgur.com/a/T407GTt

Setup based on WinUAE 4.2:

![Logo](https://i.imgur.com/peHKBbx.png)

************************************************************************************************************
![Logo](https://i.imgur.com/TZQXZQk.jpg)

To use these overlays, you will need to place the CRT folder in your overlay folder on your Pi:

`/opt/retropie/configs/all/retroarch/overlay`

You will then be able to access them from the Quick Menu as seen below:
![CRT Directory](https://i.imgur.com/UrWeiaw.jpg)

1080p Settings | Value
:--- | ---:
Aspect Ratio | Custom
Custom Aspect Ratio X Pos | 480
Custom Aspect Ratio Y Pos | 180
Custom Aspect Ratio Width | 960
Custom Aspect Ratio Height | 720
Integer Scale | Off

Most of these overlays need a curved CRT shader to avoid cropping too much in the image corners. On my RetroPie setup, I use the CRT-Pi Curved shader with most settings at default, and this change:

Shader Variable | Value
:--- | ---:
Screen Curvature Vertical | 0.25
