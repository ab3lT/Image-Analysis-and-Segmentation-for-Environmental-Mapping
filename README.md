# 🌍 Environmental Mapping using Undirected Graphical Models

This project implements an image analysis and segmentation pipeline for environmental mapping using **undirected graphical models (UGMs)**. It retrieves satellite imagery and elevation data of a specified location, segments the image to identify environmental features (forests, grassy areas), and visualizes them with color-coded boundaries based on distance from a reference point.

---

## 🚀 Features

- 📸 Satellite image retrieval of any geolocation (within 1000 ft radius)
- 🏔️ Elevation retrieval using Google Maps Elevation API
- 🧠 Segmentation using undirected graphical models (MRF/CRF)
- 🌲 Detection and classification of forests and grassy areas
- 🎨 Visualization with distance-based color-coded boundaries:
  - Blue: forests/grassy areas within 200 ft
  - Red: forests/grassy areas between 200 ft and 1000 ft
- 📊 Evaluation and performance analysis

---

## 🧱 Technologies Used

- Python
- OpenCV, NumPy, scikit-image – for image preprocessing
- NetworkX – for graphical model structure
- Matplotlib – for visualization
- Google Maps APIs / Earth Engine – for image and elevation data

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/env-mapping-ugm.git
cd env-mapping-ugm
pip install -r requirements.txt