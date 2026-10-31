# YouTube Video Summarizer

## Project Overview
YouTube Video Summarizer is an AI-powered web application that extracts transcripts from YouTube videos and generates easy-to-understand summaries using the Google Gemini API. It helps users quickly understand lengthy videos and create useful study notes.

## Features
- Extract transcripts from YouTube videos.
- Generate AI-powered video summaries.
- Display important points and key information.
- Preview YouTube video thumbnails.
- Download generated summaries as Markdown files.
- Simple and user-friendly interface using Streamlit.

## Technologies Used
- Python
- Streamlit
- Google Gemini API
- YouTube Transcript API
- Python-dotenv

## Project Structure
```text
YouTube-Video-Summarizer/
│
├── app.py
├── requirements.txt
|──  README.md
```

## Installation and Setup

**1. Clone the repository**
```bash
git clone https://github.com/your-username/YouTube-Video-Summarizer.git
```

**2. Navigate to the project folder**
```bash
cd YouTube-Video-Summarizer
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Configure your API key**

Create a `.env` file in the project folder and add:
```env
GOOGLE_API_KEY=your_gemini_api_key
```

**5. Run the application**
```bash
streamlit run app.py
```

## How It Works
1. Enter a YouTube video URL.
2. The application extracts the available transcript.
3. The Gemini API processes the transcript.
4. The application generates a structured summary.
5. View and download the generated notes.

## Security
Never upload your `.env` file or expose your API key on GitHub.

## Author
Developed as an AI-powered project using Python and Generative AI.
