# EduOutline-AI

# Course Craft AI
Course Craft AI is an intelligent assistant designed to automate course outline generation and streamline the mapping of Course Learning Outcomes (CLOs) to Program Learning Outcomes (PLOs). Built for academic institutions following Outcome-Based Education (OBE), the system helps instructors generate structured outlines and evaluate CLO performance using AI and document parsing.

# Features
# Course Outline Generator
Upload a PDF or enter a course description

Generate a full course outline using AI (OpenAI/Cohere)

Automatically includes objectives, CLOs, textbooks, and weekly topics

# CLO Percentage Calculator
Upload an Excel file with student marks

Automatically detect CLOs and calculate attainment percentages

Add remarks for each CLO (e.g., "Attained", "Not Attained")

# CLO-PLO Mapping Extractor
Upload a Word document with a CLO-PLO mapping table

Parse the table and generate a structured CLO-to-PLO mapping

Combine results with CLO attainment data

# Downloadable Outputs
Final output is exported as an Excel file with structured and labeled sheets:

Course Outline

CLO Performance

CLO-PLO Mapping

# How It Works
# 1. Course Outline Generation

Accepts PDF or prompt

Sends it to the selected AI model

Parses structured output into headings like CLOs, textbooks, topics, etc.

# 2. CLO Calculation

Identifies CLO columns and "Total Marks" columns using regex

Calculates percentage and marks for each student

Summarizes performance by CLO

# 3. CLO-PLO Mapping

Reads Word table (using python-docx)

Matches CLOs to corresponding PLOs using table data

Prepares a mapping matrix

