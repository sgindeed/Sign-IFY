# ✍️ Sign-IFY 🔍

[![🚀 Deployed on Render](https://img.shields.io/badge/Deployed%20on-Render-brightgreen)](https://signify-dpcu.onrender.com/)

## 🔎 Overview
**Sign-IFY** is a **signature verification tool** 🌟 that uses **AI-powered image processing** to check if two signatures belong to the same person. Perfect for identity verification and fraud detection!

## 🚀 Features
- 🔍 **Quick Signature Comparison**: Upload two signature images and get a similarity score in seconds.
- ⚙️ **Advanced Image Processing**: Leveraging OpenCV for precise template matching.
- 🎨 **Intuitive Interface**: Simple, clean, and user-friendly for quick verifications.
- 🌐 **Online Access**: Check out Sign-IFY anytime on Render 👉 [Sign-IFY on Render](https://signify-dpcu.onrender.com/).

## 📂 Project Structure

```
Sign-IFY/
├── app.py                   # Flask app logic
├── requirements.txt         # Project dependencies
├── templates/
│   └── index.html           # Frontend template
└── uploads/                 # Stores uploaded images
```

## 🛠️ Getting Started

### Prerequisites
- Python 3.x 🐍
- Libraries listed in `requirements.txt` 📄

### Installation
1. **Clone the Repository** 📥:
   ```bash
   git clone https://github.com/sgindeed/Sign-iFY.git
   cd Sign-iFY
   ```

2. **Install Dependencies** 📦:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application** 🚀:
   ```bash
   python app.py
   ```
   The app will be accessible at `http://127.0.0.1:5000`.

### 🌐 Deployment on Render
Already live! Visit the app at [https://signify-dpcu.onrender.com/](https://signify-dpcu.onrender.com/) 🌎.

## 🖱️ How to Use
1. **Visit the app** locally or online.
2. **Upload** the signature image and the reference image.
3. **Receive** instant feedback with:
   - A **Match Score** 🎯: Numeric similarity between the images.
   - A **Match Status** ✅❌: Indicates if the signatures are likely from the same person.

## 📊 How It Works: Signature Matching

1. **Image Preprocessing** 🖼️: Resizes images for a standard comparison.
2. **Template Matching** 🔍: Uses `cv2.matchTemplate` to check similarity.
3. **Threshold Evaluation** 📈: Scores above 70% indicate a likely match.

## 🛠️ Tech Stack
- **Backend**: Python + Flask 🐍
- **Frontend**: HTML (Jinja2 Templates) 📄
- **Image Processing**: OpenCV + NumPy 🔍
- **Deployment**: Render 🚀

## 🤝 Contributions
**Your contributions are welcome!** 🛠️ 
1. **Fork** the repo 🍴.
2. **Create a Branch** (`feature/YourFeatureName`) 🌿.
3. **Commit** your changes 💾.
4. **Push** and **Open a PR** 🚀.

## 📬 Contact
For questions or feedback, reach out to the maintainer [@sgindeed](https://github.com/sgindeed) on GitHub.
