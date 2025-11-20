
# **Imagi – AI Text-to-Image Generator**

## **🧠 What is Imagi?**

Imagi is a lightweight AI-powered web application that transforms simple text prompts into fully generated images.
Using advanced text-to-image models, Imagi turns imagination into visuals through an intuitive and minimal web interface.

---

## **🚀 Key Features**

* Generate images using natural-language prompts
* Built-in gallery to view previously generated images
* Clean and responsive UI
* Fast local storage using SQLite
* Smooth Flask-based backend workflow

---

## **📂 Project Structure**

```
Imagi/
├── app.py                 # Main Flask backend
├── static/                # CSS and other static assets
│   └── gallery.css
├── templates/             # Frontend HTML templates
├── image_gen.db           # SQLite database for images
├── .env                   # Hugging Face API key
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

---

## **🛠️ Technology Stack**

* **Backend:** Flask (Python)
* **AI Model:** Hugging Face Inference API
* **Database:** SQLite
* **Frontend:** HTML, CSS
* **Image Processing:** Pillow (PIL)

---

## **🔧 Installation & Setup**

### **1. Clone the repository**

```
git clone https://github.com/Insaan01/Imagi.git
cd Imagi
```

### **2. Create a virtual environment**

```
python -m venv venv
```

Activate it:

* Windows: `venv\Scripts\activate`
* Mac/Linux: `source venv/bin/activate`

### **3. Install dependencies**

```
pip install -r requirements.txt
```

### **4. Add your Hugging Face API key**

Create a file named `.env`:

```
HF_TOKEN=your_token_here
```

### **5. Run the application**

```
python app.py
```

Open in browser:
**[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

## **📸 How Imagi Works**

1. User enters a text description
2. The backend sends the prompt to the Hugging Face model
3. The model returns a generated image
4. The image is displayed instantly
5. The image is saved in the gallery for future viewing

---

## **📈 Roadmap**

* Support for custom AI models
* Advanced prompt controls
* Multi-image generation
* Cloud storage support
* Improved gallery layout

---

## **🧾 License**

This project is open-source and free to use.

---
