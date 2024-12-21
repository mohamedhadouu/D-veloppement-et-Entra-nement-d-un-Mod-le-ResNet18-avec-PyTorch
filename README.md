# ResNet18 Implementation with PyTorch

This repository contains the implementation and training of a ResNet18 model using PyTorch for image recognition tasks. The project demonstrates key steps in deep learning workflows, including data preprocessing, model definition, optimization, and performance evaluation.

## Features

- Implementation of ResNet18 architecture using PyTorch.
- Training pipeline with custom dataset support.
- Performance evaluation with accuracy metrics and visualizations.

## Requirements

The project requires the following dependencies:

- Python 3.8+
- PyTorch
- Torchvision
- NumPy
- Matplotlib

You can install the dependencies using the following command:

```bash
pip install torch torchvision numpy matplotlib
```

## Usage

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/yourusername/resnet18-pytorch.git
    cd resnet18-pytorch
    ```

2. **Prepare Dataset:**

    - Place your dataset in the `data/` directory.
    - Update the data loading script if necessary to handle your dataset.

3. **Run Training Script:**

    ```bash
    python train.py
    ```

4. **Evaluate the Model:**

    Use the evaluation script to assess model performance on test data:

    ```bash
    python evaluate.py
    ```

## Project Structure

- `train.py`: Script for training the ResNet18 model.
- `evaluate.py`: Script for evaluating the model on test data.
- `model.py`: Definition of the ResNet18 architecture.
- `utils.py`: Utility functions for data loading, preprocessing, and visualization.
- `data/`: Directory for storing datasets.

## Results

The ResNet18 model achieved high accuracy on the test dataset, showcasing its robustness for image recognition tasks. Detailed results and visualizations can be found in the `results/` directory.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
