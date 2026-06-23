# VaaniAI

> AI Powered Communication and Presentation Coach

## Overview

VaaniAI is an AI-powered, web-based system designed to help speakers become more confident, self-aware, and impactful communicators.

By analyzing verbal and non-verbal communication, VaaniAI provides holistic and adaptive feedback that helps users improve their speaking skills.

## What Makes VaaniAI Unique?

- **Multimodal Integration:** Combines audio, video, and text to deliver a complete analysis of communication style.
- **Accessibility and Inclusivity:** Tailored for marginalized communities, individuals with disabilities, non-native speakers, and anyone seeking affordable, personalized coaching.
- **Scenario-Based Training:** Practice in real-world contexts like interviews, presentations, and team discussions.
- **Comprehensive Feedback:** Integrates posture tracking, speech metrics, grammar correction, emotional analysis, sentiment analysis, and facial expression recognition.

## Tech Stack

- **MediaPipe:** Gesture, posture, and face tracking
- **Deepgram STT API:** Speech-to-text transcription
- **LanguageTool:** Grammar checks
- **Google Gemini:** Emotional analysis, sentiment summarization, and enhanced feedback
- **Python and Flask:** Backend logic and web server
- **ffmpeg:** Video and audio processing
- **NLTK:** Text analysis and sentence tokenization
- **Markdown:** Formatted feedback display

## Features

- **Speech Transcription:** Converts spoken words into text
- **Grammar Correction:** Identifies and suggests improvements for grammatical errors
- **Facial Expression Recognition:** Analyzes emotions conveyed through facial cues
- **Hand Gesture and Posture Analysis:** Evaluates body language effectiveness
- **Sentiment Summarization:** Provides an overview of emotional tone
- **Real-Time Feedback:** Gives feedback on verbal and non-verbal communication
- **Filler Word and Pause Detection:** Highlights speaking habits and helps reduce filler usage
- **Scenario-Based Training:** Simulates real-life communication challenges
- **Comprehensive Reporting:** Combines all analysis components into unified feedback
- **Playback and Review:** Supports reviewing recordings with feedback
- **Inclusivity:** Provides adaptive interfaces and feedback for diverse user needs

## Usage Guide

1. Start the application:

   ```bash
   python app.py
   ```

2. Open the web interface:

   ```text
   http://localhost:5000
   ```

3. Begin your session:

   - Speak or present as you normally would.
   - The system tracks gestures, posture, and facial expressions.
   - Receive actionable feedback on your delivery.
   - Review your performance with comprehensive reports.

## Folder Structure

```text
VaaniAI/
|-- app.py
|-- requirements.txt
|-- static/
|   |-- css/
|   |-- js/
|   |-- uploads/
|-- templates/
|-- images/
|-- README.md
```

## API Endpoints

| Endpoint           | Method | Description                         |
| ------------------ | ------ | ----------------------------------- |
| `/`                | GET    | Serves main recording interface     |
| `/save_video`      | POST   | Receives and processes recordings   |
| `/video`           | GET    | Serves latest processed video       |
| `/report`          | GET    | Returns latest posture report       |
| `/transcript`      | GET    | Returns latest speech transcript    |
| `/analysis`        | GET    | Returns latest speech analysis      |
| `/combined_report` | GET    | Returns all analysis components     |
| `/playback`        | GET    | Serves playback interface           |
| `/analyze_report`  | POST   | Triggers AI enhancement of analysis |
| `/llm_response`    | GET    | Provides latest enhanced feedback   |

## Installation Guide

1. Clone the repository:

   ```bash
   git clone 

2. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   Windows:

   ```bash
   venv\Scripts\activate
   ```

   macOS/Linux:

   ```bash
   source venv/bin/activate
   ```

4. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:

   ```bash
   python app.py
   ```

## Future Scope

- Advanced AI feedback with deeper context-aware recommendations
- Multilingual support
- VR/AR practice environments
- Industry-specific modules for legal, medical, technical, and other domains
- Mobile app support
- API development for platform integrations

## References

- Flask Documentation
- MediaPipe
- Deepgram
- Google Gemini
- NLTK
- LanguageTool


