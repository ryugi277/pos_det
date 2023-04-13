# Posture Detector using YOLOv5

![Product Name Screen Shot][product-screenshot]  
This GitHub repository contains a posture detection program that utilizes YOLOv5, an advanced object detection algorithm, to detect and predict sitting postures. The program is designed to analyze the user's sitting posture in real-time and provide feedback on whether the posture is good or bad based on predefined criteria. The goal of this project is to promote healthy sitting habits and prevent potential health issues associated with poor posture.

Key Features:

* YOLOv5: The program leverages the power of YOLOv5, which is a state-of-the-art object detection algorithm, to
  accurately detect the user's sitting posture from a webcam.
* Real-time Posture Detection: The program provides real-time feedback on the user's sitting posture, making it suitable
  for use in applications such as office ergonomics, fitness, and health monitoring.
* Good vs. Bad Posture Classification: The program uses a pre-trained model to classify the detected posture as good or
  bad, enabling users to improve their posture and prevent potential health issues associated with poor sitting habits.
* Open-source: The program is released under an open-source license, allowing users to access the source code, modify
  it, and contribute to the project.

### Built With

![Python]

# Getting Started

### Prerequisites

* Python 3.9.x

### Installation

#### Windows

1. `git clone https://github.com/itakurah/SittingPostureDetection.git`
2. `python -m venv venv`
3. `.\venv\scripts\activate.bat`
4. `pip install -r ./requirements_windows.txt`

#### Linux

1. `git clone https://github.com/itakurah/SittingPostureDetection.git`
2. `python3 -m venv venv`
3. `source venv/bin/activate`
4. `pip3 install -r requirements_linux.txt`

### How to run the program

`python application.py`

# About

This project was developed by Niklas Hoefflin, Tim Spulak,
Pascal Gerber & Jan Bösch and supervised by André Jeworutzki
and Jan Schwarzer as part of the "Train Like A Machine" module.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

<!-- MARKDOWN LINKS & IMAGES -->  

[product-screenshot]: images/screenshot.png

[Python]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
