<div align="center">
  <h1>OSINT - Reverse an Image</h1>
  <img src="https://github.com/user-attachments/assets/30731402-2b37-4148-97b1-d3d1085ae93a" alt="OSINT" width="300px" />
</div>

---

## Overview

This repository is your go-to guide for reverse-engineering images using Open Source Intelligence (OSINT) techniques. Discover how to extract location data and context from images by analyzing **metadata**, **visual clues** (e.g., shadows, road signs, architecture), and leveraging cutting-edge tools. Whether you're a beginner or seasoned investigator, this repo will help you uncover the stories behind the pixels.

---

## What Will You Learn?

- Extracting **metadata** (e.g., GPS, timestamps) from images.
- Recovering hidden details via **uncropping** and forensic analysis.
- Using **AI tools** for upscaling, geolocation, and facial recognition.
- Decoding **visual clues** like signs, flora, and cultural markers.
- Mastering online resources and search engines for deeper insights.
- Practicing geolocation with interactive platforms.

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
6. [Forensic Techniques](#forensic-techniques)
7. [Other Resources](#other-resources)
8. [Practice Platforms](#practice-platforms)
9. [Contributing](#contributing)

---

## Introduction

Images are treasure troves of information—if you know how to dig. Start with **metadata** to find GPS coordinates or timestamps. No luck? Try **uncropping** in Photoshop to reveal hidden edges. Use **AI tools** to upscale blurry details or predict locations. Analyze **visual clues** like road signs or vegetation to narrow down regions. Combine these with reverse image searches (Google, Yandex, etc.) and facial recognition (e.g., PimEyes) to unlock identities or origins. Practice makes perfect—test your skills on GeoGuessr or similar platforms.

---

## Metadata Analysis

Metadata can reveal where and when an image was taken, often embedded as EXIF (Exchangeable Image File) data.

### Tools by Platform
- **Windows**:
  1. Right-click → Properties → Details tab.
  2. [ExifTool](https://exiftool.org/) (`exiftool -a -G image.jpg` for verbose output).
- **Linux**:
  1. `mat2 image.jpg` (install via `sudo apt install mat2`).
  2. `exiv2 image.jpg` for detailed metadata extraction.
- **Mac**:
  1. Finder → Right-click → Get Info, or Photos app → "Photo Info".
  2. [Exif Metadata](https://apps.apple.com/us/app/exif-metadata/id12345678) app.
- **Online Tools**:
  1. [jimpl.com](https://jimpl.com/) – Deletes uploads after 24 hours.
  2. [exifdata.com](https://exifdata.com/) – Quick and reliable.
  3. [fotoforensics.com](https://fotoforensics.com/) – Includes EXIF and error-level analysis.

**Pro Tip**: Look for camera serial numbers in EXIF to link images taken by the same device. Watch out for stripped metadata—filenames like `20230215_123456.jpg` might still hint at dates.

---

## Uncropping Images

Non-destructive cropping (common on iPhones/Androids) hides original data that you can recover.

### Steps in Photoshop
1. Open image in Photoshop.
2. Select **Crop Tool** (`C`).
3. Drag handles outward to reveal hidden areas.
4. Press **Enter**.

### Alternative Tools
- [GIMP](https://www.gimp.org/) – Free, open-source alternative.
- [Photopea](https://www.photopea.com/) – Browser-based editor.
- [XnView](https://www.xnview.com/) – Lightweight viewer with crop recovery.

**New Clue**: Check for subtle reflections or shadows in uncropped areas—they might reveal additional objects or people.

---

## AI-Powered Tools

AI enhances images, predicts locations, and identifies faces or objects.

### Upscaling
Boost resolution for clearer details:
1. [iloveimg](https://www.iloveimg.com/upscale-image)
2. [imgupscaler](https://imgupscaler.com/)
3. [upscale.media](https://www.upscale.media/)
4. [letsenhance.io](https://letsenhance.io/) – AI-driven enhancement.

### Location Prediction
AI guesses where an image was taken:
1. [Picarta](https://picarta.ai/) – Predicts global coordinates.
2. [GeoSpy](https://geospy.ai/) – Analyzes backgrounds.
3. [Google Vision API](https://cloud.google.com/vision) – Detects landmarks (requires API key).

### Reverse Image Search
Find where an image appears online:
- [Google Images](https://images.google.com/) – Use the camera icon.
- [Yandex Images](https://yandex.com/images/) – Superior for faces and unique images.
- [TinEye](https://tineye.com/) – Tracks image history.
- [Bing Visual Search](https://www.bing.com/visualsearch) – Crop-specific search.

### Facial Recognition
Identify people in photos:
1. [PimEyes](https://pimeyes.com/) – Searches the web for faces.
2. [Search4faces](https://search4faces.com/) – Free face search engine.

**New Addition**: Use [Lenso.ai](https://lenso.ai/) for reverse image searches tailored to people, places, or duplicates.

---

## Visual Clues

When metadata fails, visual elements can pinpoint locations.

### Languages and Street Signs
- **"Street" Translations**: [IndifferentLanguages](https://www.indifferentlanguages.com/words/street).
- **Scripts**:
  - Asian languages: [Image](https://github.com/user-attachments/assets/363e8b5a-1879-4236-a41d-6ec33caaf22a).
  - Guide: [Vox Language Maps](https://www.vox.com/2014/11/17/7082317/language-maps-charts).
- **OCR Tools**: Use [Google Lens](https://lens.google.com/) or [Tesseract](https://github.com/tesseract-ocr) to extract text from signs.

### Road Signs and Speed Limits
- **USA Highways**: [Image](https://github.com/user-attachments/assets/a7433440-0438-4700-921a-3e9bd1b53f5f).
- **Speed Limits**:
  - USA/Canada: [USA](https://github.com/user-attachments/assets/80e3be8d-e1d8-4708-ad30-d513acaa6161), [Canada](https://github.com/user-attachments/assets/264577f0-6e04-46bc-8a06-a49eeba04515).
  - China: [Image](https://github.com/user-attachments/assets/b900fe8a-36d2-498b-882b-4c4fe2ac9005).
  - New Zealand/Australia: [NZ](https://github.com/user-attachments/assets/8c0fd68b-3535-48ef-8a4d-71fc8c28f84b), [AU](https://github.com/user-attachments/assets/202e6577-125b-4ca4-8a4b-f5214c5b72f9).
  - More: [Traffic Signs by Country](https://en.wikipedia.org/wiki/Traffic_signs_by_country).
- **New Clue**: Look for sign shapes—octagons (stop) are universal, but colors vary (e.g., yellow in Japan).

### Road Markings and License Plates
- **Road Lines**: [Road Markings by Country](https://commons.wikimedia.org/wiki/Category:Road_markings_by_country).
- **License Plates**:
  - Europe: Blue rectangle on left; Portugal’s yellow on right.
  - USA: [Vehicle License Plates](https://en.wikipedia.org/wiki/Vehicle_license_plates_of_the_United_States).
  - Global: [World License Plates](http://www.worldlicenseplates.com/).
- **New Clue**: Plate fonts and sizes differ—e.g., Germany uses a distinct DIN Next Pro font.

### Harbors
- **Most Important**: [Harbors](https://en.wikipedia.org/wiki/Harbor#Important_harbors).
- On most harbors the edge line is painted yellow and the box is gray. There is only one box in europe that is painted yellow and it is in Reykjavik, Iceland.

### Additional Visual Indicators
- **Driving Side**: [Left- vs Right-Hand Traffic](https://en.wikipedia.org/wiki/Left-_and_right-hand_traffic).
- **Vegetation**: Palm trees suggest tropics; birch trees point to northern climates.
- **Architecture**: Pagodas (East Asia), windmills (Netherlands), adobe (Southwest USA).
- **Shadows**: Use [SunCalc](https://suncalc.org/) to estimate latitude/time.
- **Weather**: Snow narrows to winter regions; monsoons suggest South Asia.
- **New Clue**: Utility poles vary—wooden in rural USA, concrete in Europe.

---

## Forensic Techniques

Go beyond the surface with image forensics.

- **Error Level Analysis (ELA)**: [FotoForensics](https://fotoforensics.com/) detects edits by analyzing compression artifacts.
- **Noise Analysis**: [Forensically](https://29a.ch/photo-forensics/) highlights tampering via noise patterns.
- **Magnification**: Zoom in on reflections (e.g., eyes, windows) for hidden details.
- **New Tool**: [Ghiro](http://www.getghiro.org/) – Open-source forensic analyzer for batch processing.

**New Clue**: Check for digital artifacts—JPEG compression quirks can reveal editing software used.

---

## Other Resources

- [OSINT Framework](https://osintframework.com/) – Directory of OSINT tools.
- [The-OSINT-Toolbox](https://github.com/The-Osint-Toolbox/Image-Research-OSINT) – Image-specific tools.
- [Bellingcat Toolkit](https://www.bellingcat.com/resources/) – Investigative guides.
- [Mapillary](https://www.mapillary.com/) – Crowdsourced street imagery.

---

## Practice Platforms

Sharpen your geolocation skills:
- **GeoGuessr**: Paid, community-driven. [Link](https://www.geoguessr.com/).
- **Openguessr**: Free, lightweight. [Link](https://openguessr.com/).
- **WorldGuessr**: Free, quirky. [Link](https://www.worldguessr.com/).
- **Sporcle Geography Quizzes**: [Link](https://www.sporcle.com/games/category/geography).

---

## Contributing

Got a new tool or clue? Fork this repo, add your insights, and submit a pull request. Let’s make this the ultimate OSINT image resource!
