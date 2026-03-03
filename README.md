Computational modeling of retinal ganglion cell (RGC) spike trains using Generalized Linear Models (GLMs).  Analysis of stimulus encoding and spike-history effects to investigate neural response dynamics and temporal precision.

---

# Retinal Ganglion Cell Spike Modeling (GLM)

Brain Modeling project investigating neural encoding mechanisms in retinal ganglion cells through statistical modeling and spike-train analysis.

---

## Project Overview

This project studies how retinal ganglion cells encode visual stimuli into spike trains using Generalized Linear Models (GLMs).

Starting from stimulus-driven encoding, the model is progressively extended to include spike-history effects in order to capture refractoriness and temporal dependencies.

The analysis is performed at:

1. **Single-neuron level**, evaluating stimulus-response encoding.
2. **Model comparison level**, assessing improvements from spike-history inclusion.

---

## Model and Methodology

- **Statistical Framework:** Generalized Linear Models (GLMs)
- **Distributions Used:**
  - Linear-Gaussian model
  - Poisson GLM for spike counts
- **Stimulus Encoding:** Design matrix with temporal stimulus history
- **Spike-History Modeling:** Inclusion of past spike activity to capture refractoriness and adaptation
- **Evaluation Metrics:** R² score and model comparison
- **Simulation:** Spike-train generation from fitted GLMs
- **Visualization:** Raster plots, model predictions, variability analysis

---

## Parameter Analysis

The project investigates:

- Effect of stimulus-only encoding
- Contribution of spike-history terms
- Model generalization across neurons
- Variability comparison between observed and simulated spike trains

---

## Results and Insights

- Poisson GLM improves predictive performance over linear-Gaussian models.
- Inclusion of spike-history terms increases explanatory power.
- Spike-history modeling captures temporal precision beyond firing rate effects.
- Simulated spike trains reproduce key statistical properties of recorded neurons.
- Demonstrates dissociation between firing rate and temporal structure.

---

## Technical Details

- **Language:** Python  
- **Libraries:**  
  - Scientific Computing: numpy, scipy  
  - Statistical Modeling: statsmodels  
  - Visualization: matplotlib  

---

## Repository Structure

- `brain_modeling_glm_rgc.ipynb` – Full notebook implementation
- `requirements.txt` – Project dependencies

---

## Authors 

Daria Miele
Chiara Pierini
Marta Paniconi
