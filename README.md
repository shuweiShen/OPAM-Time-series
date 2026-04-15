Time Series Prediction Training Strategy Implementation
This project implements a dedicated training strategy for time series prediction, supporting long-term time series prediction tasks and providing a standardized script-based running method.
Environment Configuration
Hardware Environment
Graphics Card: NVIDIA RTX 3090
Software Environment
Python 3.8
PyTorch 1.7.1
Other dependent libraries are detailed in requirements.txt
Quick Start
The project runs training/testing with one click through Shell scripts, and the core mode is switched by modifying the is_training parameter in the script:
Running Example
Take the long-term forecast task (ETTh1 dataset + DLinear model) as an example:
bash

# Execute the prediction script
bash scripts/long_term_forecast/ETT_script/DLinear_ETTh1.sh
Mode Switching
Training Mode: Open the corresponding script file and set the parameter is_training to 1
Testing/Prediction Mode: Set the parameter is_training to 0
Custom Running
You can customize according to your own needs:
Write the corresponding Shell script
Modify the dataset, model, hyperparameters and other configurations in the script
Execute the custom script to complete training/prediction
Project Structure
plaintext
├── scripts/                 # Running script directory
│   └── long_term_forecast/  # Long-term forecast scripts
└── ...                     # Core project code
