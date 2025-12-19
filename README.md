# Fluttter-Projects

# 🏄 Outdoor Board Sports

**Outdoor Board Sports** is an intelligent mobile application designed to detect and identify outdoor board sports equipment in real time using machine learning. Built with **Flutter** and an on-device **machine learning model**, the application provides accurate detection, detailed history tracking, and performance analytics while processing data locally.

---

## ✨ Key Features

- **Board Sport Identification**  
  Detects and identifies different outdoor board sports equipment using the device camera.

- **Multiple Board Sport Classes**  
  Supports 10 board sport types:
  - Skateboard  
  - Longboard  
  - Surfboard  
  - Snowboard  
  - Wakeboard  
  - Paddleboard  
  - Bodyboard  
  - Skimboard  
  - Sandboard  
  - Mountain board  

- **Guided Detection Process**  
  Users select a specific board sport type before detection to improve accuracy.

- **Detection Confirmation**  
  Allows users to confirm results or retake images when confidence is low.

- **Detection History Tracking**  
  Automatically records all detections, including correct and incorrect results.

- **Advanced History Filtering**  
  Filter detection history by:
  - Verification status (Verified / Not Verified)  
  - Result (Correct / Incorrect)  
  - Board sport type  

- **Analytics Dashboard**  
  Displays total scans, verified detections, error rate, and per-class performance metrics.

---

## 🔄 How It Works

### 1. Select Board Sport
When the application opens, users are presented with the 10 available board sport classes. The user selects the board sport they want to detect.

### 2. Capture
After selecting a board type, the application automatically opens the camera. The user points the camera at the board equipment.

### 3. Analyze
The captured image is processed locally using a machine learning model. The system checks if the detected board matches the selected board sport class.

### 4. Detect & Validate
- If the detected board does not match the selected class, an error message is displayed.  
- If the detected board matches, the system proceeds to the Detection Result module.

### 5. Confirm & Save
The user can confirm the detection or retake the image. Once confirmed, the result is marked as verified and saved to the system.

---

## 📊 Modules Overview

### Detection Result Module
- Displays the detected board sport and confidence result  
- Allows confirmation or image retake  
- Saves verified detections automatically  

### History Module
- Shows all detection records, including errors  
- Stores both correct
