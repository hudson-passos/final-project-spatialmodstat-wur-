# 🌿 Final Assignment

## 📄 Project Information

**Author:** Hudson Passos  
**Institution:** Wageningen University & Research (WUR)  
**Date:** April, 2024  
**Assignment Title:** *Flood Uncertainty Case 2024 – Maas & Waal Region*  
**Professors:** Sytze de Bruin and Gerard Heuvelink  
**Repository Name:** `research-project-internship-nioo`

---

## 🧭 Summary

As part of the course **GRS-30306 – Uncertainty Propagation**, we completed an assignment focused on understanding and quantifying the **impact of input uncertainties**—specifically, uncertainties in **elevation data** and **influx values**—on flood predictions in the **Maas and Waal region** following a hypothetical **dike failure**.

The assignment built on prior work using a flood simulation model and aimed to support evacuation planning by identifying areas where we could be **95% confident** that flooding would not occur after **48 or 72 hours**.

To address the task, we:

- Used a **Monte Carlo simulation** to generate and analyze hundreds of possible flood scenarios based on uncertain input data.
- Constructed a **geostatistical model of DEM uncertainty** (e.g., using variogram analysis and kriging), based on residuals between the DEM and ground-truth elevation points.
- Generated **100 realizations of the DEM** and **100 realizations of water influx**, assuming a normal distribution for the latter with parameters from the literature.
- Ran the flooding model for each combination of DEM and/or influx realizations to simulate a range of plausible flooding outcomes.
- Calculated spatial statistics such as the **mean**, **variance**, and **probability of flooding** across simulations.
- Identified regions that were **95% certain to remain unflooded**, based on probabilistic analysis of the results.
- Assessed the **relative contribution of elevation and influx uncertainty** to the variance in inundation depth, and visualized their spatial influence.
- Compiled all findings into a concise report answering **seven structured questions**, including maps, figures, and interpretations.

The project was carried out in small groups over the course of **five days**, with the final report submitted collectively and contributing **15%** to the course grade.  

---
_This project was completed as part of the GRS-30306 course at Wageningen University & Research._


