# 🌌 Multi-Mode AI Translator 🚀

Welcome, Traveler, to the ultimate communication nexus. This isn't just a translator; it's a bridge between languages, signals, and eras. Whether you're deciphering ancient Morse code or speaking to a new friend across the globe, this tool ensures your message is always understood.

![Welcome Screen](WELCOME-SCREEN.jpg)

---

## ✨ Mission Control: Core Features

Our station is equipped with state-of-the-art modules to handle any communication challenge:

* **🧠 AI Language Portal**: Powered by the Google Gemini API, instantly translate spoken or written words between a vast constellation of languages, including Tamil, Telugu, Spanish, and more.
* **📡 Morse Code Transceiver**:
    * **Encode**: Convert modern English into the timeless signals of Morse code.
    * **Decode**: Translate incoming Morse signals back into plain English using a direct text input or our interactive tap pad.
* **🎙️ Sonic Input (Voice-to-Text)**: Engage your microphone and speak your thoughts directly into the translator. The Web Speech API captures your voice for both language and Morse inputs.
* **🔊 Audio Playback (Text-to-Speech)**: Hear the pronunciation of any translation or text with the integrated audio playback feature.
* **- Text File Upload**: Decode entire documents by uploading `.txt` files directly. The system automatically checks if the content is suitable for the selected mode.
* **🛰️ Captain's Log (Translation History)**: A persistent log of all your language translations is automatically saved. Access your communication history at any time through a sleek pop-up modal.
* **💫 Dual-Star UI (Light & Dark Themes)**: Switch between a bright starburst theme or a deep space dark mode to suit your visual preferences.

---

## 🛠️ Tech Stack & Systems

This project is built with a fusion of powerful frontend and backend technologies:

* **Bridge (Frontend)**: `HTML5` | `CSS3` | `Tailwind CSS` | `JavaScript`
* **Engine Room (Backend)**: `Python` | `Flask`
* **Hyperdrive (APIs)**: `Google Gemini API` | `Web Speech API` | `Web Audio API`
* **Nav-Computer (Icons)**: `Lucide Icons`

---

## 🚀 Launch Sequence: Getting Started

Follow these instructions to get your own instance of the translator running locally.

### Prerequisites

* Python 3.7+ & `pip`
* A browser that supports the Web Speech API (**Google Chrome** or **Microsoft Edge** recommended)
* A **Google Gemini API Key**

### Installation & Ignition

1.  **Clone the Starship:**
    ```bash
    git clone <your-repository-url>
    cd morsecode
    ```

2.  **Power Up the Backend Engine:**
    * Navigate to the backend:
        ```bash
        cd backend
        ```
    * Create and activate a Python virtual environment:
        ```bash
        # For Windows
        python -m venv venv
        .\venv\Scripts\activate
        ```
    * Install all necessary components:
        ```bash
        pip install -r requirements.txt
        ```
    * Create a **`.env`** file in the `backend` directory to store your secret key.
    * Add your Google Gemini API key to it. You can get a free key from [Google AI Studio](https://aistudio.google.com/).
        ```env
        GEMINI_API_KEY="YOUR_SECRET_GEMINI_API_KEY_HERE"
        ```

3.  **Engage Both Servers (IMPORTANT):**
    This application requires **two terminals running simultaneously**.

    * **🚀 Terminal 1 (Backend API @ Port 5000):**
        ```bash
        # Make sure you are in the 'backend' folder
        python app.py
        ```
    * **🛰️ Terminal 2 (Frontend Server @ Port 8000):**
        ```bash
        # Make sure you are in the main 'morsecode' folder
        python -m http.server
        ```

---

## 👨‍🚀 How to Use

With both servers running, open your browser and navigate to the command bridge:

**`http://localhost:8000/welcome.html`**

From there, select your portal and begin your journey into universal communication!

---

## 🧑‍🚀 The Crew

This project was forged in the stars by **Rohit, Leno & Rahul (RLR)**.