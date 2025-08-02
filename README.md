⚡ Power System Fault Detection and Classification

  This project aims to develop a machine learning-based system for rapid and accurate detection and classification of faults in a power distribution network using electrical   measurement data.


 📘 Project Overview

Power grids are vulnerable to various types of faults that can affect their stability and reliability. By utilizing supervised machine learning techniques, this project detects and classifies different types of electrical faults based on voltage and current phasors.

📌 Problem Statement

Design a system that uses electrical measurement data (e.g., voltage and current phasors) to detect and classify different types of faults in a power distribution system:

- Normal condition  
- Line-to-Ground Fault (LG)  
- Line-to-Line Fault (LL)  
- Double Line-to-Ground Fault (LLG)  
- Three-Phase Fault (LLL)

💡 Proposed Solution

We propose a supervised learning model trained on simulated or real-time data from PMUs or simulation tools like MATLAB/PSCAD:

🔧 Preprocessing
- Acquire synchronized voltage and current phasors.
- Label events as normal or specific fault types.

 📊 Feature Extraction
- Time-domain: RMS values, peak amplitude, zero-crossing rate  
- Frequency-domain: FFT coefficients, harmonic content  
- Phasor features: Magnitude and angle  
- Derived features: Sequence components, impedance trajectories  

 ⚙️ System Development Approach

The classification problem is approached in two stages:

1. Fault Detection (Binary Classification): Normal vs Fault  
2. Fault Type Classification (Multi-Class): LG, LL, LLG, LLL  

 📈 Algorithms
- LSTM Neural Networks (preferred for time series)
- ARIMA / Prophet (for classical time series forecasting)

 🧪 Results

The model successfully detects and classifies different fault types using simulation data, showing high accuracy in fault identification. This enhances fault response times and supports predictive maintenance.


 ✅ Conclusion

This system demonstrates a robust machine learning-based solution for power fault detection and classification. It builds a foundation for intelligent grid monitoring and predictive load management.
