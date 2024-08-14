# Perturbation AI Weather

This project involves downloading ERA5 data, testing the Pangu model, and examining perturbations for the Pangu model. It is based on the research presented in the paper "Potential Paradigm Shift in Hazard Risk Management: AI-Based Weather Forecast for Meteorological Hazards" by Kairui Feng, Dazhi Xi, Wei Ma, Cao Wang, Xuanhong Chen. https://arxiv.org/abs/2404.18440

## Requirements
To utilize these tools, you need to copy the respective Google Colab notebooks to your Google account. Therefore, a Google account is necessary.

you also need to download the pangu model from their github repo: https://github.com/198808xc/Pangu-Weather and download pangu_weather_24.onnx and put it under the proper paths.

## Resources

### Download ERA5 Data
Access the notebook to download ERA5 data here:
[Download ERA5 Data Notebook](https://colab.research.google.com/drive/1D_bpW6EUJE4o51J_UbEmrIX2Yfa8jBWf?usp=sharing)

### Reform ERA5 Data into Pangu Input
Access the notebook to reform ERA5 data for Pangu model input here:
[Reform ERA5 Data Notebook](https://colab.research.google.com/drive/1RBj24rU4HOiUUyA-hQC8IJiawK5v9P7z?usp=sharing)

### Run Pangu Model
This requires GPU support. You might need to subscribe to Colab Pro, which costs $10/month, and may require a credit card. Make sure the CUDA version is consistent with the requirements of the `onnxruntime-gpu` package. If the GPU is not utilized, check the ONNX website for troubleshooting.
Access the notebook to run the Pangu model here:
[Run Pangu Model Notebook](https://colab.research.google.com/drive/1COxeNXDhbG7_wWPklMmuM3Tkk7lNs61I?usp=sharing)

Hope you enjoy this project ^_^

