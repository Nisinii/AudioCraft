# Audio Craft - AI-Powered Adaptive Audio Script Generator

Audio Craft is an innovative script generation system that transforms textual narratives—such as book chapters or storylines—into fully-realized audio scripts. It intelligently incorporates customization of tone, genre, and creativity level, empowering users to adapt outputs to specific storytelling needs.

## Key Features

* **Narrative-to-Script Conversion:** Transforms plain text from stories or books into rich, production-ready audio scripts.
* **Deep Customization:** Allows users to control the script's tone, genre, and the precise level of AI creative input.
* **Intelligent Content Generation:** Uses OpenAI's GPT-3 to automatically generate character descriptions, dialogues, and scene headings.
* **Emotion Integration:** A custom-built sentiment analysis module detects and integrates character emotions into the script for a more authentic experience.
* **Sound Effect Enrichment:** Employs NLP to identify and annotate contextual sound effects (e.g., footsteps, ambient sounds) based on narrative cues.
* **Intuitive UI:** A clean frontend built in React allows for easy text uploads, setting adjustments, and script previews.

## Project Showcase

![1748699981347](https://github.com/user-attachments/assets/0ab50dbc-6850-4663-8aa1-4b545c2d1283)

![1748700075316](https://github.com/user-attachments/assets/ff3c169f-4f4c-4bcc-bbe6-b2996e1ae60e)

![1748700224615](https://github.com/user-attachments/assets/1d83ca33-62f8-486f-ae32-7403187426ea)



## How It Works

The system leverages a fine-tuned **OpenAI GPT-3** Transformer Model to perform deep natural language analysis, identifying characters, scene transitions, and dialogue structures within complex narrative texts. This allows for the generation of richly detailed audio scripts tailored to user-defined parameters.

A **custom-built sentiment analysis module** further enriches the output by detecting and integrating character emotions into dialogues and scene descriptions, enabling a more authentic and emotionally engaging audio experience.

In addition, Audio Craft incorporates **NLP-driven sound effect extraction**, where the system automatically identifies and annotates contextual sound effects based on narrative cues, enhancing the immersive quality of the audio script.

The frontend, built in **React**, offers an intuitive interface where users can upload text and adjust customization settings. The backend, powered by **Flask**, manages model integration and processing pipelines, ensuring smooth interaction between the frontend and AI-driven modules.

## Tech Stack & Skills

* **Frontend:** React.js
* **Backend:** Python, Flask
* **AI & NLP:** OpenAI (GPT-3), Prompt Engineering, Natural Language Processing (NLP), Sentiment Analysis
* **Design & UI:** Figma, User Interface Design
* **Architecture:** REST APIs, Microservices

 ---

## Getting Started

Follow these steps to set up Audio Craft on your local machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/Nisinii/AudioCraft.git](https://github.com/Nisinii/AudioCraft.git)
cd AudioCraft
```

### 2. Configure the AI Brain (Backend)
The backend is powered by Flask and requires an OpenAI API key to process the narratives.

1. Navigate to the app directory:
```bash
cd "Audio Craft/audio-craft-backend/app"
```

2. Set your API Key: Open the file generate_through_story.py and locate the following line:
```bash
# Set OpenAI API key
openai.api_key = "YOUR_API_KEY_HERE"
```
Replace "YOUR_API_KEY_HERE" with your actual OpenAI secret key.

3. Run the Flask server:
```bash
python app.py
```

### 3. Launch the Visual Interface (Frontend)
Open a second terminal window to run the React application.

1. Navigate to the frontend directory:
```bash
cd "Audio Craft/audio-craft-frontend"
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

---
### Check out the Live demo consisting of code explanation and the research behind this project
https://www.youtube.com/watch?v=7b4I8X8Nor0
