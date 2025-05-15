# AgriAid - Multilingual Crop Disease Diagnosis

## Overview
AgriAid is an AI-powered web application that helps farmers diagnose crop diseases and get treatment recommendations in multiple languages. The application uses Google's Gemini AI to analyze text descriptions, images, and audio recordings of plant issues.
Streamlit app: https://agriaid.streamlit.app/

## Features
**Multilingual Support**: Interface available in multiple languages including English, Hindi, Spanish, French, Tamil, Telugu, and Kannada

**Multiple Input Methods**:
  
  Text descriptions of crop symptoms
  
  Image uploads of affected plants
 
  Audio recordings describing the issues

**AI-Powered Analysis**: Uses Google's Gemini AI to diagnose plant diseases and provide treatment recommendations

**Audio Output**: Converts diagnosis results to speech for accessibility

**Responsive Design**: Works on both desktop and mobile devices

## Requirements
Python 3.8+
Streamlit
PIL (Pillow)
Google Generative AI
gTTS (Google Text-to-Speech)
Deep Translator

## Setup
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up your Gemini API key in Streamlit secrets:
   ```
   [secrets]
   GEMINI_API_KEY = "your-api-key-here"
   ```
4. Run the application: `streamlit run app.py`

## Usage
1. Select your preferred language
2. Choose an input method (Text, Image, or Audio)
3. Provide information about your crop issue
4. Click "Diagnose" to get AI-powered analysis
5. View the diagnosis results and listen to the audio explanation if needed

## Project Structure
- `app.py`: Main application file
- `utils/`: Helper modules
  - `gemini_api.py`: Functions for interacting with Gemini AI
  - `translation.py`: Translation utilities
  - `translation_loader.py`: Loads language translations
  - `gemini_audio.py`: Audio processing functions

## Notes
- Diagnosis accuracy depends on input quality
- For critical cases, consult a professional agronomist
- Supported crops include tomatoes, potatoes, wheat, rice, and common vegetables

# ____________________________________________________________________________
 
# OUTPUT

![image](https://github.com/user-attachments/assets/59365fb2-6553-4c31-871c-c105d62789f7)

![image](https://github.com/user-attachments/assets/e41e077e-2057-4de7-bb7b-ca1b9eefe2e7)

![image](https://github.com/user-attachments/assets/5cebd2fb-ec6e-4c31-a777-d2ff6effd3f6)

![image](https://github.com/user-attachments/assets/2ede25f4-ad77-4b54-8d49-0739de36499f)

# ____________________________________________________________________________
# App

![app3](https://github.com/user-attachments/assets/567b25d3-df2a-481e-ba68-292420586d1b)

![app5](https://github.com/user-attachments/assets/065e6c49-ea28-4c4f-b17e-afeee54fa5c4)



