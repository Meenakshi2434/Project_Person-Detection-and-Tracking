# Project_Person-Detection-and-Tracking
This project aims to build a real-time person detector and tracking system to identify and track children and adults in videos.

---

# Person Detection and Tracking for Autism Spectrum Disorder Therapy

## Overview

This project aims to build a real-time person detector and tracking system to identify and track children and adults in videos. The primary goal is to assign unique IDs to individuals, track their movements, and reassign correct IDs post-occlusion or upon re-entry into the frame. The system is designed to monitor children with Autism Spectrum Disorder (ASD) and therapists to understand behavior patterns, emotions, and engagement levels, contributing to the development of personalized treatment plans to enhance skills and learning outcomes.

## Features

- **Person Detection**: Detects children and adults in the video using state-of-the-art deep learning models.
- **Unique ID Assignment**: Assigns a unique ID to each individual entering the video frame for the first time.
- **Re-entry Tracking**: Tracks individuals who exit and re-enter the frame, ensuring their original ID is reassigned.
- **Post-Occlusion Tracking**: Re-identifies individuals after occlusion or partial visibility loss, ensuring continuity in tracking.
- **Multiple Person Tracking**: Simultaneously tracks multiple individuals to monitor behavior in a group setting.

## Application

This project is specifically tailored for therapy sessions with children with ASD, where tracking individual engagement, behavior, and interaction with therapists can provide insights to optimize therapy approaches and outcomes.

## Technologies

- Python
- OpenCV
- YOLOv5 (or similar detection models)
- DeepSORT (for object tracking)
- NumPy
- Pandas

## Future Enhancements

- Emotion and behavior recognition
- Integration with therapy analytics tools
- Automated reporting and treatment suggestions

---
