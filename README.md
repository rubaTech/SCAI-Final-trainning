
 VirtuArena – Smart Stadium Experience Platform

VirtuArena is an AI-powered platform designed to enhance the fan experience inside stadiums during major sporting events. It combines smart pathfinding, live crowd analytics, and an interactive chatbot system to assist attendees in real-time.

: Project Idea
The goal of VirtuArena is to solve the issue of crowd management and poor user experience during large events. It allows fans to
 Navigate the shortest or least crowded route to their seat
Interact with a smart chatbot for FAQs and live updates
 Access real-time match schedules and event information

: Technologies Used
- AI Model: 
Trained using Random Forest to determine the least crowded or shortest path within the stadium based on simulated path data.
Chatbot: Built using  Dialogflow , integrated through  Make.com , and Working connected to a mobile Software .
Platform: Final system is designed for cross-platform deployment via mobile app.

 How It Works

1.  User opens the app  and clicks "Ask Assistant"
2. Predefined buttons  trigger Dialogflow intents connected via Make
3. The chatbot responds with:
   - Shortest path
   - Match schedule
   - Fan guidance or FAQs
4. Behind the scenes, AI models process live/stored data to give optimized recommendations

  Testing & Deployment

- Data simulation and training were performed using Google Colab.
- JSON flow files were uploaded to Dialogflow and tested through Make’s visual interface.
- Final integration is planned via FlutterFlow with API links to both AI model and chatbot.

  Team Highlights

- Built and trained custom AI model using simulated crowd data.
- Developed full chatbot experience using JSON logic and cloud automation.
- Presented in the SCAI Hackathon  with a 5-minute live demo.
- Integrated insights from existing smart stadium solutions and added localized features.

 Final Notes

VirtuArena represents a step toward future-ready stadiums in Saudi Arabia, aligning with Vision 2030's smart city transformation goals.  
This repository contains the full pipeline of our solution from data modeling to user interaction.
