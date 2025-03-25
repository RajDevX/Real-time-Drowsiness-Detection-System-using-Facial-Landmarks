# Real-time Drowsiness Detection System using Facial Landmarks  

## Abstraction  
The **Real-time Drowsiness Detection System** is designed to enhance safety by detecting signs of drowsiness in individuals using a **Convolutional Neural Network (CNN)** model. This system is crucial for scenarios requiring continuous alertness, such as **driving** or **operating heavy machinery**.  

### Key Features:  
- **Real-time eye state monitoring** via a webcam.  
- **Facial image capture & eye detection** for classifying eye states as **"Open"** or **"Closed"**.  
- **CNN-based deep learning model** for accurate classification.  
- **Auditory alarms and visual alerts** to notify users when drowsiness is detected.  
- **Optimized model training** using the **Adam optimizer** and **categorical cross-entropy loss**.  

## Methodology  
1. **Facial Image Capture:** The system captures real-time facial images using a webcam.  
2. **Eye Detection:** The eyes are detected and extracted from the facial image.  
3. **Eye State Classification:**  
   - Preprocessed grayscale eye images are passed through a **CNN model**.  
   - The model classifies the eye state as **Open** or **Closed**.  
4. **Drowsiness Detection & Alert System:**  
   - If prolonged eye closure is detected, the system triggers an **auditory alarm** and **visual alert**.  

## CNN Architecture  
- **Convolutional Layers**: Extract features from input eye images.  
- **Pooling Layers**: Reduce dimensionality and enhance model efficiency.  
- **Fully Connected Layers**: Classify the eye state.  
- **Dropout Layers**: Prevent overfitting and improve generalization.  

## Dataset & Training  
- The model is trained on a dataset containing labeled **open and closed eye images**.  
- Optimized using **Adam optimizer** and **categorical cross-entropy loss function**.  
- Training ensures high accuracy in **real-time deployment scenarios**.  

## Applications  
- **Driver Monitoring Systems**: Prevent accidents caused by drowsy driving.  
- **Workplace Safety**: Ensure alertness of machine operators in industrial settings.  
- **Medical & Research Applications**: Assist in sleep studies and fatigue detection.  

## Installation & Usage  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/Real-time-Drowsiness-Detection-System-using-Facial-Landmarks.git
   cd Real-time-Drowsiness-Detection-System-using-Facial-Landmarks
