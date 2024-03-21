# Speech-to-Text Application for Unattended Retail Customer Service

## Overview
This Python application facilitates automated customer service in unattended retail environments by transcribing voice messages from callers and extracting pertinent information to autofill help requests. Developed for a SaaS company specializing in customer service solutions for unattended retail.

## Problem Statement
Unattended retail environments, such as micro-markets, electronic car chargers, and vending machines, often present consumers with issues they cannot resolve independently due to lack of time, tools, or expertise. Traditional call center solutions are not optimal for these environments, hence the need for an asynchronous workflow.

## Objective
The objective was to integrate a speech-to-text component into the company's text-based customer service application to accommodate consumers who prefer calling over texting. By leveraging deep learning tools and OpenAI's Large Language Models, the aim was to automate the handling of customer queries initiated via voice messages.

## How It Works
1. Recording Voice Messages: Users record voice messages describing their issue, along with their name and phone number.
2. Transcription: The application transcribes the voice message into text using OpenAI's transcription service.
3. Information Extraction: Pertinent information such as name, issue description, and phone number is extracted from the transcribed text using OpenAI's GPT-3.5 Turbo model.
4. Auto-filling Help Requests: The extracted information is utilized to auto-fill help request forms, streamlining the process of logging and addressing customer issues.

## Dependencies
Streamlit
Python
OpenAI

## Usage
1. Setup: Ensure all dependencies are installed.
2. Run the Application: Execute the Python script to start the Streamlit application.
3. Record Message: Users describe their issue and provide their name and phone number via voice message.
4. Transcription and Analysis: The application transcribes the voice message, extracts relevant information, and presents it for review.
5. Issue Resolution: The extracted information can be used to generate work orders and address customer issues efficiently.

## Future Enhancements
Integration with CRM systems for seamless issue tracking.
Support for multiple languages to cater to diverse customer bases.
Improved natural language understanding for more accurate transcription and information extraction.

Feel free to contribute to this project by forking and submitting pull requests!

https://github.com/zachjgraves/speech-to-text/assets/127673423/351d7389-17e2-4583-ae23-7a99253e8121

