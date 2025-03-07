
# SipakMed-GAN-ViT
This project focuses on generating synthetic cancer cell images using WGAN on the SipakMed dataset and addressing class imbalance with an Instruction Vision Transformer.

## SipakMed Dataset
The **SipakMed dataset** is a collection of **cell images** obtained from **Papanicolaou (Pap) smear tests**, used for detecting **cervical cancer**. It contains **5 classes** of cells:
1. **Superficial-Intermediate (SIP)**  
2. **Parabasal (PAB)**  
3. **Koilocytotic (KOC)**  
4. **Dyskeratotic (DYS)**  
5. **Metaplastic (META)**  

Each class has a limited number of images, leading to an **imbalance issue**, which is a challenge for deep learning models. In this project, I am using **WGAN** to generate synthetic cancer cell images and mitigate this imbalance using **Instruction-ViT**.

## Features
- Fine-tuned LSUN Generator from WGAN-PyTorch
- Synthetic image generation for cancer cells
- Instruction-ViT for class imbalance handling
## Generated Cancer Cell Images
Here are synthetic cancer cell images generated using WGAN:
![image](https://github.com/user-attachments/assets/ae66b364-26c4-47fe-bb98-024579e4e9ea)


## Next Steps
I am currently working on improving the generated images and addressing class imbalance. My next steps include:  

- 📌 **Mathematical Understanding**: Studying the underlying principles behind the WGAN algorithm for better fine-tuning.  
- 🏗 **Handling Class Imbalance**: Using an **Instruction Vision Transformer (ViT)** to rebalance the dataset by generating more underrepresented cancer cell images.  
- 📊 **Evaluation & Refinement**: Comparing the generated images with real ones and refining the generator’s architecture for improved quality.  
- 📝 **Documentation & Updates**: Regularly updating the repository with research findings, model improvements, and new results.  

Stay tuned for further updates! 🚀
