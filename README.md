**AI-Driven Safe Music Listening Protecting Hearing Health in the Age of Personalized Audio**
An intelligent AI-powered system that monitors music characteristics in real time and automatically adjusts system volume to protect users from long-term hearing damage—without ruining the listening experience.

**Problem Statement:**
With the rise of personalized audio platforms and prolonged headphone usage, users are increasingly exposed to unsafe sound levels, especially during beat-heavy or high-energy tracks. Existing solutions only provide warnings, not automatic prevention.
This project solves that gap using AI & Machine Learning.

**Solution Overview:**
The AI-Driven Safe Music Listening System:
Detects the currently playing music automatically
Analyzes audio features in real time
Classifies songs into intensity levels
Automatically adjusts system volume
Protects hearing health intelligently and seamlessly

**Key Features:**
 Real-Time Song Detection (no manual upload)
 Machine Learning-Based Audio Classification
 Automatic System Volume Control
 Audio Feature Extraction (tempo, RMS, spectral features)
 User-Friendly Interface
 
**Tech Stack:**
Programming Language
Python 
Libraries & Tools
librosa – audio feature extraction
numpy, pandas – data processing
scikit-learn – ML model
sounddevice / pyaudio – audio capture
pycaw – system volume control (Windows)
tkinter / customtkinter – GUI
Machine Learning Model
Algorithm Used: Random Forest / SVM (configurable)

**Input Features:**
Tempo
RMS Energy
Spectral Centroid
Zero Crossing Rate
Output: Song intensity class

**How to Run the Project:**
1️⃣ Clone the Repository
git clone https://github.com/your-username/ai-driven-safe-music-listening.git
cd ai-driven-safe-music-listening

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Application
python main.py
