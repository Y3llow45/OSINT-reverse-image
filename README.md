<div align="center">
  <h1>OSINT - Reverse an Image</h1>
  <img src="https://github.com/user-attachments/assets/30731402-2b37-4148-97b1-d3d1085ae93a" alt="OSINT" width="300px" />
</div>

## What will you learn?

You will learn how to use details like metadata, shadows, road signs, license plates, vegetation, letters and more to determine where an image was taken.

## Table of Contents
- [Introduction](#introduction)
- [Metadata](#metadata)
- [Uncrop](#uncrop)
- [AI](#ai)
- [Visual Clues](#visual-clues)
- [Useful Tools](#useful-tools--resources)
- [Other Resources](#other-resources)
- [Practice](#practice)

## Introduction
First, check the image’s metadata for the location. If that doesn’t work, open it in Photoshop and see if you can restore the original size (it might just be cropped non-destructively). AI upscalers help when using Google or Yandex image search. To find people, screenshot their face and upload it to PimEyes or similar sites. Identifying locations from road signs and buildings is hard but possible. Finally, use online tools to gather more info. Practicing on openguessr.com and geoguessr.com can help you a lot.

## Metadata
  **On Windows**
  1. Right click the image, go to properties and then details
  2. Use ExifTool by Phil Harvey

  **On Linux**
  1. Run ```mat2 image.jpg```

  **On Mac**
  1. Check "Photo info" in Finder or "Get info" from Photos app
  2. Download and use "Exif Metadata" app

  **Websites**
  1. jimpl.com - all photos are deleted after 24 hours
  2. exifdata.com - works just fine

## Uncrop
  Iphones and some androids crop images **non-destructively**. This means that the file still holds the original image and you can recover it.
  1. Open photoshop
  2. Select the crop tool
  3. Click and drag the crop handles outward
  4. Press enter

## AI
  **Upscale**
  1. <a href="https://www.iloveimg.com/upscale-image">iloveimg</a> <br>
  2. <a href="https://imgupscaler.com/">imgupscaler</a> <br>
  3. <a href="https://www.upscale.media/">upscale.media</a>
  
  **Location**
  1. <a href="https://picarta.ai/">picarta</a>
  2. <a href="https://geospy.ai/">geospy</a>

## Visual Clues
  * How to say "street" in every language <a href="https://www.indifferentlanguages.com/words/street">LINK</a> (usefull when you can see street signs)
  * Asian languages: <br> ![asian-languages](https://github.com/user-attachments/assets/363e8b5a-1879-4236-a41d-6ec33caaf22a)
  * USA highway signs: <br> ![roadsign-usa-01](https://github.com/user-attachments/assets/a7433440-0438-4700-921a-3e9bd1b53f5f)
  * Speed limit signs: <br>
  USA and Canada<br>
  ![roadsign-speed-usa-01](https://github.com/user-attachments/assets/80e3be8d-e1d8-4708-ad30-d513acaa6161)
  ![roadsign-speed-canada-01](https://github.com/user-attachments/assets/264577f0-6e04-46bc-8a06-a49eeba04515) <br>
  China: <br>
  ![Expwy_Spdlmt_CHN](https://github.com/user-attachments/assets/b900fe8a-36d2-498b-882b-4c4fe2ac9005) <br>

