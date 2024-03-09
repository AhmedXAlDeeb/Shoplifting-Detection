# Shoplifting Detection using ConvLSTM Architecture

## Introduction
Shoplifting detection is a critical component in ensuring the security of retail environments. Human Activity Recognition (HAR) AI systems play a crucial role in identifying and classifying human actions, including potentially suspicious activities such as shoplifting. This project, submitted during the Machathon competition held at the Information Technology Institute (ITI) and organized by the STP team, focuses on utilizing ConvLSTM (Convolutional Long Short-Term Memory) architecture for shoplifting detection.

## Team
- Ahmed Aldeeb
- Mostafa Ali
- Mohamed Hisham

## Human Activity Recognition (HAR)
Human Activity Recognition (HAR) systems involve the use of artificial intelligence to identify and categorize human actions based on sensor data or video feeds. In the context of shoplifting detection, HAR AI systems can analyze surveillance footage and flag activities that may indicate potential shoplifting incidents.

## Data Set
The dataset used in this project was provided by the STP team and was specifically curated for shoplifting detection. The dataset is divided into two labels: "shoplifter" and "non-shoplifter." This binary classification dataset serves as the foundation for training and evaluating the ConvLSTM model.

## Contributions
Our team tackled the shoplifting detection problem using ConvLSTM architecture and explored two approaches:

1. **Two-Model Fusion Approach:**
   - Divided the dataset into a labels: "check," "normal," "shoplifter," and "Buy"
   - Trained two separate models, each focusing on a subset of the classes.
   - Fused the results of both models to enhance the overall shoplifting detection accuracy.

2. **Single-Model Four-Class Approach:**
   - Divided the dataset into four labels: "check," "normal," "shoplifter," and "Buy"
   - Trained a single ConvLSTM model on all four classes, allowing the model to learn complex relationships between different activities.

Our goal was to explore the effectiveness of these approaches in improving the shoplifting detection capabilities of the ConvLSTM architecture.

## Usage
To replicate our experiments or integrate the ConvLSTM model into your shoplifting detection system, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/shoplifting-detection.git
   cd shoplifting-detection
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the provided Jupyter notebooks for training, evaluation, and result analysis.

Feel free to adapt and extend the codebase to meet your specific requirements.

## License
This project is licensed under the [MIT License](LICENSE).

If you have any questions or suggestions, please feel free to reach out to the project contributors.
