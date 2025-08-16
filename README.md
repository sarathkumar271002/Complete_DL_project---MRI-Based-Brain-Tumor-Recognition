# 🧠 Brain Tumor Detection using Deep Learning  

## 📌 Project Overview  
The goal of this project is to **detect brain tumors from MRI images** using deep learning.  
Since accuracy in medical diagnostics is critical, the model was optimized to achieve a minimal error margin.  

- **Dataset**: MRI scans labeled as **Positive (with tumor)** and **Negative (without tumor)**  
- **Approach**: Started with a **custom CNN**, then improved using **Transfer Learning (MobileNet)**  

---

## 🗂️ Dataset Preparation  
- **Split**:  
  - Training → 70%  
  - Validation → 15%  
  - Testing → 15%  
- **Data Augmentation**: Applied zoom, shear, and horizontal flip to improve generalization  

---

## ⚙️ Initial Model Development  
- **Architecture**: Custom **CNN** with Convolutional, MaxPooling, Dropout, and Dense layers  
- **Training**: Conducted on training set, validated on validation set  
- **Results**: Achieved **93% accuracy** on test set  
- **Limitation**: A 7% error margin is unacceptable in medical applications  

---

## 🚀 Model Improvement (Transfer Learning)  
- Adopted **MobileNet** as the base model  
- **Frozen pre-trained layers** and added custom dense layers for classification  
- **Callbacks**: Early stopping & Model checkpointing to prevent overfitting  

---

## 📊 Results  
- **Final Accuracy**: Significantly improved using MobileNet  
- **Error margin reduced** to meet medical standards  

## ✅ Conclusion  
- Successfully built a **Brain Tumor Detection Model** with high accuracy suitable for medical use  
- **Next Steps**:  
  - Experiment with other architectures (ResNet, EfficientNet)  
  - Use larger datasets  
  - Apply advanced augmentation techniques
 
## 📢 Author

👨‍💻 **Sarathkumar Soundarrajan**
📌 LinkedIn: (https://www.linkedin.com/in/sarathkumar271002/))
📌 GitHub: (https://github.com/sarathkumar271002)
