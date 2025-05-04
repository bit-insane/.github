# Harvest Sense

## Project Overview

**Harvest Sense** is a smart system built to help farmers determine the best time to harvest their crops. Traditionally, many farmers rely on guesswork when deciding harvest time, leading to crop loss or missed opportunities. Harvest Sense eliminates the guesswork by using AI-driven image analysis and real-time robotic feedback.

## How It Works

- **Capture Crop Images:**  
  Farmers can use a mobile phone, webcam, or Raspberry Pi camera to capture images of their crops.

- **AI-Powered Image Analysis:**  
  We use a YOLO (You Only Look Once) model trained to recognize different ripeness stages. For demonstration, we trained the model on Roboflow’s **Banana Ripeness dataset**. Though bananas were used for the example, the model can be adapted to any crop with the right dataset.

- **Real-Time Prediction:**  
  After capturing the image, the AI analyzes it instantly and classifies the crop as ripe, overripe, or not ripe, giving farmers immediate, actionable insights.

- **Weather Data Integration (Future Scope):**  
  We plan to enhance the system by integrating weather data (like temperature and humidity) for even more accurate harvest predictions.

- **Real-Time Robotic Assistance:**  
  We built and integrated a real-time bot using **LEGO modules and BrickPi**. This bot can assist in tasks like monitoring crops, guiding harvesting processes, or even automating small physical tasks related to crop checking.

## Why Harvest Sense?

- Reduces crop loss by removing guesswork.
- Provides instant feedback using AI.
- Future-ready with plans for weather data integration.
- Includes a robotic system for real-time assistance.
- Simple to set up with affordable hardware like Raspberry Pi and LEGO modules.

## Technologies Used

- YOLO Object Detection Model
- Roboflow for dataset management and training
- Raspberry Pi for running live camera feeds
- LEGO Mindstorms modules and BrickPi for real-time robotic operation
- Python for backend development and camera interfacing
- Inference API for live model prediction

## Demo Dataset

- We used the **Banana Ripeness dataset** from Roboflow for this concept.
- With proper datasets, the system can be extended to any crop type.

## Documentation 
[REVOLUTIONIZING FIELDS, ONE BIT AT A TIME](https://drive.google.com/file/d/1UpJ6_4OXPiAYcJ_YhW5LAUJ6GtCWn4Bw/view?usp=drivesdk)
