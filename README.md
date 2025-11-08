## 🌌 Cosmic Data Lab — Astronomical Image Processing & Star Detection

This project explores astronomical data analysis using Python, focusing on:

* ✅ Loading & visualizing FITS images
* ✅ Noise smoothing & contrast scaling (ZScale)
* ✅ Detecting stars using DAOStarFinder (photutils)
* ✅ Plotting detected sources on astronomical images
* ✅ Pixel intensity statistics & histogram analysis

The goal is to build practical experience in **astronomical data science & observational astronomy techniques**, similar to workflows used in research pipelines for telescopic images.

---

## 📂 Project Structure

```
Cosmic-Data-Lab/
│
├── Cosmic_Data_Lab_FITS.ipynb     # Main notebook — FITS processing & star detection
├── HorseHead.fits                 # Sample FITS file (Horsehead Nebula)
└── README.md
```

> Future additions will include: `.fits` data directory, photometry scripts, and ML galaxy classification.

---

## 🔭 Features

| Feature            | Description                              |
| ------------------ | ---------------------------------------- |
| FITS handling      | Load and inspect space-telescope images  |
| Z-Scale Stretch    | True astronomical intensity scaling      |
| Gaussian smoothing | Reduce noise for faint object detection  |
| Star detection     | `DAOStarFinder` from Photutils           |
| Astrometry plots   | Overlay detected star positions          |
| Data stats         | Min/max/mean/std histogram with log axis |

---

## 🛰️ Sample Results

* Pixel statistics printed for FITS image
* Log-scaled pixel histogram
* Detected stars highlighted on smoothed image
* Detection count example:

  ```
  ✅ Detected ~82 stars in Horsehead Nebula frame
  ```

> *(Image outputs visible inside the notebook)*

---

## 🛠️ Installation

### ✅ 1. Create a Virtual Environment (recommended)

```bash
python -m venv astroenv
source astroenv/bin/activate   # Mac/Linux
astroenv\Scripts\activate      # Windows
```

### ✅ 2. Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install astropy photutils numpy scipy matplotlib
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

## 📦 Data Source

* **Horsehead Nebula FITS Image** — downloaded from Astropy tutorial archive
  *(Public astrophysics education dataset)*

---

## 🎯 Future Roadmap

* 🌠 Add more telescope FITS images (HST, SDSS)
* ⭐ Aperture photometry & magnitude estimation
* 🧠 Machine learning — galaxy/star classification
* 📂 `/notebooks`, `/data`, `results/` folders
* 🌌 Integrate Astropy WCS (coordinate system)

---

## 👩‍🚀 Author

**Palak Patel**
Aspiring Astrophysicist & Data Scientist
Focus: *Astronomy x Machine Learning x Python*

---

## 📄 License

This project is open-source for learning & research use.

---

## 🤝 Contributions

Pull requests & suggestions are welcome!
If you'd like to collaborate on astronomy ML, spectroscopy, exoplanets, or gravitational-wave data — let’s connect 🚀

---

### ⭐ If you found this useful, star the repo!


