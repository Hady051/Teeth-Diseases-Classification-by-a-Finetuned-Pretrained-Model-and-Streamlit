# Teeth-Diseases-Classification-by-a-Finetuned-Pretrained-Model-and-Streamlit

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project trains a deep learning model to classify dental images into different categories using **MobileNetV2** as the backbone. The trained model is then deployed as an interactive **Streamlit app**, accessible via **ngrok** in Google Colab.

### 📂 Dataset
The dataset is expected in the following structure:
Teeth DataSet/
 ├── train/
 │    ├── CaS/
 │    ├── CoS/
 │    ├── Gum/
 │    ├── MC/
 │    ├── OC/
 │    ├── OLP/
 │    └── OT/
 ├── val/
 │    └── (same structure as train)
 └── test/
      └── (same structure as train)

## The 7 classes are:

* CaS – Cavity Surface

* CoS – Composite Surface

* Gum – Gum related conditions

* MC – Missing Crown

* OC – Oral Cyst

* OLP – Oral Lichen Planus

* OT – Other

## Sample:

<img width="1366" height="647" alt="Sample 1" src="https://github.com/user-attachments/assets/aaa9c26f-d709-40c8-a4d4-a72bc8f71cd2" />

<img width="1216" height="644" alt="Sample 2" src="https://github.com/user-attachments/assets/083bf626-39a5-4b66-9f0a-51c3666f1212" />

<img width="1092" height="457" alt="Sample 3" src="https://github.com/user-attachments/assets/c557ea25-9344-4812-83c8-76a3b0ae64af" />
