# AWS SageMaker Visual Inspection Automation

## Overview
This repository contains code and materials for automating **visual inspection tasks** using **AWS SageMaker**. It showcases how to use machine learning models to detect defects or anomalies in images, specifically in industrial automation scenarios, such as quality control.

## Contents
- **dist/**: Distribution-ready package for deployment.
- **docs/**: Documentation and guidelines for the project.
- **lib/**: Core libraries used in the project.
- **notebooks/**: Jupyter notebooks for data preparation, training, and model evaluation.
- **src/**: Source code for visual inspection automation.
- **solution-assistant.zip**: Pre-built solution package.
- **stack_outputs.json**: AWS CloudFormation stack output details.

## Requirements
You will need the following dependencies installed, which can be derived from the `notebooks/` and `src/` code:

- **boto3**: For AWS service interactions
- **sagemaker**: For using AWS SageMaker services
- **numpy**: Used for data manipulation
- **Pandas**: For data processing
- **Matplotlib**: For visualization
- **TensorFlow** or **PyTorch** (depending on the model used for training)
  
You can install these dependencies using:
```bash
pip install boto3 sagemaker numpy pandas matplotlib
```

## Usage

1. **Data Preparation**: Use the provided notebooks in the `notebooks/` folder to prepare your dataset for training the visual inspection model.
2. **Model Training**: Train models using AWS SageMaker by running the notebooks or scripts provided.
3. **Deployment**: Use the deployment scripts in `dist/` and `src/` to automate visual inspection tasks.

## License
This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for more information.
