# Diabetic Retinopathy Detection

This project aims to develop a web-based platform for the detection of diabetic retinopathy using Convolutional Neural Networks (CNN). It provides an easy-to-use interface for users to upload retinal images and receive instant diagnoses.

## Features
- **Deep Learning**: Utilizes a CNN model for high-accuracy detection.
- **Web Interface**: Implemented using Flask, enabling user-friendly image uploads and result displays.
- **Pre-trained Model**: Includes a pre-trained model for immediate use.
- **Data Preprocessing**: Scripts for preparing and normalizing retinal image data.

## System Requirements
- Python 3.7+
- Flask
- TensorFlow/Keras
- OpenCV
- NumPy
- Pandas

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/aditya-singhhh/Diabetic_retinopathy.git
    cd Diabetic_retinopathy
    ```

2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask application:
    ```bash
    python app.py
    ```

## Usage

1. Start the Flask server.
2. Open your web browser and go to `http://127.0.0.1:5000/`.
3. Upload a retinal image to get the diagnosis.

## Project Structure

- `app.py`: Main Flask application script.
- `diabetic_retinopathy.ipynb`: Jupyter Notebook for data preprocessing, model training, and evaluation.
- `requirements.txt`: Python dependencies.
- `templates/`: HTML templates for the web application.


## Model Training

The model is trained using a dataset of retinal images. The training process involves:
1. Data augmentation and normalization.
2. CNN architecture design and compilation.
3. Model training and evaluation.

## Results

The trained model achieves high accuracy in detecting diabetic retinopathy. Detailed results and performance metrics are documented in `diabetic_retinopathy.ipynb`.

## Contributing

Contributions are welcome! Please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Acknowledgments

- [Kaggle Diabetic Retinopathy Dataset](https://www.kaggle.com/c/diabetic-retinopathy-detection)
- TensorFlow/Keras community
