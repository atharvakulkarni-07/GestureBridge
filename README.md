# GestureBridge

## Overview

The **American Sign Language (ASL) Detector** is a machine learning project designed to recognize and interpret American Sign Language gestures using computer vision techniques. This project leverages deep learning models to process video input, identify hand signs, and translate them into text or speech.

## Features

- **Real-time Gesture Recognition**: Detects ASL signs in real-time using webcam input.
- **High Accuracy**: Utilizes state-of-the-art convolutional neural networks (CNNs) for improved accuracy in sign detection.
- **User-Friendly Interface**: Simple interface for users to interact with the system.
- **Multi-Sign Support**: Capable of recognizing multiple ASL signs and phrases.

## Technologies Used

- **Python**: The primary programming language for developing the application.
- **OpenCV**: For image processing and video capture.
- **TensorFlow/Keras**: For building and training deep learning models.
- **NumPy**: For numerical computations.
- **Matplotlib**: For visualizing training data and model performance.

## Installation

To set up the ASL Detector on your local machine, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/asl-detector.git
   cd asl-detector
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.x installed. Then, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   Start the ASL detection application:
   ```bash
   python main.py
   ```

## Usage

1. Launch the application.
2. Allow access to your webcam when prompted.
3. Perform ASL signs in front of the camera.
4. The system will display the recognized sign in real-time.

## Training the Model

If you wish to train your own model, follow these steps:

1. Prepare your dataset of ASL signs (images/videos).
2. Update the dataset path in the `config.py` file.
3. Run the training script:
   ```bash
   python train.py
   ```
4. The trained model will be saved in the `models/` directory.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to all contributors and researchers who have worked on gesture recognition technologies.
- Inspired by various open-source projects and research papers on sign language recognition.

## Contact

For any inquiries or feedback, please reach out via [your email] or open an issue in the GitHub repository.

---

Feel free to modify any sections as needed based on specific details of your project or additional features you may want to highlight!

Citations:
[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/4810014/488e6729-8c4b-4c76-9c3e-c93d87caae5e/ASL_Detection_FINAL.ipynb
