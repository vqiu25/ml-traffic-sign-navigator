# ML Traffic Sign Navigator

<p align="center">
  <img width="450" alt="dataset" src="https://github.com/user-attachments/assets/200164ac-0b76-40a0-866e-c7af4650ec0e">
</p>

## About
Project for COMPSYS 306 (Artificial Intelligence and Machine Learning). This project involves creating an ML model to help a NVIDIA JetBot traverse a track with various traffic signs. The ML model chosen was Support Vector Machine (SVM), and is able to generalise to any track with the following signs.

There were 5 possible "signs", these being:
* **Speed Sign**: When encountered, the JetBot should speed up
* **Stop Sign**: When encountered, the JetBot should pause, and reset it's speed
* **Green Light**: When encountered, the JetBot should travel forwards
* **Red Light**: When encountered, the JetBot should stop
* **Sheep**: When encountered, the JetBot should stop

With the line/road also being included as a class:
* **Line**: When encountered, the JetBot should travel forwards

## Dataset
The dataset collected is around 8000 images, and can largely be represented by the following images:
<p align="center">
  <img width="450" alt="dataset" src="https://github.com/user-attachments/assets/9185e397-8b66-4cda-8bbb-6727eb6ef9a1">
</p>

## Preprocessing Steps for Dataset
1. Crop the images to contain only the middle 60%
2. Resize images to 32x32
3. Flatten the images to an 1D array

## Video

https://github.com/user-attachments/assets/0f413103-26b0-40d2-bb06-32ad281c02ed

## Team Members
* Victor Qiu
* Jenny Wang
* Peter Yin
* Teresa Zhang
