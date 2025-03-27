# ATS Resume Analyzer

A mini Streamlit app that compares your resume with a job description using Google's Gemini API. Built as part of my job search to simulate how an Applicant Tracking System (ATS) evaluates resumes.

## Overview
Upload your resume (PDF) and paste a job description. The app uses Gemini 1.5 Pro to give:
- HR-style evaluation
- Match percentage
- Missing keywords

## Tech Stack
Python 3.10  
Libraries: Streamlit, pdf2image, Pillow, google-generativeai  
Tools: Poppler, GitHub, Conda

## How It Works
- First page of the resume is converted to an image
- Sent with job description and prompt to Gemini
- Streamlit displays the feedback in real time



