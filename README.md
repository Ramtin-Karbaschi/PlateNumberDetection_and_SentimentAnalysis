# License Plate Detection and Sentiment Analysis Project

## Overview
This repository contains two main components: an Automatic Number Plate Recognition (ANPR) system and a Sentiment Analysis implementation. The project demonstrates the application of computer vision and natural language processing techniques in real-world scenarios.

## Project Structure
```
.
├── Plate Number Detection/
│   └── Final-model-ANPR/
│       ├── Character_Detector.ipynb
│       ├── LicensePlate_Detector.ipynb
│       ├── LicensePlate_Detector_YOLO12n.ipynb
│       ├── OCR.ipynb
│       └── final_test_result/
└── Sentiment Analysis/
    ├── P1 & P2/
    └── P3/
```

## 1. License Plate Detection (ANPR)

### Description
The ANPR system is designed to automatically detect and recognize vehicle license plates from images or video streams. The system employs a multi-stage approach:

1. **License Plate Detection**: Utilizes YOLO-based models for accurate plate localization
2. **Character Detection**: Implements character segmentation within detected plates
3. **Optical Character Recognition (OCR)**: Converts detected characters into machine-readable text

### Components
- `Character_Detector.ipynb`: Implementation of character segmentation and detection
- `LicensePlate_Detector.ipynb`: Main license plate detection module using YOLOv11n architecture
- `LicensePlate_Detector_YOLO12n.ipynb`: Enhanced detection using YOLOv12n architecture
- `OCR.ipynb`: Optical Character Recognition implementation

## 2. Sentiment Analysis

### Description
The sentiment analysis component focuses on natural language processing to determine sentiment polarity in text data. The implementation is divided into multiple phases:

- **Phase 1 & 2**: Initial implementation and baseline models
- **Phase 3**: Advanced sentiment analysis techniques and improvements

### Features
- Text preprocessing and cleaning
- Sentiment classification
- Performance evaluation metrics
- Model optimization


## Contributing
Contributions are welcome!

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- YOLOv12 and YOLO11 implementation contributors
- OpenCV community
- NLTK developers
