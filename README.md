# Phishing URL Detection using Deep Learning and Knowledge Distillation

## 🧠 Overview
This repository presents a comparative study of deep learning architectures for **phishing URL detection**, including:

- **Convolutional Neural Network (CNN)**
- **Bidirectional Recurrent Neural Network (BRRN)**
- **Attention-Based Neural Network**
- **Teacher-Student Knowledge Distillation (RoBERTa → DistilRoBERTa)**

The models were trained on a curated dataset of phishing and legitimate URLs. Each model's performance was evaluated using **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **Confusion Matrix**.



---
![classimbalance](https://github.com/user-attachments/assets/f472337a-add8-43ea-a146-ac6f06f70605)
![CFM](https://github.com/user-attachments/assets/fcccb643-f43a-4269-bdd1-68c06e02da27)
![classbalance](https://github.com/user-attachments/assets/272c6fc2-62b8-4c7e-81e7-bbc5acec3ff1)
![model accuracy](https://github.com/user-attachments/assets/c5ad821c-b172-4abd-8c51-5c3b2549be78)
![precRecall](https://github.com/user-attachments/assets/91bd07fe-c16a-4956-bfbd-e38e1942a398)
![F-1](https://github.com/user-attachments/assets/8950a217-4c1e-4495-9237-3e0c0967b301)

---

## 📚 Research Publication
📄 Read the full academic paper: [**View Publication**](https://www.researchgate.net/publication/390873884_Title_A_Comparative_Study_of_Deep_Learning_Models_for_Phishing_Detection_Using_Teacher-Student_Learning)

---

## 📈 Results Summary
| Model                    | Accuracy | F1-Score (Phishing Class) |
|--------------------------|----------|----------------------------|
| CNN                      | 63.5%    | 0.72                       |
| BRRN                     | 54.7%    | 0.60                       |
| Attention Network        | 55.2%    | 0.61                       |
| Student (DistilRoBERTa)  | 75.0%    | 0.85                       |
| Teacher (RoBERTa)        | 75.0%    | 0.85                       |

---

## 🔍 Methodology Summary
- **Preprocessing:** Tokenization, URL cleaning, padding
- **Balancing:** Applied **SMOTE** to address class imbalance
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, Confusion Matrix
- **Visual Analysis:** Charts for metric comparison, heatmaps for confusion matrices

---


---

## 🛠️ Technologies Used
- **Python**
- **TensorFlow & Keras**
- **Hugging Face Transformers**
- **Scikit-learn**
- **Imbalanced-learn (SMOTE)**
- **Matplotlib, Seaborn**

---

## 📌 Citation
If you use this repository or reference the research, please cite:
```
Oluwadamilare Tobiloba. (2025). A Comparative Study of Deep Learning Models for Phishing Detection Using Teacher-Student Learning.
```

---

## 🙌 Acknowledgements
Special thanks to the open-source community for the tools and datasets that enabled this research.

---

## 📫 Contact
Have questions or suggestions? Feel free to reach out or connect:
- LinkedIn: [Profile]([https://linkedin.com/in/your-profile](https://www.linkedin.com/in/tobiloba-oluwadamilare-a850b0223/)
- Email: tbiggest4@gmail.com

