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
  ### How to say "street" in every language <a href="https://www.indifferentlanguages.com/words/street">LINK</a> (usefull when you can see street signs)
  ### Asian languages: <br> ![asian-languages](https://github.com/user-attachments/assets/363e8b5a-1879-4236-a41d-6ec33caaf22a)
  ### USA highway signs: <br> ![roadsign-usa-01](https://github.com/user-attachments/assets/a7433440-0438-4700-921a-3e9bd1b53f5f)
  ### Speed limit signs: <br>
  USA and Canada<br>
  ![roadsign-speed-usa-01](https://github.com/user-attachments/assets/80e3be8d-e1d8-4708-ad30-d513acaa6161)
  ![roadsign-speed-canada-01](https://github.com/user-attachments/assets/264577f0-6e04-46bc-8a06-a49eeba04515) <br>
  China: <br>
  ![Expwy_Spdlmt_CHN](https://github.com/user-attachments/assets/b900fe8a-36d2-498b-882b-4c4fe2ac9005) <br>
  New Zealand and Australia: <br>
  ![New_Zealand_RG-3 svg](https://github.com/user-attachments/assets/8c0fd68b-3535-48ef-8a4d-71fc8c28f84b)
  ![Australia_road_sign_R4-1_(50) svg](https://github.com/user-attachments/assets/202e6577-125b-4ca4-8a4b-f5214c5b72f9) <br>
  Philippines and Indonesia: <br>
  ![Philippines_road_sign_R4-3_(40) svg](https://github.com/user-attachments/assets/59dfaf31-61aa-4e9a-9215-63a9017a94d9)
  ![Indonesia_New_Road_Sign_Pro_4h](https://github.com/user-attachments/assets/5224cb37-3f02-495f-a529-cf156e867594) <br>
  Argentina, Columbia and Chile: <br>
  ![Argentina_road_sign_R16 svg](https://github.com/user-attachments/assets/2b8e4fc8-7f01-4ad8-a0d1-a82a9f7769b4)
  ![Colombia_road_sign_SR-30A svg](https://github.com/user-attachments/assets/05eabe4c-b484-4c15-a874-260c54a6d2a9)
  ![Chile_road_sign_RR-2_(40) svg](https://github.com/user-attachments/assets/69ca97cb-a4b1-4bde-8684-5f7da11aab35) <br>
  UAE and Samoa: <br>
  ![UAE_Speed_Limit_-_60_kmh svg](https://github.com/user-attachments/assets/e618363b-9a85-4ca4-bc5d-7af124d5d302)
  ![Samoa_-_Speed_Limit svg](https://github.com/user-attachments/assets/be6d913f-3889-4088-8c80-a568a412c027) <br>
  UK and Ireland: <br>
  ![UK_traffic_sign_670V50 svg](https://github.com/user-attachments/assets/44eca7c1-cb62-4bf1-ad0b-ad590a54414c)
  ![IE_road_sign_RUS-043 svg](https://github.com/user-attachments/assets/19f4edaf-8b0a-446d-9edd-5fdbccac8d5f) <br>
  South Korea and Japan: <br>
  ![KR_road_sign_225-30 svg](https://github.com/user-attachments/assets/fc10a75c-e210-4edb-a872-ffcc728884b1)
  ![Japan_road_sign_323_(50) svg](https://github.com/user-attachments/assets/dae30e49-2835-4824-ab91-725dbf9b6151) <br>
  Germany:  <br>
  ![Zeichen_274 1_-_Beginn_einer_Tempo_30-Zone,_StVO_2013 svg](https://github.com/user-attachments/assets/9e16fe02-c949-48a3-b6be-04c9bed29d54)
  ![Zeichen_282_-_Ende_sämtlicher_Streckenverbote,_StVO_1970 svg](https://github.com/user-attachments/assets/a5f6081f-8398-46a8-9e25-6f14c9fdf68d) <br>
  France and Sweden: <br>
  ![France_road_sign_B30_(30) svg](https://github.com/user-attachments/assets/5092d89c-426e-40c1-999e-0081b9124e5e)
  ![Sweden_road_sign_C31-5 svg](https://github.com/user-attachments/assets/e400444d-e145-4202-8155-3cc7a886609c)
  ### Other road signs: <br>
  Kilometer signs in Slovenia: <br>
  ![roadsign-slovenia](https://github.com/user-attachments/assets/4ed84651-953a-4585-ab92-99bad1d58fa2) <br>
  Kilometer signs in Denmark: <br>
  ![roadsign-denmark](https://github.com/user-attachments/assets/d3c1decf-15bb-45cf-9987-4d769528467e) <br>
  Others <a href="https://en.wikipedia.org/wiki/Traffic_signs_by_country">HERE</a>
  ### Road lines:
  <a href="https://commons.wikimedia.org/wiki/Category:Road_markings_by_country">HERE</a>
  ### License plates:
  European cars have blue rectangle on the left.
  Portugal is the only European country with bright yellow on the right.
  USA vehicle license plate requirements: <a href="https://en.wikipedia.org/wiki/Vehicle_license_plates_of_the_United_States">HERE</a>
  <a href="http://www.worldlicenseplates.com/">MORE HERE</a>
