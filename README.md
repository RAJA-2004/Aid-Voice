<div align="center">
  <br />
  <h1>🗣️ Aid-Voice</h1>
  <p>
    <em>A voice-based interactive system designed to facilitate seamless communication between doctors and patients, <br/> enhancing accessibility and support for medical consultations.</em>
  </p>
  <p>
    <img src="https://img.shields.io/badge/-Python-black?style=for-the-badge&logo=python&logoColor=white&color=3776AB" alt="Python" />
    <img src="https://img.shields.io/badge/-Gradio-black?style=for-the-badge&logo=gradio&logoColor=white&color=FFB6C1" alt="Gradio" />
    <img src="https://img.shields.io/badge/-SpeechRecognition-black?style=for-the-badge&logo=google&logoColor=white&color=4285F4" alt="SpeechRecognition" />
  </p>
</div>

---

## 🧠 What is Aid-Voice?

**Aid-Voice** is a voice-enabled medical assistant system built using Python and Gradio. It aims to:
- Simulate real-time doctor-patient interactions via speech  
- Enable both parties to communicate through audio input/output  
- Enhance medical support accessibility for patients with language or typing difficulties

The system mimics intelligent voice flow handling using predefined models/scripts and voice-based prompts.

---

## 🗂️ Project Structure

| File/Folder               | Description                                           |
|---------------------------|-------------------------------------------------------|
| `voice_of_the_patient.py` | Handles patient-side voice interaction               |
| `voice_of_the_doctor.py`  | Generates AI doctor responses                        |
| `brain_of_the_doctor.py`  | Logic layer for doctor reasoning and reply synthesis |
| `gradio_app.py`           | Gradio-based UI for voice chat                       |
| `images/`                 | Image assets for the UI                              |
| `final.mp3`               | Sample voice output                                  |

---

## 🛠️ Tech Stack

- **Python** – Core language for logic and integration  
- **Gradio** – UI interface for web-based voice chat  
- **SpeechRecognition** – Voice input handling  
- **gTTS / pyttsx3** – Text-to-speech conversion  
- **pyaudio** – Audio streaming & processing  

---

## 🧪 How It Works

- User speaks via microphone input  
- Patient voice is converted to text  
- Doctor’s AI logic responds with a spoken reply  
- Interaction continues in conversational flow  

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/RAJA-2004/Aid-Voice.git
cd Aid-Voice

# Install dependencies
pip install -r requirements.txt

# Run the app
python gradio_app.py
```

---

## 🧩 Sample Demo

🎧 **Make sure your mic is enabled.**  
Speak as a patient and hear the doctor respond with a meaningful reply.

🎥 **Coming Soon:**

---

## 🧠 Example Use Case

> **"I have a fever and cough"** →  
> 🤖 *"It may be a viral infection. Please take rest, stay hydrated, and consider visiting a physician."*

This creates a voice-based consultation simulation that's easy to use for patients who cannot type or read fluently.

---

## 🌐 Connect with Me

<div align="center">
  Curious to learn more or collaborate on this? Let's connect!  
  <br/><br/>
  <a href="https://www.linkedin.com/in/rajadigvijaysingh/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Raja_Digvijay_Singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
</div>
