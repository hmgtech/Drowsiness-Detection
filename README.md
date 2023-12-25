[![language](https://img.shields.io/badge/language-python3.8-blue
)](https://img.shields.io/badge/language-python3.8-blue
) 
[![license](https://img.shields.io/badge/license-MIT-orange
)](https://img.shields.io/badge/coverage-86%25-orange
)
# Drowsiness-Detection

This project focuses on creating a tool for detecting drowsiness in individuals, especially applicable in scenarios like driving where alertness is crucial.

## Demo
![Demo](./drowsiness.gif)

## Overview
Drowsiness Detection uses computer vision techniques to analyze facial features and identify signs of drowsiness in real-time. By monitoring key facial expressions and eye movements, the system can alert individuals when they show signs of drowsiness, potentially preventing accidents caused by fatigue.

## How it Works
The detection process involves:

- Facial Landmark Detection: The system identifies facial landmarks, including eyes and mouth, using computer vision algorithms.

- Eye Aspect Ratio (EAR): The EAR is calculated based on the ratio of distances between different facial landmarks. It provides insights into the openness of the eyes.

- Drowsiness Threshold: A predefined threshold is set to determine when an individual is becoming drowsy based on the calculated EAR.

- Alert System: When drowsiness is detected, an alert is triggered, such as a sound alert or a visual notification, to notify the individual to stay alert.

## Installation
### 1. Clone the repository:

```bash 
git clone https://github.com/hmgtech/Drowsiness-Detection.git
cd Drowsiness-Detection 
```

### 2. Install the required dependencies:

```bash
pip install -r requirements.txt
```
### 3. Run the Drowsiness Detection tool:

```bash
python drowsiness_detection.py
```

## Usage
1. Ensure your webcam is connected and properly configured.
2. Run the Drowsiness Detection tool.
3. Monitor the real-time output for alerts and notifications when drowsiness is detected.


## License
This project is licensed under the terms of the MIT license.