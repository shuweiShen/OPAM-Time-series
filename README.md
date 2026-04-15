# Time Series Prediction Training Strategy Implementation

This project implements a dedicated training strategy for **time series prediction**, supporting long-term time series forecasting tasks with standardized shell script-based workflows.

---

## Environment Setup
### Hardware
- NVIDIA RTX 3090 GPU

### Software
- Python 3.8
- PyTorch 1.7.1
- Additional dependencies are listed in `requirements.txt`

---

## Quick Start
All experiments are run via shell scripts. You can switch between training and testing modes by modifying the `is_training` parameter in the script.

### Example Usage
To run the long-term forecasting task on the ETTh1 dataset with the DLinear model:
```bash
bash scripts/long_term_forecast/ETT_script/DLinear_ETTh1.sh
