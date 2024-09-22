# LLM-Based Projects Repository

This repository contains two projects that utilize LangChain and GPT to perform generative AI tasks. Both projects share a similar structure but focus on different outputs.

## Project 1: Social Media Post Generator

**File:** `social_media_post_generator.ipynb`

This project generates professional social media posts based on a user's answers to a questionnaire and a sample post. The generated post follows the format and tone of the provided sample, ensuring consistency in style, flow, and use of bullet points.

## Project 2: Personalized Timetable Generator

**File:** `student_timetable_generator.ipynb`

This project creates personalized study plans for students. It considers the student's academic subjects, learning styles, extracurricular activities, and other personal details to produce a tailored study timetable. The generated timetable is also converted into an HTML table for easy visualization.

## How to Run the Projects

 - Clone/download the repo
 - Install the requirements by running: `pip install -r requirements.txt`
 - Create a .env file, and add your OpenAI API key by adding the following line in the file: 
    `OPENAI_API_KEY="{YOUR_API_KEY_HERE}"`
 - Run either notebook
