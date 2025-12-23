# Devanagari-Sign-Language-Recognition-and-Translation
This is a high-impact project, especially considering its real-world implementation at Adhaar Mook Badhir Vidyalaya. To make your GitHub repository stand out to recruiters and the open-source community, you need a balance of technical depth and social impact


## 🏫 Real-World Implementation
The models developed in this repository were implemented at **Adhaar Mook Badhir Vidyalaya** to assist students and teachers. Due to licensing and school-specific data privacy, this repository serves as a documented version of the logic, model architectures, and translation algorithms rather than the final commercial-ready application bundle.

## 🚀 Key Features
- **Engineered Accuracy:** Achieved a peak accuracy of **96%** for gesture recognition.
- **40+ Signs:** Supports a wide vocabulary of Devanagari characters and common phrases.
- **Optimized Pipeline:** Uses **MediaPipe** for real-time hand landmark tracking, ensuring the model remains lightweight enough for edge device deployment.
- **Multi-Algorithm Approach:** Comparative implementation using **CNN, SVM, and Random Forest** to find the optimal balance between speed and precision.

---

## 🛠️ Technical Stack
* **Computer Vision:** OpenCV, MediaPipe (Hand Tracking)
* **Deep Learning:** TensorFlow, Keras (CNN Architecture)
* **Machine Learning:** Scikit-learn (SVM & Random Forest)
* **Language:** Python 3.x

---

## 📈 Performance Benchmark
During the development phase, we benchmarked three distinct architectures to ensure the best performance for the school's specific environment:

| Model | Accuracy | Suitability |
| :--- | :--- | :--- |
| **CNN (Deep Learning)** | **96.4%** | Best for high-resource environments |
| **SVM** | **91.2%** | Balanced performance |
| **Random Forest** | **89.5%** | Highly efficient for mobile CPUs |
