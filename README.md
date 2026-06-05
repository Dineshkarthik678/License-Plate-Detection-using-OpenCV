# License-Plate-Detection-using-OpenCV

## Overview

This project demonstrates License Plate Detection using OpenCV and Haar Cascade Classifiers. The system detects vehicle license plates in images and highlights them with rectangular bounding boxes.

## Features

- Image Loading and Processing
- Haar Cascade-based License Plate Detection
- Grayscale Conversion
- Vehicle Plate Localization
- Bounding Box Visualization
- OpenCV Implementation

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Jupyter Notebook


## Algorithm

1. Load the input vehicle image.
2. Convert the image to grayscale.
3. Load the Haar Cascade XML classifier.
4. Detect license plate regions using `detectMultiScale()`.
5. Draw bounding rectangles around detected plates.
6. Display the result.

## Applications

- Traffic Monitoring
- Smart Parking Systems
- Toll Collection Systems
- Vehicle Tracking
- Security and Surveillance

## Requirements

```bash
pip install opencv-python matplotlib numpy
```

## Run the Project

1. Clone the repository:

```bash
git clone https://github.com/your-username/license-plate-detection-opencv.git
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Run:

```bash
_License Plate Detection.ipynb
```

## Future Enhancements

- Automatic Number Plate Recognition (ANPR)
- Real-time Video Detection
- OCR Integration using Tesseract
- Deep Learning-based Detection

## Author

**Dinesh karthik R**

## License

This project is licensed under the MIT License.
