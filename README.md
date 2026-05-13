# SignVerse — Real-Time Speech to Sign Language Translator

SignVerse is an AI-powered real-time Speech-to-ASL translation platform that converts spoken language into corresponding sign language gestures using NLP and video mapping.
The project was built to improve accessibility and communication for the deaf and hard-of-hearing community through fast and intuitive translation.


## Features

- 🎤 Real-time speech recognition
- 🤟 Speech-to-ASL gesture translation
- 🧠 NLP-powered semantic phrase matching
- ⚡ Multi-word phrase prioritization
- 🎥 Dynamic gesture video rendering
- 🌐 Full-stack web application
- 📚 250+ gesture video mappings
- 🔄 Fast and scalable translation pipeline



#### Tech Stack

# Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Flask

### NLP & AI
- spaCy
- Semantic phrase matching
- Greedy algorithm optimization



## How It Works

1. User speaks into the application
2. Speech is converted into text
3. NLP engine processes and cleans the sentence
4. Semantic matching identifies the best sign mappings
5. Multi-word phrases are prioritized over individual words
6. Corresponding ASL gesture videos are rendered sequentially


## NLP Translation Engine

The translation system uses a hybrid NLP pipeline:

### Stage 1 — Text Processing
- Speech-to-text conversion
- Tokenization
- Cleaning and normalization

### Stage 2 — Semantic Matching
- spaCy-based NLP similarity matching
- Context-aware gesture mapping

### Stage 3 — Phrase Optimization
A greedy algorithm prioritizes:
- Multi-word gestures
- Meaning preservation
- Reduced translation fragmentation

This significantly improves translation quality compared to word-by-word mapping systems.



## Project Architecture

Speech Input
      ↓
Speech Recognition
      ↓
NLP Processing Engine
      ↓
Semantic Phrase Matching
      ↓
Gesture Mapping
      ↓
ASL Video Rendering


## Use Cases

* Accessibility tools
* Educational platforms
* Public service communication
* Assistive technology solutions
* Real-time interpretation systems


## Future Improvements

* Live webcam-based sign generation
* Support for multiple sign languages
* AI avatar animation
* Mobile application support
* Transformer-based NLP models
* Emotion-aware translations


## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/signverse.git
cd signverse
```

### Backend Setup

```bash
pip install -r requirements.txt
python app.py
```

### Frontend Setup

```bash
npm install
npm start
```

---

## Screenshots

Add screenshots or demo GIFs here.

Example:

* Home page
* Speech recognition interface
* Translation output
* Gesture rendering pipeline


## License
This project is licensed under the MIT License.

## Inspiration
SignVerse was created with the goal of making communication more inclusive and accessible through AI-powered assistive technology.

