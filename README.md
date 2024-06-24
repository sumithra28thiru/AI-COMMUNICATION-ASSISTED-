# Softskill Communication Analysis

This repository presents a viable solution for soft skill communication analysis, combining both visual analysis of posture and emotional confidence with audio transcription. The system leverages various Python libraries and tools to provide insights into communication dynamics.

This is more of a general overview, detailed explanations of individual modules can be found in their respective readme files within the project repository.


## Overview

The project integrates visual analysis components for posture and emotional confidence assessment, as well as audio analysis and transcription capabilities. By analyzing video frames and audio content, the system aims to offer a holistic understanding of communication interactions.

## Features

- **Visual Analysis:** Utilizing Mediapipe joint landmarks, the system assesses posture confidence, providing insights into body language and gestures. Additionally, a custom-trained model is employed for emotion recognition, extending the analysis to emotional states.

- **Audio Transcription:** The system transcribes audio content, enabling textual analysis of communication cues. Both Hugging Face pipeline and Google Speech Recognition models are utilized for transcription, providing flexibility and accuracy options.

## Installation and Configuration

The installation process involves installing required dependencies using the provided `REQUIREMENTS.txt` file. Additionally, configuration steps include ensuring the presence of necessary model files, integrating Haarcascade for face detection, and customizing file paths for smooth execution.

## Performance Considerations

The system operates frame-by-frame for visual analysis, which may result in slightly slower performance when processing pre-recorded videos. However, the integration of audio transcription complements the analysis, providing a comprehensive understanding of communication dynamics.

## Output and Model Training

Upon completing the analysis, the system outputs variables for posture and emotional confidence levels, as well as transcribed audio content. The model training process involved utilizing the extensive Face Expression Recognition Dataset for emotion recognition.

## Testing and Reliability

While primarily serving as a prototype/poc, the system offers substantial accuracy in analysis. Further refinement and testing are totally required for specific use cases and production deployment.

