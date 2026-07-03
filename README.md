# EEG Signal Analysis Using MATLAB

A Biomedical Engineering project that performs EEG signal processing using MATLAB. This project analyzes healthy and epileptic EEG recordings by filtering the signals, extracting brain wave components, performing Fast Fourier Transform (FFT), and comparing brain wave powers.

---

## Project Overview

Electroencephalography (EEG) records the electrical activity of the brain. EEG signal analysis is widely used for studying neurological conditions such as epilepsy.

This project demonstrates a complete EEG signal processing workflow using MATLAB, including preprocessing, brain wave extraction, frequency analysis, and comparison of healthy and epileptic EEG signals.

---

##  Objectives

- Read EEG signals from EDF files
- Preprocess EEG signals using a Butterworth band-pass filter
- Extract Delta, Theta, Alpha, Beta, and Gamma brain waves
- Perform Fast Fourier Transform (FFT)
- Calculate brain wave power
- Compare healthy and epileptic EEG recordings
- Export results to Excel
- Save analysis figures automatically

---

##  Technologies Used

- MATLAB
- Signal Processing Toolbox
- EDF (European Data Format)
- Butterworth Band-pass Filter
- Fast Fourier Transform (FFT)
- Biomedical Signal Processing

---

##  Brain Wave Frequency Bands

| Brain Wave | Frequency Range | Brain Activity |
|------------|-----------------|----------------|
| Delta | 0.5 – 4 Hz | Deep Sleep |
| Theta | 4 – 8 Hz | Relaxation, Memory |
| Alpha | 8 – 13 Hz | Calmness, Eyes Closed |
| Beta | 13 – 30 Hz | Thinking, Concentration |
| Gamma | 30 – 45 Hz | Learning, Cognition |

---

##  Project Workflow

```text
EDF EEG File
      │
      ▼
Read EEG Signal
      │
      ▼
Band-pass Filtering (0.5–45 Hz)
      │
      ▼
Brain Wave Extraction
      │
      ▼
FFT Analysis
      │
      ▼
Brain Wave Power Calculation
      │
      ▼
Healthy vs Epilepsy Comparison
      │
      ▼
Results + Figures + Excel File
```

---

##  Repository Structure

```text
EEG-Signal-Analysis-Using-MATLAB
│
├── Code
│   ├── Main.m
│   └── analyzeEEG.m
│
├── Results
│   ├── Healthy_RawEEG.png
│   ├── Healthy_FilteredEEG.png
│   ├── Healthy_BrainWaves.png
│   ├── Healthy_FFT.png
│   ├── Healthy_vs_Epilepsy.png
│ 
│
└── README.md
```

---

##  Results

The project successfully:

- Processed healthy and epileptic EEG recordings
- Extracted all five brain wave frequency bands
- Calculated power for each brain wave
- Compared healthy and epileptic EEG signals
- Generated graphical visualizations
- Exported numerical results to Excel

---

##  How to Run

1. Open the project in MATLAB.
2. Place the EEG EDF files in the appropriate data folders.
3. Open `Main.m`.
4. Run the script.
5. MATLAB will:
   - Read EEG files
   - Filter the signals
   - Extract brain waves
   - Perform FFT analysis
   - Compare healthy and epileptic EEG
   - Save figures automatically
   - Export results to Excel

---

##  Dataset

This project uses publicly available EEG datasets from PhysioNet.

Healthy EEG Dataset:
https://physionet.org/

Epilepsy EEG Dataset:
https://physionet.org/content/chbmit/

Please download the datasets from PhysioNet and place them in the appropriate folders before running the project.

---

##  Future Improvements

- Multi-channel EEG analysis
- Automatic seizure detection
- Machine Learning classification
- Deep Learning based diagnosis
- Real-time EEG monitoring
- MATLAB GUI (App Designer)

---

## Author

**Rafia Mughal**

Undergraduate Biomedical Engineering Student

---

## ⭐ If you found this project useful, consider giving it a Star.
