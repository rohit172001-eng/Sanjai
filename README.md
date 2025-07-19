# 🧠 SanjAI – Your Smart Meeting Assistant

> _"Missed a meeting? SanjAI didn’t."_  
> An intelligent assistant that generates summaries, transcripts, and answers questions from your meeting recordings securely and automatically.

---

## 🚩 Problem Statement

Though platforms like Zoom offer built-in features for meeting transcription and summarization, enterprise environments like Oracle often disable these capabilities due to security and compliance concerns. This creates a gap in productivity tools for teams that rely heavily on virtual meetings.

---

## 💡 Our Solution – SanjAI

**SanjAI** is your intelligent meeting companion that transforms recordings into actionable insights.

Imagine if someone took perfect notes during your meetings, summarized them, and could even answer your questions afterward, that’s exactly what SanjAI does.
It eliminates the need for manual MoMs, makes every discussion searchable, and turns your meetings into a smart, secure knowledge base you can revisit anytime.

Built within Oracle Innovation Lab, this tool helps bridge the gap by privately processing meeting recordings and delivering actionable insights securely.

---

## 🔍 Key Features

- **🔁 Automatic Transcript Generation**  
  Once a Zoom meeting ends, the audio is processed and transcribed using internal scripts.

- **🧾 Summarization**  
  Automatically summarizes the meeting using an internal summarization service.

- **📩 Email Notifications**  
  Fetches the meeting details from Outlook Calendar and sends an authenticated summary link to all participants, no more manual MoMs.

- **📺 Interactive UI on Oracle APEX**  
  Users can view:
  - Meeting videos  
  - Speaker-by-speaker transcripts  
  - Scrollable video with synced transcript  
  - Downloadable content (video + transcript)  
  - Participant access management  

- **💬 Conversational Chatbot**  
  Ask questions like:  
  _“What was the demo about?”_  
  _“Who presented the solution?”_  
  SanjAI answers using the transcript context.

- **🔐 Access Control**  
  Only authorized participants can view meeting data ensuring enterprise-grade security.

- **🔎 Search Across Meetings** *(In Progress)*  
  Easily find past meetings by topic, date, or speaker.

---

## 🛠️ Tech Stack

- **Backend:** Python  
- **UI Platform:** Oracle APEX  
- **NLP Services:** Internal Summarization Service  
- **Calendar Integration:** COM   
- **Storage & Auth:** Secure internal Oracle storage and user authentication

---

## 🚀 Demo Walkthrough

A brief look at the demo meeting:
- Meeting files (audio, etc.) are stored after each Zoom call.
- The system automatically triggers processing scripts.
- Users receive a secure email with summary and transcript links.
- A chatbot answers any meeting-related questions from the transcript.
- The host can edit summaries, manage access, and more.

---

## 📦 Future Enhancements

- **Semantic Search Across Meetings**  
  Don’t remember when a particular thing was discussed? Just ask SanjAI. It will intelligently search across all past meeting transcripts using semantic understanding.

- **Keyword & Domain Context Awareness**  
  Allow users to configure domain-specific keywords, jargon, or business terms—tailored to each team's unique context—for more relevant summaries and chatbot responses.

- **Project-Based Meeting Segregation**  
  Organize and filter meetings by project, team, or business unit to easily retrieve relevant discussions and summaries.

---


## 📣 Feedback and Suggestions

Have an idea or feedback? Reach out to us internally or open an issue in this repository.
