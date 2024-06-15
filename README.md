# Space Network Intrusion Detection Using CNN-LSTM 🛡️

## Introduction

This project focuses on developing an intrusion detection system for a space network using a hybrid Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) model. The hybrid model combines the strengths of CNNs in feature extraction and LSTMs in handling sequential data, providing a robust and pretty accurate solution for detecting anomalies in network traffic.

## Dataset

📂 We used the synthetic space network data generated for this project , we tried to replicate as realistic as possible. This dataset includes various features such as duration, protocol type, service, flag, source and destination bytes, and an outcome label indicating normal or anomalous traffic.

Dataset not publicly available yet, as it is generated specifically for this project to simulate space network traffic. You can generate your own synthetic dataset using the provided code in the Jupyter Notebook.

## Models

🔍 The project implements a hybrid CNN-LSTM model for intrusion detection in space network data. The architecture includes:

1. **Convolutional Layer (Conv1D):** Extracts local features from the input data.
2. **MaxPooling Layer:** Reduces the dimensionality of the feature maps.
3. **LSTM Layers:** Captures sequential dependencies in network traffic.
4. **Dropout Layers:** Prevents overfitting by randomly setting a fraction of input units to zero.
5. **Dense Layers:** Fully connected layers leading to the final output.

## Model Performance Metrics

📊 The model performance is evaluated using the following metrics:

- **Accuracy:** Measures the overall correctness of the model.
- **Precision:** Indicates how many of the predicted positive cases were actually positive.
- **Recall:** Measures the ability of the model to identify positive cases.
- **F1 Score:** Harmonic mean of precision and recall, providing a single metric that balances both concerns.

## Code Structure

📁 The repository is organized as follows:

- `data/`: Directory containing the synthetic data used for training.
- `notebooks/`: Jupyter Notebooks with detailed steps and code.
- `models/`: Saved models after training.
- `README.md`: Project overview and instructions.
- `requirements.txt`: Requirements for the project 

## Usage

🚀 Follow these steps to use the repository:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/sivasakthi037/space-network-intrusion-detection.git
   cd space-network-intrusion-detection
   ```

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook and start exploring the models.**

4. **Open and Run Each Notebook:**
   Follow the sections in the Jupyter Notebook to generate data, preprocess it, visualize it, and train the CNN-LSTM model.

## Conclusion

📈 This project demonstrates the application of machine learning models for detecting intrusions in a simulated space network. By generating synthetic data, preprocessing it, and employing a hybrid CNN-LSTM architecture, we achieved promising results in detecting anomalies in network traffic.

## Acknowledgments

🙏 Special thanks to the contributors , other github users for your inspirations and open-source community for tools and libraries that made this project possible.

## Contribution

🛠️ Contributions are welcome! Whether you want to suggest improvements, submit bug reports, or add new features, feel free to open an issue or create a pull request.

Join us in building an intelligent defense system against network intrusions with machine learning. 🛡️🖥️💼

## License

📜 This project is licensed under the MIT License - see the LICENSE file for details.
