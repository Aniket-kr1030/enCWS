# Suspicious Activity Classification - Fast R-CNN

This project aims to detect and classify suspicious activities in real-time using video footage obtained from CCTV cameras. The model is built on the Fast R-CNN framework, a deep learning-based object detection system that is capable of processing thousands of object proposals in parallel. By detecting and classifying potential criminal activities, this system can help law enforcement and security personnel take appropriate action and prevent potential incidents.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Usage](#usage)
- [License](#license)

## Overview

This project is based on the Fast R-CNN architecture, a popular choice for object detection tasks. Fast R-CNN is an improvement over R-CNN and SPP-net, offering a much faster training and detection time. In addition to object detection, our model also performs activity classification, focusing on the identification of suspicious activities.

Some examples of suspicious activities include:

- Assault
- Burglary
- Break-in
- Trespassing
- Vehicle break-ins

## Installation

To set up the environment and install the required dependencies, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/username/enCWS.git
   ```

2. Change the directory:

   ```
   cd enCWS
   ```

3. Create a virtual environment and activate it:

   ```
   python3 -m venv venv
   source venv/bin/activate
   ```

4. Install the dependencies:

   ```
   pip install -r requirements.txt
   ```

## Dataset

The dataset used for training and evaluation consists of annotated video clips from various public CCTV cameras. Annotations include bounding boxes for objects of interest and labels describing the suspicious activities taking place.

## Usage

To train the model, execute the following file:

```
model_enCWS.ipynb
```

For real-time detection and classification using your webcam, run:

## Evaluation

Model performance is evaluated using the mean Average Precision (mAP) metric, which measures the quality of the object detection and classification. To evaluate the trained model on the test dataset, run:


## Contributing

We welcome contributions to improve the project. To contribute, please fork the repository, make your changes, and create a pull request.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.
