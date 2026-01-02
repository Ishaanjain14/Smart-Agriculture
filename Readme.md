🌱 Crop Disease Detection using Lightweight Deep Learning Models

📌 Overview

Crop diseases significantly impact agricultural productivity and food security. This project presents a lightweight, uncertainty-aware deep learning system to automatically detect crop diseases from leaf images. The system is optimized for real-time inference and low-resource environments, making it suitable for deployment on mobile and edge devices.

The project compares multiple lightweight CNN architectures and integrates Bayesian MC-Dropout to improve robustness, reduce overfitting, and estimate prediction uncertainty.

⸻

🚀 Key Features
	•	Automated crop disease detection from leaf images
	•	Lightweight CNN models optimized for low computational cost
	•	Bayesian uncertainty estimation for reliable predictions
	•	Designed for real-time, mobile, and edge deployment
	•	Comprehensive evaluation using standard ML metrics

⸻

🧠 Models Implemented

The following pretrained models were fine-tuned and compared:
	•	SqueezeNet – ultra-lightweight architecture with minimal parameters
	•	MobileNetV2 – efficient depthwise separable convolutions for mobile devices
	•	EfficientNet-B0 – balanced accuracy and efficiency using compound scaling

Bayesian MC-Dropout was optimally integrated before the final classifier to achieve the best performance gains.

⸻

📊 Results
	•	Achieved up to 97% classification accuracy
	•	10–13% accuracy improvement after Bayesian MC-Dropout integration
	•	Reduced overfitting and improved model robustness
	•	Reliable performance across multiple crop disease classes

⸻

🛠 Tech Stack
	•	Programming Language: Python
	•	Deep Learning Framework: PyTorch, Torchvision
	•	Models: SqueezeNet, MobileNetV2, EfficientNet-B0
	•	Techniques: Transfer Learning, Bayesian MC-Dropout
	•	Libraries: NumPy, scikit-learn, Matplotlib
	•	Evaluation Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

⸻

📁 Dataset
	•	New Plant Diseases Dataset (Augmented)
	•	PlantVillage Dataset
Includes multiple crop diseases with augmented variations for better generalization.

⸻

📈 Evaluation Metrics

Models were evaluated using:
	•	Accuracy
	•	Precision
	•	Recall
	•	F1-score
	•	Confusion Matrices

These metrics help analyze both overall and class-wise performance.

⸻

🔮 Future Scope
	•	Deploy models on mobile and edge devices
	•	Integrate Agentic AI for adaptive and intelligent decision-making
	•	Extend to disease severity estimation and treatment recommendations
	•	Integrate with IoT sensors and drones for large-scale farm monitoring
