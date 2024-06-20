# :sleeping: Drowsiness Detection Using TensorFlow MobileNetV2  [![Tesorflow](https://skillicons.dev/icons?i=tensorflow)](https://skillicons.dev)

## Overview
This project leverages TensorFlow's MobileNetV2 architecture to develop a drowsiness detection system. The model is designed to identify signs of driver drowsiness, such as closed eyes, yawning, and head movements, using a custom dataset. The aim is to enhance driver safety by providing timely alerts when drowsiness is detected.

## Performance Analysis
### Quantitative Results
The TensorFlow MobileNetV2 model was trained and tested over 25 epochs, showing promising results:

- **Training Loss**: Stabilized at 0.28, indicating successful minimization of error during training.
- **Training Accuracy**: Reached 87%, demonstrating effective learning of drowsiness-related features from the training data.
- **Validation Accuracy**: Achieved 90.7%, slightly surpassing the training accuracy, which indicates strong generalization capabilities.
- **Validation Loss**: Recorded at 0.22, lower than the training loss, suggesting that the model is not overfitting and performs robustly on unseen data.

These results highlight the TensorFlow MobileNetV2 model's effectiveness and reliability in detecting drowsiness, with a good balance between learning the training data and generalizing to new data.

## Detailed Metrics
| Metric                    | Value    |
|---------------------------|----------|
| **Training Loss**         | 0.28     |
| **Training Accuracy**     | 87%      |
| **Validation Loss**       | 0.22     |
| **Validation Accuracy**   | 90.7%    |

## Model Performance Metrics
| Algorithm          | Accuracy | Precision | Recall | F1 Score | Missing Detection Score | Inference Time (seconds) |
|--------------------|----------|-----------|--------|----------|-------------------------|--------------------------|
| **TensorFlow MobileNetV2** | 0.47619  | 0.63636   | 0.50000 | 0.56000  | 0.00000                 | 9.63751                  |

## Results
<table>
  <tr>
    <td><img src="https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2/blob/main/results/accuracy.png" alt="Training Accuracy Plot" style="width: 400px;"></td>
    <td><img src="https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2/blob/main/results/loss.png" alt="Training Loss Plot" style="width: 400px;"></td>
    <td><img src="https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2/blob/main/results/val_accuracy.png" alt="Validation Accuracy Plot" style="width: 400px;"></td>
  </tr>
  <tr>
    <td><img src="https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2/blob/main/results/val_loss.png" alt="Validation Loss Plot" style="width: 400px;"></td>
    <td><img src="https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2/blob/main/results/all_plots.png" alt="All Training and Validation Plots" style="width: 400px;"></td>
  </tr>
</table>


## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/ParthJohri/Drowsiness_Detection_Using_Tensorflow_MobileNetV2.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Drowsiness_Detection_Using_Tensorflow_MobileNetV2
   ```
3. Train the model or test the results by starting the Jupyter Notebook


## Usage
1. Prepare your dataset with labeled images for training and testing.
2. Train the MobileNetV2 model using the provided training script.
3. Test the model on the test dataset to evaluate its performance.
4. Deploy the model for real-time driver monitoring to detect signs of drowsiness.

## Future Work
- **Model Optimization**: Further refine the MobileNetV2 model to enhance accuracy and reduce inference time.
- **Dataset Expansion**: Include more diverse datasets to improve model robustness and generalization.
- **Real-time Implementation**: Test the system in real-world driving scenarios to ensure practical applicability and reliability.

## Contributing
Contributions to improve the drowsiness detection system are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
