# Spotify Tracks Unsupervised Audio Clustering & Genre Segmentation

An end-to-end unsupervised machine learning pipeline designed to parse, clean, and profile extensive audio libraries on Spotify. This project uses multi-variable statistical profiling to group songs by their actual sound qualities—like rhythm and instrumentation—rather than traditional genre labels alone.

## 🏢 Project Objective & Scope
The recommendation system behind platforms like Spotify groups music based on auditory signatures. This project builds an automated machine learning architecture that:
- Pre-processes and cleans structured audio metric tracking tables.
- Explores multi-variable attribute spacing using a Pearson Correlation matrix.
- Minimizes within-cluster variance using the **Elbow Method** to discover optimal cluster sizes.
- Constructs an optimal **K-Means Clustering** engine to group similar tracking records.
- Projects higher-dimensional clustering down to 2D visualization planes using **Principal Component Analysis (PCA)**.

---

## 📊 Core Data Architecture
The pipeline analyzes the following acoustic parameters:
* `danceability`: Rhythm stability and beat strength.
* `energy`: Perceived speed, loudness, and muscle activity.
* `loudness`: Overall volume profile in decibels (dB).
* `speechiness`: Presence of spoken words vs. instrumental sections.
* `acousticness`: Probability metric indicating whether acoustic strings are used.
* `instrumentalness`: Ratio of non-vocal audio elements.
* `liveness`: Detects the presence of an audience or live performance elements.
* `tempo`: The overall pace or beats per minute (BPM).

---

