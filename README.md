<div align="center">
  <h1>OSINT - Reverse an Image</h1>
  <img src="https://github.com/user-attachments/assets/30731402-2b37-4148-97b1-d3d1085ae93a" alt="OSINT" width="300px" />
</div>

---

## Overview

This repository provides a comprehensive guide to reverse-engineering images using Open Source Intelligence (OSINT) techniques. Learn how to extract and interpret details such as metadata, visual clues (e.g., shadows, road signs, license plates), and more to determine where an image was taken or uncover additional context.

---

## What Will You Learn?

- How to extract and analyze **metadata** for location data.
- Techniques to **uncrop** images and recover hidden details.
- Using **AI tools** for upscaling and location prediction.
- Identifying locations through **visual clues** like road signs, languages, and vegetation.
- Leveraging online tools and resources for deeper investigation.
- Practical exercises to sharpen your skills.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Metadata Analysis](#metadata-analysis)
3. [Uncropping Images](#uncropping-images)
4. [AI-Powered Tools](#ai-powered-tools)
5. [Visual Clues](#visual-clues)
   - [Languages and Street Signs](#languages-and-street-signs)
   - [Road Signs and Speed Limits](#road-signs-and-speed-limits)
   - [Road Markings and License Plates](#road-markings-and-license-plates)
   - [Additional Visual Indicators](#additional-visual-indicators)
6. [Other Resources](#other-resources)
7. [Practice Platforms](#practice-platforms)
8. [Contributing](#contributing)

---

## Introduction

Reversing an image to find its origin is a powerful OSINT skill. Start by checking the image’s **metadata** for embedded location data. If that’s unavailable, explore **non-destructive cropping** in tools like Photoshop to reveal hidden portions. Use **AI upscalers** to enhance details for reverse image searches on Google or Yandex, or employ facial recognition tools like PimEyes to identify people. Visual clues—road signs, architecture, or vegetation—can also pinpoint locations. Practice with platforms like GeoGuessr or Openguessr to refine your skills.

---

## Metadata Analysis

Metadata often contains GPS coordinates, timestamps, or camera details that reveal an image’s origin.

### Tools by Platform
- **Windows**:
  1. Right-click the image → Properties → Details tab.
  2. Use [ExifTool](https://exiftool.org/) by Phil Harvey (`exiftool image.jpg`).
- **Linux**:
  1. Install and run `mat2` (`mat2 image.jpg`) to view metadata.
- **Mac**:
  1. Finder → Right-click → Get Info, or use Photos app → "Photo Info".
  2. Download [Exif Metadata](https://apps.apple.com/us/app/exif-metadata/id12345678) app.
- **Online Tools**:
  1. [jimpl.com](https://jimpl.com/) – Deletes uploads after 24 hours.
  2. [exifdata.com](https://exifdata.com/) – Simple and reliable.

**Tip**: If metadata is stripped, look for clues in the filename (e.g., `IMG_20230215_123456` might hint at a date).

---

## Uncropping Images

Some devices (e.g., iPhones, certain Androids) crop images **non-destructively**, meaning the original data is still embedded.

### Steps in Photoshop
1. Open the image in Photoshop.
2. Select the **Crop Tool** (shortcut: `C`).
3. Drag the crop handles outward to reveal hidden areas.
4. Press **Enter** to apply.

**Alternative Tools**:
- [GIMP](https://www.gimp.org/) (free, open-source).
- Online editors like [Photopea](https://www.photopea.com/).

---

## AI-Powered Tools

AI can enhance low-quality images or predict locations based on visual content.

### Upscaling
Improve image resolution for better reverse search results:
1. [iloveimg](https://www.iloveimg.com/upscale-image)
2. [imgupscaler](https://imgupscaler.com/)
3. [upscale.media](https://www.upscale.media/)

### Location Prediction
AI tools that analyze image content for geolocation:
1. [Picarta](https://picarta.ai/)
2. [GeoSpy](https://geospy.ai/)
3. [Google Vision API](https://cloud.google.com/vision) (requires setup, detects landmarks).

### Reverse Image Search
- [Google Images](https://images.google.com/)
- [Yandex Images](https://yandex.com/images/)
- [TinEye](https://tineye.com/)

---

## Visual Clues

Analyze visual elements to narrow down locations when metadata is absent.

### Languages and Street Signs
- **"Street" in Different Languages**: [IndifferentLanguages](https://www.indifferentlanguages.com/words/street).
- **Identifying Scripts**: 
  - Asian languages: [Image Reference](https://github.com/user-attachments/assets/363e8b5a-1879-4236-a41d-6ec33caaf22a).
  - General guide: [Vox Language Maps](https://www.vox.com/2014/11/17/7082317/language-maps-charts).

### Road Signs and Speed Limits
- **USA Highways**: [Image](https://github.com/user-attachments/assets/a7433440-0438-4700-921a-3e9bd1b53f5f).
- **Speed Limits by Country**:
  - USA/Canada: [USA](https://github.com/user-attachments/assets/80e3be8d-e1d8-4708-ad30-d513acaa6161), [Canada](https://github.com/user-attachments/assets/264577f0-6e04-46bc-8a06-a49eeba04515).
  - China: [Image](https://github.com/user-attachments/assets/b900fe8a-36d2-498b-882b-4c4fe2ac9005).
  - New Zealand/Australia: [NZ](https://github.com/user-attachments/assets/8c0fd68b-3535-48ef-8a4d-71fc8c28f84b), [AU](https://github.com/user-attachments/assets/202e6577-125b-4ca4-8a4b-f5214c5b72f9).
  - Philippines/Indonesia: [PH](https://github.com/user-attachments/assets/59dfaf31-61aa-4e9a-9215-63a9017a94d9), [ID](https://github.com/user-attachments/assets/5224cb37-3f02-495f-a529-cf156e867594).
  - Argentina/Colombia/Chile: [AR](https://github.com/user-attachments/assets/2b8e4fc8-7f01-4ad8-a0d1-a82a9f7769b4), [CO](https://github.com/user-attachments/assets/05eabe4c-b484-4c15-a874-260c54a6d2a9), [CL](https://github.com/user-attachments/assets/69ca97cb-a4b1-4bde-8684-5f7da11aab35).
  - UAE/Samoa: [UAE](https://github.com/user-attachments/assets/e618363b-9a85-4ca4-bc5d-7af124d5d302), [Samoa](https://github.com/user-attachments/assets/be6d913f-3889-4088-8c80-a568a412c027).
  - UK/Ireland: [UK](https://github.com/user-attachments/assets/44eca7c1-cb62-4bf1-ad0b-ad590a54414c), [IE](https://github.com/user-attachments/assets/19f4edaf-8b0a-446d-9edd-5fdbccac8d5f).
  - South Korea/Japan: [KR](https://github.com/user-attachments/assets/fc10a75c-e210-4edb-a872-ffcc728884b1), [JP](https://github.com/user-attachments/assets/dae30e49-2835-4824-ab91-725dbf9b6151).
  - Germany: [Start](https://github.com/user-attachments/assets/9e16fe02-c949-48a3-b6be-04c9bed29d54), [End](https://github.com/user-attachments/assets/a5f6081f-8398-46a8-9e25-6f14c9fdf68d).
  - France/Sweden: [FR](https://github.com/user-attachments/assets/5092d89c-426e-40c1-999e-0081b9124e5e), [SE](https://github.com/user-attachments/assets/e400444d-e145-4202-8155-3cc7a886609c).
- **Other Signs**:
  - Kilometer signs: [Slovenia](https://github.com/user-attachments/assets/4ed84651-953a-4585-ab92-99bad1d58fa2), [Denmark](https://github.com/user-attachments/assets/d3c1decf-15bb-45cf-9987-4d769528467e).
  - Comprehensive list: [Traffic Signs by Country](https://en.wikipedia.org/wiki/Traffic_signs_by_country).

### Road Markings and License Plates
- **Road Lines**: [Road Markings by Country](https://commons.wikimedia.org/wiki/Category:Road_markings_by_country).
- **License Plates**:
  - Europe: Blue rectangle on the left; Portugal has yellow on the right.
  - USA: [Vehicle License Plates](https://en.wikipedia.org/wiki/Vehicle_license_plates_of_the_United_States).
  - Global: [World License Plates](http://www.worldlicenseplates.com/).

### Additional Visual Indicators
- **Driving Side**: [Left- vs Right-Hand Traffic](https://en.wikipedia.org/wiki/Left-_and_right-hand_traffic).
- **Vegetation**: Tropical plants suggest equatorial regions; coniferous trees indicate colder climates.
- **Architecture**: Unique styles (e.g., pagodas in East Asia, stucco in Mediterranean).
- **Shadows**: Sun position can indicate latitude and time of day (use [SunCalc](https://suncalc.org/)).

---

## Other Resources

- [OSINT Image Research Toolbox](https://github.com/The-Osint-Toolbox/Image-Research-OSINT) – Curated OSINT tools.
- [Forensically](https://29a.ch/photo-forensics/) – Free tool for image forensics (noise analysis, cloning detection).
- [OSINT Framework](https://osintframework.com/) – Broad OSINT resource directory.

---

## Practice Platforms

Hone your skills with these geolocation games:
- **GeoGuessr**: Paid, robust community, requires decent hardware. [Link](https://www.geoguessr.com/).
- **Openguessr**: Free, lightweight alternative. [Link](https://openguessr.com/).
- **WorldGuessr**: Free, occasionally glitchy. [Link](https://www.worldguessr.com/).

---

## Contributing

Have a tool, technique, or resource to add? Fork this repo, make your changes, and submit a pull request! Contributions are welcome to keep this guide comprehensive and up-to-date.
