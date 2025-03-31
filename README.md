# Railway Complaint System

Railway passengers often struggle with filing complaints efficiently, leading to delays in addressing critical issues. Our Railway Complaint System solves this by allowing users to submit complaints via text or voice, which are then automatically categorized using AI and forwarded to railway authorities via email faster resolution.
Built using AI, NLP, and speech recognition, this system provides a seamless complaint submission process with real-time notifications to ensure passenger grievances are addressed quickly.

## Features

**1.Multi-Mode Complaint Submission**
 - Text Input → Manually type and submit complaints.
 - Speech-to-Text → Speak directly, and the system converts it into text.
 - Voice Recording & Upload → Upload an audio file for complaint registration.
   
**2.AI-Powered Complaint Categorization**
 - Uses Google Gemini AI to auto-classify complaints into predefined categories.
 - Reduces manual work and speeds up complaint processing.
   
**3.Secure Database Storage**
 - All complaints are stored securely in a SQLite database for future reference.
 - 
**4.Real-Time Notifications**
 - Email Alerts → Sent to railway authorities for immediate action.
   
**5.Multi-Language Support**
 - Supports all 22 Indian languages including english for accessibility.
   
**6.User-Friendly Web Interface**
 - Built using Streamlit, providing a simple and intuitive UI.

## Tech Stacks

**1.Frontend & UI**
  - Streamlit → For creating a user-friendly web interface

**2.AI & NLP**
  - Google Gemini API → For text classification
  - SpeechRecognition → Converts voice input to text

**3.Database & Storage**
  - SQLite (sqlite3) → Lightweight database for storing complaint records.
  - Pandas (pandas) → For managing structured data within the application.

**4️.Notifications & Communication**
  - Smtplib (smtplib) → For sending emails via SMTP.
  - EmailMessage (email.message) → For structuring email content.

**5️.Other Utilities and sysytem functions**
   - OS (os) → For interacting with the file system.
   - Datetime (datetime) → For handling date and time data.
   - Random (random) → For generating unique complaint IDs.
   - Tempfile (tempfile) → For managing temporary file storage.
   - Collections (defaultdict) → For efficient data structuring

## Packages Required

1.Frontend & UI

bash pip install streamlit

2.AI & NLP

bash pip install google-generativeai speechrecognition 

3.Audio Processing

bash pip install sounddevice wave numpy pydub

## Steps to Set Up & Run the Project
**1.Create a Jupyter Notebook File**
- Open Jupyter Notebook and create a new file.
- Save it as (project_name.py).
  
2.Copy & Paste the Code
Copy the provided Python script and paste it into (project_name.py).
  
3.Add Your Gemini API Key
Locate line 49 in the code and replace the placeholder with your API key.

4.Save the File
Press (Ctrl + S) to save your work.

5.Open Anaconda Prompt
Launch Anaconda Prompt on your system.

6.Run the Streamlit App
Run this command in Anaconda Prompt: bash streamlit run project_name.py

7.View the Output
The app will launch in your browser, and you can start using it!




   


