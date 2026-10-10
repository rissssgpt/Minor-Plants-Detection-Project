# 🌿 Medicinal Plant Identification Web App

A web application that identifies medicinal plant species from leaf/plant images using a Convolutional Neural Network (CNN) and returns key medicinal information such as dosage, action, Ayurvedic names, family and habitat.

🔗 **Live Demo:** [https://pmvd.netlify.app/](https://pmvd.netlify.app/)

---

## 📌 Overview

Identifying medicinal plants correctly is difficult for non-experts and time-consuming even for practitioners. This project lets a user upload a photo of a plant or leaf and instantly get the predicted species along with its medicinal details. It is useful for Ayurvedic practitioners, paramedical staff, botanists, researchers and students.

## ✨ Features

- **Image-based identification:** classifies **30+ medicinal plant species** with **92% accuracy**
- **Medicinal information:** displays plant name, dosage, action, Ayurvedic names, family and habitat
- **Multilingual UI:** interface available in multiple languages for wider accessibility
- **Speech synthesis (text-to-speech):** reads out results for visually impaired and low-literacy users
- **User authentication:** Login / Sign up through Firebase
- **Real-time storage & hosting:** Firebase integration
- **Responsive design:** works on desktop and mobile

## ⚙️ How It Works

1. **Upload an image:** user uploads a plant/leaf image (`.jpg`, `.jpeg`, `.png`)
2. **Image processing:** the image is preprocessed and prepared for the model
3. **Feature extraction & recognition:** a trained CNN extracts features and predicts the species
4. **Outcome:** the plant name and its medicinal information are displayed

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python, JavaScript |
| Model | Convolutional Neural Network (CNN) |
| Backend | Flask |
| Database / Auth / Hosting | Firebase |
| Model Deployment | Google App Engine |
| Frontend Deployment | Netlify |
| Training | Google Colab |

## 📂 Project Structure

```
├── static/            # CSS, JS, images
├── templates/         # HTML templates
├── uploads/           # Uploaded images
├── app.py             # Flask application
├── learn.ipynb        # Model training notebook
├── testing.py         # Model testing script
├── requirements.txt   # Python dependencies
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Python 3.9+
- pip
- A Firebase project (for auth and storage)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your Firebase configuration
#    Update the Firebase config in the project with your own keys

# 5. Run the app
python app.py
```

Open the URL shown in the terminal (usually `http://127.0.0.1:5000`) in your browser.

## 📊 Results

| Metric | Value |
|---|---|
| Plant species supported | 30+ |
| Model accuracy | 92% |

## 🔮 Future Enhancements

- Add more plant species and larger image datasets
- Continuously refine the model for higher accuracy
- Support live camera capture on mobile
- Add more regional languages
- Add a research/community section for collaboration

## 📬 Contact

**Rishabh Gupta**
GitHub: [rissssgpt](https://github.com/rissssgpt)
Live App: [pmvd.netlify.app](https://pmvd.netlify.app/)
