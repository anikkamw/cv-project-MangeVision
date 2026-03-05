# cv-project-MangeVision
MangeVision
Team Members (if applicable)
Anikka Williams - W200792488@student.hccs.edu
Project Tier
Tier 1: This project is a simple classification task model that will use pre-trained models. 
Problem Statement
Veterinary clinics have a struggle with time and patient comfort when diagnosing Sarcoptic and Demodectic mange, as skin scraping can take multiple samples. Sarcoptic mange is highly contagious to other animals and humans, making diagnosis very critical.
Solution Overview
My model will be a diagnostic tool that classifies types of mange from digital images of canine skin lesions. It will provide an instant classification, aiding in handling highly contagious cases. 
Technical Approach
CV Technique: Object Detection and Classification
Model: YOLOv8
Framework: PyTorch
Why this approach: I chose YOLOv8 because it is famous for being 'real-time,' meaning it can identify skin issues almost instantly, and I selected PyTorch because it is a beginner-friendly framework that makes it easy to experiment with different neural network settings
Dataset: 
Source: Kaggle
Size: approximately 2000 images
Labels: Sarcoptic Mange, Demodectic Mange, Healthy Skin
Link: https://www.kaggle.com/datasets/youssefmohmmed/dogs-skin-diseases-image-dataset, https://www.kaggle.com/datasets/devdope/skin-disease-raw-dataset
Success Metrics
Primary Metric: Accuracy
Target:85% accuracy
Secondary Metrics: Speed: <2 seconds per image
Week-by-Week Plan
Week 10: Finalize dataset from Kaggle, begin image labeling in Roboflow
Week 11:Set up YOLOv8, run initial model training
Week 12: Evaluate model performance
Week 13: Develop a simple demo showing the AI in action
Week 14: Conduct final testing, bug fixes, and complete GitHub documentation.
Week 15: Presentation
Resources Needed
Compute: Colab, Kaggle
Cost: 0
APIs: 
Risks & Mitigation
Risk Probability Mitigation
Limited high-quality manage images, Medium, Enhance the images by adjusting brightness, rotating etc. to increase my dataset
Model getting confused by the different-colored dog fur. Low : Process images to crop specifically on the skin lesion, to remove the distraction on the fur color.
