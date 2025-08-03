# 🛠️ Predictive Maintenance of Industrial Machinery

## 📌 Problem Statement
Unplanned machinery failures can cause costly downtimes in industrial operations. This project aims to develop a predictive maintenance system that uses real-time sensor data to detect and classify potential machine failures—such as tool wear, power failure, or heat dissipation issues—before they occur.

---

## 🎯 Objectives
- Analyze historical sensor data to detect failure patterns
- Build a machine learning classification model to predict failure types
- Deploy the model using IBM Watson AutoAI for real-time predictions
- Enable early maintenance scheduling to reduce downtime and costs

---

## 🗃️ Dataset
- **Source**: [Kaggle - Predictive Maintenance Classification Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
- **Features**: Type, Air temperature, Process temperature, Rotational speed, Torque, Tool wear, etc.
- **Target**: Machine failure type

---

## ⚙️ Technology Stack
- IBM Watson Studio
- IBM AutoAI (Tree Ensemble Classifier)
- Python (backend pipeline)
- Scikit-learn (via AutoAI)
- Watson Machine Learning for deployment
- IBM Cloud Object Storage

---

## 🧠 Model Summary
- **Best Model**: Batched Tree Ensemble Classifier (SnapML)
- **Accuracy**: 99.5%
- **Deployment**: Model deployed on IBM Watson as a web service for real-time predictions

---

## 📈 Results
- Achieved high accuracy with minimal false predictions
- Deployed model accepts CSV or real-time input via UI/API
- Outputs predicted failure type instantly for proactive decision-making

---

## 🚀 Future Scope
- Integrate real-time sensor data through IoT/Edge devices
- Apply deep learning models (LSTM, CNN) for complex failure patterns
- Expand to monitor machinery across multiple industrial plants

---

## 📚 References
- [IBM AutoAI Documentation](https://www.ibm.com/docs/en/cloud-paks/cp-data/4.5.x?topic=autoai-supported-algorithms)
- [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

---

## 👤 Author
Karunamayudu Doppalapudi
B.Tech - Computer Science and Engineering  
