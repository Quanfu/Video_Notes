# PixelAspectRatio

The ratio of the width to the height of an image is known as the aspect ratio, or more precisely the **display aspect ratio** (DAR) – the aspect ratio of the image as displayed; for TV, DAR was traditionally 4:3 (a.k.a. fullscreen), with 16:9 (a.k.a. widescreen) now the standard for HDTV. In digital images, there is a distinction with the **storage aspect ratio** (SAR), which is the ratio of pixel dimensions. If an image is displayed with square pixels, then these ratios agree; if not, then non-square, "rectangular" pixels are used, and these ratios disagree. The aspect ratio of the pixels themselves is known as the pixel aspect ratio (PAR) – for square pixels this is 1:1 – and these are related by the identity:
```
SAR × PAR = DAR.
```
Rearranging (solving for PAR) yields:
```
SAR × PAR = DAR.
```
PAR = DAR(**display aspect ratio**)/SAR(**storage aspect ratio**).

>For example, a 640 × 480 VGA image has a SAR of 640/480 = 4:3, and if displayed on a 4:3 display (DAR = 4:3) has square pixels, hence a PAR of 1:1. By contrast, a 720 × 576 D-1 PAL image has a SAR of 720/576 = 5:4, but is displayed on a 4:3 display (DAR = 4:3).



- Storage aspect ratio is the ratio of the image width to height in `pixels`, and can be easily calculated from the video file. 
- Display aspect ratio is the ratio of image width to height (in a unit of length such as `centimeters` or `inches`) when displayed on screen, and is calculated from the combination of pixel aspect ratio and storage aspect ratio.
