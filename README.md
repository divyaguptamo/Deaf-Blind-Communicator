# Deaf-Blind-Communicator
## 🎯 Aim
To **bridge the communication gap between blind and deaf/mute individuals** by enabling real-time, two-way interaction using **speech-to-text** and **text-to-speech** technologies.

---

## 💡 Project Overview
This desktop-based Python application provides a GUI where:

- A **blind user** can speak → their words are converted to text using speech recognition.
- A **deaf/mute user** can type → their message is read aloud using a text-to-speech engine.
- A **webcam** detects a face before speech is recorded, ensuring speech input is intentional.
- A shared conversation box logs the entire communication, making it easy to follow.

---

## 🔍 Features
| Feature                             | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| 🎙️ Speech Recognition               | Blind users speak via mic → converted to text via Google Speech API        |
| ⌨️ Text Input + TTS                 | Deaf/mute users type → system speaks it using `pyttsx3`                    |
| 🧠 Face Detection Trigger           | Face detection (OpenCV) starts listening only when a user is visible       |
| 🪟 Interactive Tkinter GUI         | Smooth and simple interface for both users                                 |
| 🧾 Conversation History             | Full two-way message log within the app                                    |
| 🔄 Reset Button                     | Clears conversation for a fresh start                                      |

---

## 🛠️ Technologies Used

- **Python 3**
- **Tkinter** – GUI
- **SpeechRecognition** – Speech-to-text
- **pyttsx3** – Offline text-to-speech
- **OpenCV (cv2)** – Face detection with webcam
- **PIL (Pillow)** – To display static image (banner)

---
## 📸 Screenshot
<img width="411" height="474" alt="image" src="https://github.com/user-attachments/assets/2e519d36-af54-4245-868f-9eb66dc11f13" />
<img width="348" height="486" alt="image" src="https://github.com/user-attachments/assets/d176eacc-6fec-49f6-b0cd-d60f67a8f5bc" />
---
## ▶️ How to Run

### Step 1:Install dependencies:
pip install pyttsx3,SpeechRecognition, opencv-python, pillow

Step 2: Run the app
python Kalpana_Hackathon_final.py
---

## 🚀 Future Enhancements
- 🧠 **Language translation**: Support multilingual communication (e.g., Hindi ↔ English).
- 📡 **Offline speech recognition**: For use in low-internet areas using models like Vosk.
- 📲 **Mobile/Tablet version**: Develop an Android app using Kivy or Flutter.
- 🧾 **Save/export conversation**: Allow saving the chat log to a file (e.g., PDF or TXT).
- 🎨 **Accessibility mode**: Increase text size, contrast, or voice speed for better usability.
- 🔊 **Voice gender/accents**: Allow TTS customization for regional inclusivity.

## 🌍 Impact
This system can significantly improve day-to-day interactions for differently-abled individuals, especially in educational institutions, healthcare centers, or public services. It's a step toward inclusive communication using accessible and affordable technology.

## 👩‍💻 Author
**Divya Gupta**  
Passionate about building AI tools that solve real-world problems.


