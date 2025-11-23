# CloudEye - Autonomous Methane Detection System

## Team: DIGAMBARA
**Team Leader:** AYUSH KUSHWAHA

---

## Project Overview

CloudEye is an AI-powered satellite system for the real-time detection, monitoring, and reporting of methane emissions from industrial sites. Our solution uses onboard edge-AI to identify methane leaks, alert authorities, and globally escalate if action isn’t taken—enabling fast response for climate impact.

---

## Competition Details

- **Hackathon:** SkyHack 2025
- **Track:** AI-Driven Autonomous Satellite Systems & AI/ML for Space Data Interpretation
- **Team Name:** DIGAMBARA
- **Team Leader:** AYUSH KUSHWAHA

---

## Demo Video

Watch our demonstration video here:  
(https://drive.google.com/file/d/14ocfSOq1_w4vkd5FxvHE1RRhRKrg1zAA/view?usp=drivesdk)

---

## How CloudEye Works

1. **Satellite Imaging:** Satellite captures high-res images of industry sites.
2. **Methane Detection:** Edge-AI model analyzes images for methane plumes in real-time.
3. **Smart Alerts:**  
   - Local authorities get secure alert if a leak is found.
   - If not fixed in 39 days, global organizations & media are notified automatically.
4. **Global Impact:** Enables accountability, rapid mitigation, and policy action.

---

## Project Files

- Demo video (see link above)
- Sample plume detection code (Python, see below)
- PDF/PPT slides (shared separately if required)

---

## Sample Code: Methane Plume Detection (Python)
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
