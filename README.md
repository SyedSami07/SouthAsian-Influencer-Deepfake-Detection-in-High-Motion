# SouthAsian-Influencer-Deepfake-Detection 🇮🇳 🇧🇩 🇵🇰

## Project Overview
With the surge of short-form video content (Reels, TikToks), deepfake technology is being used to create misleading content of South Asian influencers. This project focuses on detecting deepfakes in viral South Asian reels, which often contain complex dance moves, cultural attire, and varying lighting conditions.

## Research Focus
* **Domain:** South Asian Social Media (Viral Reels & Influencer Content).
* **Challenges:** Diverse skin tones, traditional clothing textures, and high-velocity dance movements.
* **Model Performance:** Evaluating ResNet50, Xception, and MobileNetV2 for real-world authentication.

## Dataset specification
- **Total Samples:** x no of videos.
- **Classes:** - **AI-Generated:** x no of videos of South Asian influencers created via deepfake tools.
  - **Real:** x no of authentic viral reels.
- **Source:** Social media platforms (Instagram, YouTube, TikTok).

## Key Results (ResNet50)
- **Validation Accuracy:** 77.65%
- **F1-Score (AI):** 0.63
- **Training Strategy:** Implemented Transfer Learning with heavy Dropout (0.7) and Class Balancing to handle the unique artifacts of South Asian digital content.
![Model Performance Comparison](https://github.com/SyedSami07/SouthAsian-Influencer-Deepfake-Detection-in-High-Motion/blob/main/performance.png)

## Tech Stack
- Python, TensorFlow/Keras, OpenCV, Scikit-learn.
