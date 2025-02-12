<div align="center">
  <h1>OSINT - Reverse an Image</h1>
  <img src="https://github.com/user-attachments/assets/30731402-2b37-4148-97b1-d3d1085ae93a" alt="OSINT" width="300px" />
</div>

## What will you learn?

You will learn how to use details like metadata, shadows, road signs, license plates, vegetation, letters and more to determine where an image was taken.

## Table of Contents
- [Introduction](#introduction)
- [Metadata](#metadata)
- [AI](#ai)
- [Visual Clues](#visual-clues)
- [Useful Tools](#useful-tools--resources)
- [Other Resources](#other-resources)
- [Practice](#practice)

## Introduction
First thing you should try is finding the location from the image's metadata. If that didn't work open the image in photoshop and try to see if you can restore the image to it's original
state ( The image could be croppped and you might be able to restore it's full size). AI image upscale websites are very usefull when you have to do image search using google or yandex.
You can try to find people from the image by screenshoting their face and uploading it to pimeye.com or similar. Finding the location from road signs and buildings is hard but not imposible.
Finnaly you can try to gather more info by using online tools. Practicing on openguessr.com and geoguessr.com would help you a lot.

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
