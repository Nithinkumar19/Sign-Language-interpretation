# GestureDecode
## Project Title : Sign Language Interpretation

The Sign Language Interpretation project focuses on recognizing and interpreting hand gestures to facilitate communication for individuals who use sign language. This project leverages computer vision and machine learning techniques to accurately identify and translate hand signs into text.

### Features:

- **Gesture Recognition** : Utilizes MediaPipe's hand tracking capabilities to accurately detect and interpret hand gestures in real-time, providing a robust framework for recognizing various sign language gestures.

- **Gesture Classification** : Employs the KeyPointClassifier model to classify detected hand gestures into predefined sign language symbols, enabling precise translation of gestures into meaningful commands or text.
  
- **Historical Gesture Analysis** : Implements PointHistoryClassifier to analyze and understand gesture sequences over time, enhancing the system's ability to interpret complex signs and contextual meanings.

- **Real-time Performance Metrics** : Uses CvFpsCalc from the utils module to monitor and optimize the frame rate of video processing, ensuring smooth and responsive performance during gesture recognition.

- **Customizable Input Handling** : Provides flexible input options via argparse for configuring video sources and model parameters, allowing users to adapt the system to different environments and use cases.

### Key Modules Used:

- csv
- copy
- tensorflow
- argparse
- itertools
- collections
- cv2
- numpy
- mediapipe
