# Face Mask Detection 😷

Real-time face mask detection system built with a custom CNN trained from scratch.

## Features
- Live webcam capture via Google Colab
- Custom dataset collected manually (with_mask / without_mask)
- CNN trained using TensorFlow/Keras
- Face detection using OpenCV Haar Cascade
- Displays bounding box + confidence percentage

## Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Google Colab
- scikit-learn
- NumPy

## Project Structure
dataset/
  with_mask/
  without_mask/
mask_detector.keras
mask_detection.ipynb
> Note: Dataset not included. Collect your own using the webcam cells in the notebook.
## How to Run
1. Open the `.ipynb` file in Google Colab
2. Run all cells in order
3. Collect your own dataset using the webcam cells
4. Train the model
5. Test real-time detection

## Result
Model classifies faces as **Mask** or **No Mask** with confidence percentage.

