# Rainfall Erosivity and Soil Loss Estimation (EI30 + USLE)

## Overview
This project estimates rainfall-induced soil erosion using the EI30 method and the Universal Soil Loss Equation (USLE). It demonstrates how rainfall intensity influences erosion potential in agricultural environments.

---

## Objective
To analyze rainfall data and compute:
- Rainfall intensity (I30)
- Kinetic energy of rainfall
- Rainfall erosivity index (EI30)
- Soil loss using USLE

---

## Methodology

1. Converted rainfall data into minute-level time series  
2. Applied sliding 30-minute window to compute I30  
3. Calculated kinetic energy using empirical relationships  
4. Computed EI30  
5. Estimated soil loss using USLE  

---

## Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## Results
- I30 ≈ 8 mm/hr (moderate intensity)
- Computed total kinetic energy of rainfall
- Estimated soil loss for the event

---

## Files in Repository
- `rainfall_data.xlsx` → Input rainfall dataset  
- `ei30_analysis.ipynb` → Full analysis notebook  

---

## Google Colab Notebook
[Open in Colab](https://colab.research.google.com/drive/1DX5opvqnIaHspnt84-hM3nZAMdmEgfxa?usp=sharing)

---

## Key Insight
Short-duration high-intensity rainfall plays a critical role in soil erosion, even when total rainfall is moderate.

---


