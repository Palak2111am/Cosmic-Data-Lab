## 🌌 Cosmic Data Lab — Astronomical Image Processing & Star Detection

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange" />
  <img src="https://img.shields.io/badge/Astronomy-FITS%20Data-purple" />
  <img src="https://img.shields.io/badge/Photutils-Star%20Detection-yellow" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
  <img src="https://img.shields.io/github/stars/Palak2111am/Cosmic-Data-Lab?style=social" />
</p>

This project demonstrates the fundamentals of **astronomical data analysis using Python**, including:

✅ Loading & visualizing FITS files
✅ ZScale contrast stretching like real telescopes
✅ Gaussian smoothing for noise reduction
✅ Star detection via DAOStarFinder (Photutils)
✅ Pixel statistics & histogram analysis
✅ Research-style astrophotography processing pipeline

Goal: build strong foundations in **observational astronomy + Python scientific computing** for future deep space ML projects.

---

## 📂 Project Structure

```
Cosmic-Data-Lab/
│── Cosmic_Data_Lab_FITS.ipynb     # Main notebook — FITS processing & star detection
│── HorseHead.fits                 # Sample dataset — Horsehead Nebula
│── requirements.txt               # Python dependencies
└── README.md
```

> Future planned structure:

```
data/    notebooks/   images/   results/   src/
```

---

## 🔭 Features

| Feature               | Description                               |
| --------------------- | ----------------------------------------- |
| FITS handling         | Telescope-style data loading & inspection |
| ZScale Stretch        | Observatory-standard contrast scaling     |
| Gaussian smoothing    | Noise suppression for faint sources       |
| DAOStarFinder         | Classical photometric star detection      |
| Overlay visualization | Stars marked on smoothed image            |
| Pixel histogram       | CCD-style pixel distribution (log scale)  |

---

## 📸 Example Results

* Histogram of pixel intensities (log scale)
* Smoothed frame + detected stars highlighted
* Detection result: **~82 stars in the Horsehead Nebula frame**

> Plots available inside the notebook

---

## 🛠️ Installation

### 1️⃣ Create python environment

```bash
python -m venv astroenv
astroenv\Scripts\activate      # Windows
source astroenv/bin/activate   # Mac/Linux
```

### 2️⃣ Install required libraries

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Notebook

```bash
jupyter notebook
```

Open:

```
Cosmic_Data_Lab_FITS.ipynb
```

---

## 📚 Library Purpose

| Library       | Purpose                         |
| ------------- | ------------------------------- |
| Astropy       | FITS, astronomy utilities, WCS  |
| Photutils     | Star detection & photometry     |
| NumPy / SciPy | Numerical processing            |
| Matplotlib    | Data visualization              |
| Jupyter       | Interactive scientific workflow |

---

## 🌌 Astrophysics Theory Background

This notebook uses standard astronomy methods:

### Image Science Concepts

* FITS Format — **NASA/ESO astronomical data standard**
* Z-scale stretch — telescope image scaling technique
* Gaussian smoothing — denoising faint signals
* DAOStarFinder — **Stetson (1987)** stellar photometry algorithm

### Key References

**Primary Papers & Books**

* Stetson, P. — *DAOPHOT: Stellar Photometry Program* (1987)
* Berry & Burnell — *Astronomical Image Processing*
* Carroll & Ostlie — *Modern Astrophysics*
* Howell — *Handbook of CCD Astronomy*
* Bevington & Robinson — *Data Reduction & Error Analysis*

**Official Docs**

* Astropy — [https://docs.astropy.org](https://docs.astropy.org)
* Photutils — [https://photutils.readthedocs.io](https://photutils.readthedocs.io)
* NASA HEASARC FITS Guide — [https://heasarc.gsfc.nasa.gov/docs/fcg/](https://heasarc.gsfc.nasa.gov/docs/fcg/)

---

## 🎯 Roadmap

🚀 Short-term

* Aperture photometry & magnitude measurements
* Add output images in `/images` folder
* Add `/data` & `/notebooks` directory structure

🧠 Long-term

* ML pipeline for galaxy/star classification
* Integrate SDSS / HST data
* WCS Calibration (Sky coordinates, RA/DEC)

---

## 👩‍🚀 Author

**Palak Patel**
Aspiring Astrophysicist & Data Scientist
Research Interests: *Astronomy × Python × ML × Scientific Computing*

---

## 📄 License

MIT License — free for learning and research.

---

## 🤝 Contributing

Pull requests welcome!
If you'd like to collaborate on astronomy ML, exoplanets, gravitational waves, or telescope data — I'm happy to connect 🚀

---

### ⭐ If you like this project, please star the repo!


