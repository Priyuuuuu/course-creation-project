# Course Creation Project

## Project Overview

This project automates course creation by extracting transcripts from YouTube videos, summarizing the content, and converting it into engaging multimedia outputs like presentations and videos. It leverages cutting-edge AI tools to simplify and enhance the content creation process, making it an ideal solution for educators, trainers, and content creators.

---

## Features

- **YouTube Transcript Extraction**
  - Fetches transcripts for the top 5 relevant YouTube videos on a given topic using the YouTube Transcript API.

- **Content Summarization**
  - Combines and summarizes the extracted transcripts into a cohesive narrative.

- **PowerPoint Presentation Generation**
  - Creates a visually appealing PowerPoint presentation from the summarized content.

- **Audio Conversion**
  - Generates audio narration for the presentation using Google Generative AI (Gemini).

- **Video Creation**
  - Converts the presentation slides into images and combines them with the audio to create a video.

- **GitHub Integration**
  - Easily share your project with the community.

---



## Technologies Used

- **Frontend**: Streamlit
- **Backend**: Python
- **AI Tools**: Google Generative AI (Gemini), LangChain
- **APIs**: YouTube Transcript API
- **Libraries**: OpenAI, PyTube, moviepy, python-pptx
- **Presentation Tool**: PowerPoint

---

## Setup Instructions

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-repo/course-creation-project.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd course-creation-project
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application**:
   ```bash
   streamlit run youtube.py
   ```

---




