# currency-detection-text-recognition
Currency detection and text recognition mobile app using YOLOv8 and OCR
# Currency Detection & Text Recognition Mobile App

This project is a mobile application designed to assist visually impaired users by detecting Ethiopian currency denominations and reading printed text aloud.

## Features
- Real-time detection of Ethiopian currency (5, 10, 50, 100, 200 Birr)
- Optical Character Recognition (OCR) for printed text
- Audio feedback for accessibility
- Mobile-friendly and lightweight design

## Tech Stack
- Python
- YOLOv8 (Object Detection)
- PyTorch
- Google ML Kit (Text Recognition)
- Flutter

## Model Overview
- Trained a YOLOv8 model on labeled Ethiopian currency images
- Applied data augmentation to improve robustness
- Evaluated using precision, recall, and mAP metrics

## Use Case
This application improves accessibility by enabling visually impaired users to identify currency and read text independently.

## Future Improvements
- Add more currency denominations
- Improve detection accuracy in low-light conditions
- Support multiple languages for text-to-speech

