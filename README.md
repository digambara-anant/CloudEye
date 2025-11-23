# CloudEye - Advanced Dual-Camera AI Methane Detection Satellite

## Team: DIGAMBARA
**Team Leader:** AYUSH KUSHWAHA

---

## Project Overview

CloudEye is an advanced autonomous satellite system equipped with two powerful cameras:
- **Normal Camera:** For standard high-resolution Earth imaging.
- **OGI Camera (Optical Gas Imaging):** Specialized to detect methane gas plumes invisible to the naked eye.

The satellite uses edge-AI to process images in real-time, detect methane leaks from industrial facilities, identify responsible companies using online databases, and send instant alerts to both industry and government agencies. If not fixed within 39 days, global organizations and the public are notified—creating full transparency and accountability.

---

## Competition Details

- **Hackathon:** SkyHack 2025
- **Track:** AI-Driven Autonomous Satellite Systems & AI/ML for Space Data Interpretation
- **Team Name:** DIGAMBARA
- **Team Leader:** AYUSH KUSHWAHA

---

## How CloudEye Works

1. **Satellite Imaging:** Dual-camera scan of industrial zones from orbit.
2. **Methane Detection:** OGI camera and AI confirm plume presence with high accuracy.
3. **Auto-Identification:** AI matches image locations to actual companies/plants via Google Maps, public databases, and regulatory records.
4. **Instant Alerts:** 
   - Sends direct warning to company/industry responsible.
   - Simultaneous message to the national government/authorities.
5. **39-Day Protocol:** If the leak isn’t resolved in 39 days:
   - Satellite’s system escalates alerts to UN, news agencies, and social media for global awareness.
   - Transparent log of notifications and evidence is maintained.

---

## Demo Video

Watch our full conceptual demonstration:  
[CloudEye Demo Video (Google Drive)](https://drive.google.com/file/d/14ocfSOq1_w4vkd5FxvHE1RRhRKrg1zAA/view?usp=drivesdk)

---

## Sample Detection Code
import cv2
import numpy as np
from matplotlib import pyplot as pltimg = cv2.imread('sample_satellite_methane.jpg', 0)
_, plume = cv2.threshold(img, 180, 255, cv2.THRESH_BINARY)
plt.subplot(1,2,1)
plt.title("Original Image")
plt.imshow(img, cmap='gray')
plt.subplot(1,2,2)
plt.title("Detected Methane Plume")
plt.imshow(plume, cmap='hot')
plt.show()

---

## Team Members

1. **AYUSH KUSHWAHA** – Team Leader / Project Architect
2. **Raju Singh** - Peoject's programming done by him

---

## License

This project is for educational and competition purposes – SkyHack 2025.

---

## Contact

**AYUSH KUSHWAHA** (Team DIGAMBARA Leader)  
Email: ayushkush2023@gmail.com
---
