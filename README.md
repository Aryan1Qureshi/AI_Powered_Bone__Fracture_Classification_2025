# 🦴 AI-Powered Bone Fracture Classification System

This repository hosts an **AI-powered medical image classification system** that detects and classifies **bone fractures** in X-ray images. It combines advanced **machine learning**, **explainable AI (XAI)**, and a **Streamlit-based interactive interface** to assist healthcare professionals with quick, interpretable, and reliable diagnoses.

> 🚀 **Note:** This project will be made **publicly accessible in December 2025**.  
> 📩 Until then, if you wish to **preview or access the project**, please [request access](mailto:aryannqureshi1@gmail.com).



## 🧠 Project Overview

This project presents an **AI-powered Bone Fracture Classification System** designed to assist medical professionals in the rapid and accurate diagnosis of bone fractures from medical images (e.g., X-rays). By leveraging advanced machine learning techniques, our system aims to enhance diagnostic efficiency, reduce potential human error, and ultimately improve patient outcomes.

A critical feature of this system is the integration of **LIME (Local Interpretable Model-agnostic Explanations)**. This explainability component provides crucial insights into the AI model's decision-making process, making its predictions more transparent and trustworthy for healthcare practitioners.


## 🎯 Sustainable Development Goals (SDGs) Addressed

Our AI-powered bone fracture classification system directly contributes to the United Nations' Sustainable Development Goals (SDGs), primarily focusing on **SDG 3: Good Health and Well-being**, with potential positive impacts on other related goals.

### ✅ SDG 3: Good Health and Well-being

This project significantly advances SDG 3 by:

**1. Enhancing Diagnostic Accuracy and Speed**  
_(Target 3.8: Achieve universal health coverage, including access to quality essential healthcare services)_  
The system improves the accuracy and speed of bone fracture diagnosis. This means patients can receive faster and more precise treatment plans, leading to reduced pain, fewer complications, and overall better outcomes.

**2. Improving Healthcare Efficiency and Accessibility**  
_(Target 3.8 & Target 3.c: Increase health financing and health workforce)_  
By automating a portion of the diagnostic process, the system reduces the workload on radiologists, allowing them to serve more patients. In areas lacking specialists, this AI acts as a force multiplier.

**3. Building Trust and Adoption of AI in Healthcare through Explainability (LIME)**  
_(Supports Target 3.8 and health system strengthening)_  
LIME explanations help medical professionals understand why a prediction was made, building trust in AI and enabling safe adoption. It also supports education and transparency.

**4. Reducing Morbidity from Injuries**  
_(Aligns with Target 3.4: Reduce premature mortality from non-communicable diseases)_  
Timely and accurate fracture detection helps prevent complications and long-term disability, improving patient quality of life.

### 🌍 Potential Contributions to Other SDGs

**SDG 9: Industry, Innovation, and Infrastructure**  
By bringing AI innovation into medical diagnostics, this project strengthens healthcare infrastructure and modernizes clinical workflows.

**SDG 10: Reduced Inequalities**  
Deployment in underserved areas helps bridge the healthcare gap by providing diagnostic support where specialists are scarce.


## ✅ Key Features

- 🖼️ **X-ray Classification** – Instantly detect if a bone is fractured or not.
- ⚙️ **Optimized ML Pipeline** – Uses PCA + SVM with best parameters found using OPTUNA.
- 📊 **Explainable AI (XAI)** – LIME integration for interpretable decision-making.
- 🧪 **Interactive Interface** – Upload X-rays and get visual + diagnostic results using Streamlit.
- 🛠️ **Lightweight & Efficient** – Suitable for local and remote deployment.


## 🛠️ Tools & Technologies Used

| Area | Tools & Libraries |
|------|-------------------|
| **Programming Language** | Python |
| **Machine Learning** | scikit-learn, OPTUNA, joblib |
| **Dimensionality Reduction** | PCA |
| **Explainability (XAI)** | LIME |
| **Image Processing** | OpenCV |
| **Frontend** | Streamlit |
| **Environment** | virtualenv |
| **Version Control** | Git, GitHub |


## 📈 Model Training & Tuning

- **Dataset**: Public X-ray images (fractured vs. non-fractured)
- **Preprocessing**: Grayscale conversion, resizing, normalization
- **Dimensionality Reduction**: PCA
- **Classifier**: SVM (RBF Kernel)
- **Hyperparameter Optimization**: OPTUNA (automated best C, gamma selection)
- **Performance**: High accuracy, precision, and recall on unseen test data
- **Interpretability**: LIME visualizations for model transparency


## 🌐 Access & Availability

⛔ **Currently Private** – This repository and app are under review and will be **made public in September 2025**.

📩 **Want early access?**  
Send a request to: [aryanqureshi.official@gmail.com](mailto:aryannqureshi1@gmail.com)  
Subject: _Request for Bone Fracture Classification Project Access_


## 💡 How It Works

1. Upload an X-ray image via the Streamlit app  
2. The system:
   - Preprocesses the image
   - Reduces dimensions using PCA
   - Predicts using optimized SVM model
   - Generates LIME-based explanation  
3. Results + explanation are displayed in an intuitive dashboard


## 🔜 Future Enhancements

- 🧬 **Multi-class Classification** – Extend support to detect fracture types (e.g., hairline, displaced)
- 🧠 **Deep Learning Integration** – Incorporate CNNs or transfer learning models (e.g., ResNet, EfficientNet) for higher accuracy and automatic feature extraction
- 🧪 **Advanced XAI Methods** – Add Grad-CAM for deep model explainability
- 📱 **Mobile-Responsive Version** – Deploy lightweight UI for mobile and tablets
- ☁️ **Cloud Deployment** – Host on Streamlit Cloud, Hugging Face, or Azure for real-time access


## 🙌 Acknowledgements

- Open medical datasets used for training & validation  
- Community contributors and academic mentors for project guidance  
- Libraries: Scikit-learn, Streamlit, LIME, OPTUNA, OpenCV


## 📃 License

This project will be released under an **open-source license** (MIT or Apache 2.0) upon public release.

## 👨‍💻 Author

**Aryan Qureshi**  
Computer Science Student  
📧 [aryannqureshi1@gmail.com](mailto:aryannqureshi1@gmail.com)  
🔗 [LinkedIn]([https://www.linkedin.com/in/aryan-qureshi]) • [GitHub](https://github.com/Aryan1Qureshi)

## 🌟 Stay Connected

If you're interested in AI in healthcare or want to contribute, feel free to star ⭐ the repo and reach out!
