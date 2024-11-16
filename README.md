# BrainWave
This is an educational tool which summarises and generates questions from YouTube URLs of educational content using Gemini API and YouTube transcript API.

## Installation
Clone the repository using git:
```bash
git clone https://github.com/Prajwal2212/BrainWave-using-Gemini.git
cd BrainWave-using-Gemini
```

## Dependencies:

1. The installation commands suggest the use of:\
2. youtube_transcript_api for fetching video transcripts.\
3. streamlit for creating an interactive web interface.\
4. pyngrok for hosting the tool on a temporary server.\
5. reportlab and texlive for generating formatted PDF reports, likely for summaries or question sets.

## Functionality:

- It uses the YouTube Transcript API to extract transcripts from educational YouTube videos.\
- The Gemini API is likely leveraged to process the transcripts, summarizing the content and generating relevant educational questions.\
- Streamlit provides a user-friendly interface for users to input YouTube URLs and access the results.

## Purpose:

The tool aims to aid in education by converting video content into easily digestible summaries and interactive learning aids like questions.

## User Workflow:

- Input a YouTube URL.\
- The tool fetches the video transcript.\
- It generates summaries and questions, potentially categorized by difficulty or type (e.g., multiple choice, short answer).\
- Outputs are displayed on the web interface and possibly exported as PDFs.
