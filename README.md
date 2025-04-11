# ECE57000---Project

## Overview


This project develops an end-to-end forecasting framework that leverages GPT-4 to automate time series modeling through three key capabilities: (1) automatic generation of optimized SARIMAX and Prophet models tailored to dataset characteristics, (2) iterative refinement of models using performance metrics (RMSE/MAE) as feedback, and (3) robust handling of real-world data challenges including missing value imputation and complex seasonality detection. By integrating large language models with statistical forecasting, the system reduces manual tuning efforts while maintaining interpretability through diagnostic checks and fallback mechanisms.

## Hardware Recommendation

For best performance, it is recommended to use a **T4 or higher GPU** Google Colab. This can be set by going to `Runtime > Change runtime type` and selecting **GPU** as the hardware accelerator.

### Running on Google Colab

1. Open Google Colab.
2. Upload the Jupyter Notebook from this repository.
3. Follow the instructions in the notebook to mount Google Drive and execute each cell.

Running on Google Colab is recommended to avoid compatibility issues and to make use of free GPU resources if needed

**Key Result**: 81% lower RMSE than traditional ARIMA on test data.


