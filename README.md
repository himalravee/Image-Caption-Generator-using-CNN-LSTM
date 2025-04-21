# Image Caption Generator using CNN-LSTM

This project is a deep learning-based **Image Caption Generator** that combines **Convolutional Neural Networks (CNNs)** for image feature extraction and **Long Short-Term Memory (LSTM)** networks for natural language generation. The model generates human-like captions for images, making it useful for accessibility tools, visual search engines, and social media platforms.

---

## 📚 Project Structure

```
Caption generate/
├── Caption_Generator.ipynb        # Jupyter Notebook with all code
├── best_caption_model.keras       # Best trained model (Keras format)
├── caption_model.h5               # Another model version (HDF5 format)
├── image_caption_generator.keras  # Saved model
├── image_features.pkl             # Extracted features from images
├── tokenizer.pkl                  # Tokenizer used for training
├── training_history.png           # Accuracy/loss graph
├── requirements.txt               # Python dependencies
├── README.md                      # Project description
└── captions.txt                   # Image filename + multiple captions
```

---

## 🌐 How It Works

1. **Feature Extraction**
   - A pre-trained CNN (InceptionV3) extracts image features.
2. **Text Tokenization**
   - The tokenizer encodes all training captions.
3. **Caption Generation**
   - A neural network with an LSTM decoder generates captions word by word.

---

## 🎨 Example Output

- Input: ![Image](sample.jpg)
- Output: "A dog is running through the grass."

---

## 🔧 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib (for plotting)
- Pre-trained CNN (InceptionV3)

---

## ✅ Setup Instructions

### Step 1: Clone the Repository
```bash
git clone https://github.com/himalravee/Image-Caption-Generator-using-CNN-LSTM.git
cd Image-Caption-Generator-using-CNN-LSTM
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the Notebook
```bash
jupyter notebook Caption_Generator.ipynb
```

---

## 🎓 Dataset
- The dataset used for training includes images and corresponding captions.
- Captions file: `captions.txt`
- Format: `image_name.png, caption`

---

## 📈 Results & Graphs
Training accuracy and loss graphs are saved in `training_history.png`.

---

## ✨ Future Improvements
- Use Transformer-based models (like BLIP or CLIP)
- Deploy with Streamlit or Flask
- Add attention mechanism for better results

---

## ✉️ Contact
**Author:** Himal Raveen
**GitHub:** [himalravee](https://github.com/himalravee)

---

## ⚡ Note
Some model files are large (>50MB). Consider using Git Large File Storage (LFS) if you face push errors.

Learn more: [Git LFS](https://git-lfs.github.com)

---

## ⚖️ License
This project is open-source and available under the MIT License.

