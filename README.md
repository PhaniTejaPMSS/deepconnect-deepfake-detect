# DeepConnect

## Overview

DeepConnect is a powerful tool designed to detect deepfake video content using frame-by-frame analysis. Leveraging advanced machine learning models and facial recognition techniques, this detector provides an easy-to-use interface for analyzing videos and determining their authenticity.

## Features

- **Frame-by-frame detection**: Processes each video frame for accurate detection.
- **Deepfake confidence score**: Provides a confidence score indicating the likelihood of the video being deepfake.
- **Visual output**: Generates a video highlighting the detected faces and sequences.

## Dependencies

- Python 3.10
- OpenCV
- NumPy
- TensorFlow
- TensorFlow Addons
- facenet-pytorch
- PIL
- moviepy
- gradio

## Installation

1. Clone the repository:

```bash
git clone https://github.com/PhaniTejaPMSS/deepconnect-deepfake-detect.git

cd deepconnect-deepfake-detect
```

2. Download the pre-trained model zip file and place it in the appropriate directory. [ Update the paths accordingly ]

## Usage

To use the detector, simply run the Jupyter notebook and upload your video through the Gradio interface. The detector will process the video and return the result along with the confidence score and a visual representation of the detected faces.

## Interface

![DeepConnect](https://github.com/PhaniTejaPMSS/deepconnect-deepfake-detect/assets/109794469/3d0da133-2fbf-441e-87ce-3e183bb71021)

## License

This project is licensed under the MIT License.

## Contact

For any questions or inquiries, please reach out to phanitejacse2021@gmail.com.
