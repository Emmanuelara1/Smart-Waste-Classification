# ♻️ Smart Waste Classification System

### A Deep Learning-Based Approach for Sustainable Waste Management

This project demonstrates the use of computer vision, deep learning, and OpenCV to automate waste classification and support sustainable recycling practices. By leveraging transfer learning on pre-trained CNN models (ResNet50, VGG16, MobileNetV2, InceptionV3), the system classifies images of waste into six categories: cardboard, glass, metal, paper, plastic, and trash.

##  Key Features
- Transfer Learning Models:
  - ResNet50 (Best Accuracy: 93–95%)
  - VGG16 (80%)
  - InceptionV3 (87%)
  - MobileNetV2 (65%)

- Real-Time Classification with OpenCV:
  - Live webcam detection with bounding boxes & labels
  - Frame-by-frame predictions with high accuracy

- Web Interface:
  - Built with Flask (backend) and HTML/CSS (frontend)
  - Users can upload images to receive instant classification and confidence scores

- Robust Evaluation:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix and ROC-AUC (ResNet50 achieved near-perfect AUC scores across all classes)

##  Dataset
We consolidated multiple open-source TrashNet datasets from Hugging Face:
- kuchidareo/small_trashnet (2.5k images)
- garythung/trashnet (5k images)
- edwinpalegre/trashnet_enhanced (19.9k images)

Data preprocessing included resizing, normalization, augmentation (rotation, flips, zoom), and balanced train-validation-test splits.

##  Tech Stack
- Languages: Python
- Libraries: TensorFlow/Keras, OpenCV, Scikit-learn, NumPy, Matplotlib
- Frameworks: Flask, FastAPI (for API integration)
- Deployment: Real-time webcam integration + web interface

##  Contributors
- Paras Godhani – Backend, OpenCV integration, deployment
- Priya Patel – Data preprocessing, frontend development
- Sukhjit Kaur – API development & optimization
- Rutvi Patel – Model training, hyperparameter tuning, documentation
- Emmanuel Araoyinbo – Documentation, validation testing & OpenCV integration

##  Impact
This project highlights how AI and sustainability can work together to create smart waste management solutions for recycling plants, smart cities, and educational institutions. By automating waste classification, it reduces manual labor, improves accuracy, and promotes environmentally friendly practices.

 Future Work: Integration with IoT-enabled smart bins, larger real-world datasets, and lightweight deployment for mobile/embedded devices.

 “Turning AI into real-world impact, one sustainable solution at a time.”
