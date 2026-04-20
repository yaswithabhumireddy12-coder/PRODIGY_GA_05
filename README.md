# PRODIGY_GA_05

# 🎨 Task-05: Neural Style Transfer

## 📌 Objective
Apply the artistic style of one image to the content of another image using Neural Style Transfer.

---

## 🧠 Concept
Neural Style Transfer (NST) is a deep learning technique that combines:
- **Content Image** → Structure of the image  
- **Style Image** → Artistic patterns (colors, textures)

Using a pre-trained CNN (VGG19 / TensorFlow Hub), the model extracts features and generates a new stylized image.

---

## 🛠️ Technologies Used
- Python  
- TensorFlow  
- TensorFlow Hub  
- NumPy  
- Matplotlib  
- Pillow (PIL)  

---

## ⚙️ How It Works

1. Load content and style images  
2. Preprocess images (resize, normalize)  
3. Pass images through pre-trained model  
4. Combine:
   - Content features  
   - Style features  
5. Generate stylized output image  

---
## 🌟 Preview
<img width="512" height="288" alt="stylized_output (1)" src="https://github.com/user-attachments/assets/0c0c5324-dded-43fc-b529-d7d577882523" />


## ▶️ How to Run

### 1. Install dependencies

### 2. Upload images
content.jpg
style.jpg
### 3. Run the code
python style_transfer.py
### 📸 Output
The generated image is saved as
stylized_output.jpg
