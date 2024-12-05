# AMITECC_Ex2

This repository belongs to a project carried out in the course "AI/ML in the Era of Climate Change" at TU Vienna in WS2024. The goal is to train and compare several baseline models on the LamaH daily timeseries dataset and perform a feature importance study. The target variable is the Fraction of water in topsoil "volsw_123" and subsoil "volsw_4".

### LamaH Dataset

**Source:**
The LamaH dataset (LArge-SaMple DAta for Hydrology and Environmental Sciences) is designed for large-sample studies and comparative hydrology in Central Europe. It covers the entire upper Danube to the state border of Austria–Slovakia, as well as all other Austrian catchments including their foreign upstream areas.[1](https://essd.copernicus.org/articles/13/4529/2021/)

**Data attributes:**
- **Temperature (°C)**
- **Wind Speed (m/s)**
- **Forecast Albedo**
- **Green Leaf Area**
- **Snow Water Equivalent (mm)**
- **Solar Radiation (W/m²)**
- **Surface Pressure (Pa)**
- **Total Evapotranspiration (mm)**
- **Precipitation (mm)**
- **Fraction of water in soil (m³/m³)**

### Preprocessing

1. Run `pip install -r requirements.txt`
2. Open `src/preprocessing.ipynb`
3. Run all chunks

Preprocessed data can then be found in `data/processed`.
