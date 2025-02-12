
# DeepFake Detection System
#TruthLens

## 📌 Overview
In an era where AI-generated deepfakes blur the line between reality and deception, detecting manipulated media is more crucial than ever. This project leverages advanced **Deep Learning** techniques, specifically **Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs)**, to analyze videos and images, detecting deepfake manipulations with high accuracy.

## 🔍 Problem Statement
- **Deepfakes are hard to detect**: Their high realism makes them indistinguishable from genuine media.
- **Deepfakes can cause harm**: They can be used for misinformation, identity fraud, and defamation.
- **Existing solutions have limitations**: Many detection methods struggle with complex manipulations or are computationally expensive.
- **Need for a robust detection system**: A reliable AI-based approach is essential to mitigate these threats.

## 🚀 Key Features
✅ **CNN-based Feature Extraction** – Identifies facial inconsistencies and artifacts at the pixel level.  
✅ **RNN-based Temporal Analysis** – Detects unnatural motion patterns in video sequences.  
✅ **Hybrid Model Fusion** – Combines spatial and temporal features for robust detection.  
✅ **User-Friendly Web Interface** – Upload videos/images for real-time deepfake detection.  
✅ **Backend with Flask API** – Ensures seamless integration of AI models and frontend.  
✅ **Scalable & Optimized** – Designed for efficient deployment on cloud platforms.  

## 🏗️ System Architecture
1️⃣ **Preprocessing**: Frames are extracted from videos and normalized.  
2️⃣ **Feature Extraction (CNN)**: Captures spatial inconsistencies in images.  
3️⃣ **Temporal Analysis (RNN - LSTM/GRU)**: Tracks motion inconsistencies across frames.  
4️⃣ **Classification**: Deepfake vs. Real prediction using a fully connected neural network.  
5️⃣ **Output Generation**: Provides a confidence score and visualization of manipulated regions.  

## 🛠️ Technologies Used
- **Frontend**: React.js
- **Backend**: Flask
- **Machine Learning Frameworks**: TensorFlow, Keras, OpenCV
- **Database**: PostgreSQL (for storing metadata and results)
- **Cloud Deployment**: AWS/GCP (optional)

## 🏁 Installation & Setup
### Prerequisites
- Python 3.8+
- Node.js & npm
- Virtual environment (recommended)

### Step 1: Clone the Repository
```sh
$ git clone https://github.com/your-repo/deepfake-detection.git
$ cd deepfake-detection
```

### Step 2: Setup Backend (Flask)
```sh
$ python -m venv venv
$ source venv/bin/activate  # On Windows: venv\Scripts\activate
$ pip install -r requirements.txt
$ python app.py
```

### Step 3: Setup Frontend (React.js)
```sh
$ cd frontend
$ npm install
$ npm start
```

### Step 4: Run the Application
Access the web interface at **http://localhost:3000/**

## 📊 Model Training & Evaluation
To train the model, use:
```sh
$ python train.py --dataset /path/to/deepfake-dataset --epochs 50
```
After training, evaluate the model:
```sh
$ python evaluate.py --model model.pth --testset /path/to/test-data
```

## 📌 Future Enhancements
- 🎭 **GAN-based Deepfake Generation**: Creating adversarial examples for robust training.
- 📹 **Real-time Detection**: Optimizing for live video stream analysis.
- 🔬 **Explainable AI (XAI)**: Visualizing decision-making for trustworthiness.
- 🌎 **Multilingual Support**: Expanding the detection model for different languages and face types.

## 🤝 Contributors
- **Livya Falodia**   
- **Annu Mishra**

## 📜 License
This project is licensed under the **MIT License**.

## ⭐ Acknowledgments
- Inspired by **DeepFake Detection Challenge** datasets.
- Special thanks to researchers in AI Ethics & Digital Security.

---
📌 **If you like this project, give it a star ⭐ on GitHub!**

