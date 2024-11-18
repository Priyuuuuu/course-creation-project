# course-creation-project
This project automates course creation by extracting transcripts from YouTube videos, summarizing the content, and converting it into engaging multimedia outputs like presentations and videos.

Features:
YouTube Transcript Extraction: Fetches transcripts for the top 5 relevant YouTube videos on a given topic using the YouTube Transcript API.
Content Summarization: Combines and summarizes the extracted transcripts into a cohesive narrative.
PowerPoint Presentation Generation: Creates a visually appealing PowerPoint presentation from the summarized content.
Audio Conversion: Generates audio narration for the presentation using Google Generative AI (Gemini).
Video Creation: Converts the presentation slides into images and combines them with the audio to create a video.
GitHub Integration: Easily share your project with the community.

Project Workflow :
  Input Topic: User provides a topic or keyword.
  Fetch YouTube Transcripts: Retrieves transcripts for the top 5 related YouTube videos.
  Summarize Content: Combines and summarizes the transcripts.
  Generate Presentation: Converts the summarized content into PowerPoint slides.
  Add Narration: Uses AI to generate audio narration for the slides.
  Create Video: Converts the slides and audio into a video format.

run command:
streamlit run youtube.py
pip install -r requirements.txt
