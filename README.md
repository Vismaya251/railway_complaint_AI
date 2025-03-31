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
  
**2.Copy & Paste the Code**

Copy the provided Python script and paste it into (project_name.py).
  
**3.Add Your Gemini API Key**

Locate line 49 in the code and replace the placeholder with your API key.

**4.Save the File**

Press (Ctrl + S) to save your work.

**5.Open Anaconda Prompt**

Launch Anaconda Prompt on your system.

**6.Run the Streamlit App**

Run this command in Anaconda Prompt: bash streamlit run project_name.py

**7.View the Output**

The app will launch in your browser, and you can start using it!

## Snapshots

**1.HomePage**
![image](https://github.com/user-attachments/assets/fd96f42d-ed9c-4edc-885b-91c3a9e2e4f4)

**2.File a complaint**

![image](https://github.com/user-attachments/assets/af9679e9-4e97-42d7-a364-d4c2fac9e96b)

- Through Type complaint
![image](https://github.com/user-attachments/assets/686b1301-e215-4066-a269-4db054dbb466)

- Through Record/Upload Audio
  ![image](https://github.com/user-attachments/assets/0d7f304d-6992-4620-92d8-009e3e21bf77)

 **3.Admin panel**
![image](https://github.com/user-attachments/assets/bb63ec22-242e-48e1-8615-b827621c3f82)

**4.Database Storage**
![image](https://github.com/user-attachments/assets/6a0896b5-8cb7-45b4-b56e-1b95a97e5a63)

**5.Email**
![image](https://github.com/user-attachments/assets/d3f29485-837f-48a9-afe2-3f0b5a4bf8c2)

## System Architecture

Below is the architecture diagram explaining how complaints are processed, categorized, and sent as notifications.

![image](https://github.com/user-attachments/assets/dccfbf9c-cff4-455d-b9d0-caa598737a83)

## Demo Video

Click the link to watch the full demonstration of the Railway Complaint System:
https://drive.google.com/drive/folders/1MAYDAIQLHCv9H5JOiPobE0sAAai7B9eb?usp=drive_link

Railway_complaint_AI_Demovideo

















  










   


