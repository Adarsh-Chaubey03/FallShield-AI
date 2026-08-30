# FallShield-AI

**FallShield-AI is a privacy-first, smartphone-based fall detection and emergency response system that uses built-in motion sensors to detect potential falls, verify incidents, and alert emergency contacts when assistance is needed.**

## Problem Statement


Falls are a major public-health concern, particularly among older adults. According to the **WHO, an estimated 684,000 people die from falls globally each year**, with adults over 60 experiencing the highest number of fatal falls. Additionally, around **37.3 million falls annually are severe enough to require medical attention**.

When a person falls while alone, delayed assistance can increase the risk of serious complications. This is especially concerning for **senior citizens and visually impaired users**, who may have limited mobility or environmental awareness and may struggle to seek help after a fall.

Existing fall-detection systems often rely on **wearable devices, cameras, or cloud-based processing**, which can increase cost, inconvenience, accessibility challenges, and privacy concerns.

## Solution Overview


FallShield-AI turns a smartphone into a **fall-detection and emergency response assistant** using its built-in accelerometer and gyroscope. The system analyzes motion patterns, validates potential falls, confirms incidents with the user, and initiates an emergency response when required.

The system focuses on providing **accessible, privacy-preserving, and responsive fall detection** without requiring dedicated wearable hardware or continuous camera monitoring.

## Key Features



* Real-time accelerometer and gyroscope monitoring
* AI-based fall detection using smartphone IMU data
* Confidence-based validation to reduce false alarms
* Voice-assisted user confirmation after suspected falls
* Automatic SOS escalation for help requests or no response
* Emergency contact notification with location sharing
* Priority-based emergency response
* Privacy-first sensing without camera monitoring
* Local and offline-friendly processing

## System Workflow



```text
Accelerometer + Gyroscope
            ↓
     Sensor Processing
            ↓
     Fall Detection Model
            ↓
    Confidence Validation
            ↓
     User Confirmation
            ↓
 ┌──────────┴──────────┐
 │                     │
Safe              Help / No Response
 │                     │
Cancel Alert           ↓
                Emergency Escalation
                       ↓
              Contact Notification
```

## Technology Stack


* **Mobile:** React Native, Expo, Expo Router, Expo Sensors, Expo Speech
* **Backend:** Node.js, Express.js
* **Machine Learning:** Python, PyTorch, NumPy, SciPy, Scikit-learn, ONNX Runtime
* **Database / Storage:** MongoDB, Local Storage
* **Notifications:** SMS / Push Notifications
* **Sensors:** Smartphone Accelerometer and Gyroscope



## Team



| Member               | Enrollment No. |
| -------------------- | -------------: |
| Adarsh Chaubey       |       23103066 |
| Aditya Laxkar        |       23103071 |
| Divyam Kumar Choubey |       23103070 | 
| Sakshi Gupta         |       23103067 |

