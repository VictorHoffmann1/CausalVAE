# Causal Variational Autoencoder (Causal VAE)

This repository implements a Causal Variational Autoencoder (Causal VAE) with a focus on adaptability to different resource constraints and datasets. It is heavily influenced by Huawei Noah's Ark Causal VAE, with adaptations made to suit our specific needs.

## Features

- Implementation of a Causal VAE
- Adaptations for varying resource constraints (memory, GPU, disk storage)
- Support for multiple datasets: Flow and Pendulum

## Usage

To utilize this repository, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Training the Model**:
   - To train the model on a specific dataset (e.g., Flow), run:
     ```bash
     python run_flow.py
     ```

3. **Inference**:
   - After training, you can perform inference using:
     ```bash
     python inference_flow.py
     ```

## Datasets

This repository includes two datasets:

- Flow
- Pendulum

## Note

During both training and inference, the code will generate plots and store them in designated folders.

## Acknowledgements

This repository is heavily influenced by [Huawei Noah's Ark Causal VAE](https://github.com/huawei-noah/trustworthyAI).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.