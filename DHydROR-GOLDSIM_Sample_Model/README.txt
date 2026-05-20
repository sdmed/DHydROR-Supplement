# DHydROR-GoldSim-SWAT

This repository provides a reproducible implementation of the Dynamic Hydropower Reservoir Operation Routine (DHydROR), developed in the manuscript:

**Development of a Dynamic Hydropower Reservoir Operation Routine (DHydROR): A Complement to the SWAT Model for Downstream Reservoir Impact Assessment**

---

## 1. Purpose

This repository is provided to support:

- Peer review and methodological transparency  
- Reproducibility of the DHydROR framework  
- Independent evaluation of model structure and logic  
- Future adaptation and extension by researchers  

---

## 2. Repository Overview

This repository contains a simplified and fully documented implementation of the DHydROR framework, including:

- GoldSim-based model structure  
- Sample input datasets  
- Example simulation outputs  
- Model workflow documentation  
- Reproducibility guidance  

---

## 3. Software Requirements

To run the model, users require:

- Windows operating system (tested on Windows 10 64-bit or higher)  
- GoldSim simulation software (Academic, Professional, or equivalent license)  
- Microsoft Excel (or compatible CSV reader)  

Note: SWAT model outputs can be used as external inputs for coupling but are not required to execute the demonstration model.

---

## 4. Model Description

The included GoldSim model (`DHydROR_sample_model.gsm`) implements the core components of the DHydROR framework, including:

- Reservoir water balance simulation  
- Dynamic reservoir storage updating  
- Turbine discharge and hydropower generation  
- Spillway and environmental release operations  
- Evaporation and seepage losses  
- Sediment inflow and reservoir sedimentation impacts  
- Rule-based reservoir operation logic  

---

## 5. Input Data

Sample input datasets are provided both:

- embedded within the GoldSim model file  
- and as external Excel files for transparency  

Key inputs include:

- Reservoir inflow time series  
- Sediment inflow  
- Precipitation and potential evapotranspiration  
- Stage–storage–area relationships  
- Operation rule curves  
- Turbine and spillway parameters  
- Reservoir design characteristics  

---

## 6. Outputs

The model generates example outputs including:

- Reservoir storage dynamics  
- Release and spill volumes  
- Hydropower production  
- Sediment accumulation effects  
- System performance under operation rules  

---

## 7. Data Availability and Limitations

This repository provides a **simplified and representative version** of the DHydROR framework.

The original case-study datasets used in the manuscript (including observed reservoir operations and basin-specific hydrometeorological records) are not included due to external ownership and site-specific restrictions.

However, all methodological components required to understand, evaluate, and reproduce the modeling framework are provided.

---

## 8. Reproducibility Statement

The DHydROR framework is fully reproducible in terms of model logic, structure, and computational workflow. Execution of the native model file requires GoldSim software, which is a proprietary simulation environment.

---

## 9. Citation

If this repository is used in academic work, please cite the associated manuscript:

**[Insert full citation once published]**

---

## 10. Contact

Corresponding author: e.sadam91@gmail.com