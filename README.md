A Machine Learning & Computer Vision system to:
 Predict Quality of Sleep using health & lifestyle data
 Monitor sleep posture and restlessness via camera in real-time
 Provide personalized suggestions to improve sleep quality

 Features
 Sleep Quality Prediction

Predicts sleep quality (1–10) based on metrics like stress, physical activity, heart rate, etc.

Trained Neural Network saved as .h5

 Camera-Based Sleep Monitor

Uses webcam to detect body movements and posture while sleeping

Alerts if restless or abnormal sleep behavior is detected

Summarizes sleep analysis at the end

 Personalized Suggestions

Suggests actionable tips to improve sleep hygiene and patterns

 Project Structure
bash
Copy
Edit
Sleep-Pattern-Detection/
│
├── sleep_quality_model.py         # Trains ML model for sleep quality prediction
├── sleep_advisor.py               # Predicts sleep quality from user inputs
├── sleep_camera_monitor.py        # Camera-based real-time sleep monitoring
├── Sleep_health_and_lifestyle_dataset.csv  # Dataset
├── sleep_quality_model.h5         # Saved ML model
├── sleep_disorder_model.h5        # Saved disorder classification model
├── README.md                      # This file
 Dataset
Sleep Health and Lifestyle Dataset

Source: Kaggle

Contains 400+ records with:

Age, Gender

Sleep Duration, Quality

Stress Level, Physical Activity

BMI, Heart Rate, Blood Pressure

Sleep Disorders (Insomnia, Apnea)
