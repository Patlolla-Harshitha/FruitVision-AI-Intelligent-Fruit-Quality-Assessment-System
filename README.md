 FruitVision AI – Intelligent Fruit Quality Assessment System
Overview

FruitVision AI is an advanced computer vision application that automatically detects fruits in an image and evaluates their quality using deep learning. The system combines object detection and Vision Transformer (ViT) models to classify fruits based on freshness, ripeness, and edibility.

The project is designed to assist in food quality inspection, smart agriculture, supply chain monitoring, and reducing food waste through AI-powered analysis.

Features
 Automatic fruit detection from images
 Freshness classification (Fresh / Rotten)
 Ripeness prediction (Unripe / Ripe / Overripe)
 Edibility assessment (Eatable / Not Eatable)
 Multi-fruit detection in a single image
 Transformer-based deep learning architecture
 Confidence score for each prediction
 End-to-end automated fruit quality analysis
Technologies Used
Artificial Intelligence & Deep Learning
PyTorch
Vision Transformer (ViT)
DETR (DEtection TRansformer)
Hugging Face Transformers
Computer Vision
Pillow (PIL)
Image Processing
Object Detection
Programming Language
Python
Model Architecture
Fruit Detection
DETR (facebook/detr-resnet-50)
Identifies fruits and extracts bounding boxes from images.
Fruit Quality Analysis
Vision Transformer (google/vit-base-patch16-224)
Multi-task learning approach with three prediction heads:
Freshness Classification
Ripeness Classification
Edibility Classification
Classification Categories
Freshness
Fresh
Rotten
Ripeness
Unripe
Ripe
Overripe
Edibility
Eatable
Not Eatable
Workflow
Upload a fruit image.
Detect all fruits using DETR.
Crop each detected fruit.
Process crops through Vision Transformer.
Predict:
Freshness
Ripeness
Edibility
Display predictions with confidence scores.
