# Effects of Facial Hair on Face Recognition

This repository provides resources associated with the paper:

**“Effects of Facial Hair on Face Recognition”**  
*2025 IEEE 19th International Conference on Automatic Face and Gesture Recognition (FG 2025)*

---

## 📄 Paper

📘 **IEEE Xplore:**  
[https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11099142](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11099142)

---

## 🧠 Abstract

A person’s facial hairstyle, such as presence and size of beard, can significantly impact face recognition accuracy. While previous research has examined the facial hair effect using binary attributes, no work utilizes a segmentation model to capture the full extent of the facial hair. To investigate the effect of facial hair size in a rigorous manner, we first created a set of fine-grained facial hair annotations to train a segmentation model. Cross-dataset evaluation is performed and accuracy across African-American and Caucasian face images is reported. We then use our facial hair predictions to categorize image pairs according to the degree of difference or similarity in the facial hairstyle. We find that the False Match Rates for image pairs with different categories of facial hairstyle varies by a factor of over 10 for African-American males and over 25 for Caucasian males on MORPH dataset. Also, False Non-Match Rates of 4 race categories on BA-Test dataset are analyzed to measure the accuracy bias in unconstrained settings. Our findings suggest that, while facial hair can cause a shift in similarity score distributions, this effect can be mitigated by employing an adaptive threshold based on facial hair predictions.

---

## 📊 Facial Hair Annotations

Facial hair annotations used in this study are available at the following link:

👉 [Download Facial Hair Annotations (Google Drive)](https://drive.google.com/file/d/1n9ltHlvkpgpcaWMSAFS0qiu7Aq86NWlb/view?usp=drive_link)

---

## 🧩 Related Dataset

The annotations are based on the **CelebAMask-HQ** dataset:  
🔗 [https://github.com/switchablenorms/CelebAMask-HQ](https://github.com/switchablenorms/CelebAMask-HQ)

---

## 🧾 Citation

If you use this work, please cite:

```bibtex
@INPROCEEDINGS{11099142,
  author={Ozturk, Kagan and Bezold, Grace and Wu, Haiyu and Bhatta, Aman and Bowyer, Kevin W.},
  booktitle={2025 IEEE 19th International Conference on Automatic Face and Gesture Recognition (FG)}, 
  title={Effects of Facial Hair on Face Recognition}, 
  year={2025},
  volume={},
  number={},
  pages={1-10},
  keywords={Hair;Image segmentation;Adaptation models;Accuracy;Annotations;Face recognition;Gesture recognition;Predictive models},
  doi={10.1109/FG61629.2025.11099142}}
