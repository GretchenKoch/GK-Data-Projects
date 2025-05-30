# GK-Data-Projects

# 🐇 Gaming App Project: Rabbit Hole

## 📁 `rabbit-hole-timer`

**Overview**  
*Rabbit Hole* is a gamified Pomodoro-style timer designed to support focus and healthy distraction for users with executive function challenges—whether due to neurodivergence or simply a tendency to fall down increasingly irrelevant (but fascinating) tangents.

**Concept**  
Building on the traditional Pomodoro structure, *Rabbit Hole* introduces an animated cartoon rabbit that body doubles with the user. The rabbit works alongside you in its own little home office, typing at a computer during focus sessions. When it's time for a break, the rabbit leans into the screen and climbs through the monitor into a side-scrolling tunnel system—a visual metaphor for entering a “rabbit hole.”

As the rabbit explores, it encounters colorful orbs representing ideas, tabs, or distractions. It can only collect a few before returning to the surface, just in time for the next work cycle. The itch has been addressed—if not thoroughly scratched—and the day is not lost to an insatiable desire to learn everything about leafy sea dragons (as cool as they indisputably are).

**Skills and Tools**  
This project explores animation, behavioral design, and timeboxing mechanics through a Python-based prototype. Future iterations may include more advanced interactions, customizations, and data logging for visualization.


# 🧠 Exploratory Data Analysis Projects

This repository contains two exploratory data analysis (EDA) projects that recruit skills in data wrangling, visualization, and insight generation using Python. Each project focuses on a distinct type of dataset—- one small and community-based, the other large and government-sourced-- to highlight a range of analytical skills.

---

## 📁 `makeict-member-insights/`

**Dataset:**  
Membership interest survey data collected at MakeICT, a nonprofit makerspace in Wichita, KS.

**Goal:**  
Identify which activities and shop areas are most popular among new members to guide programming, outreach, and grant-writing decisions.

**Key Questions:**
- What are the most frequently selected interest areas?
- Are there overlaps or common combinations?
- How can these trends inform future planning?

**Methods:**  
Wrangled the data using Pandas, created summary tables and bar charts using Seaborn and Matplotlib, and explored patterns across time and categories.

---

## 📁 `cbp-inadmissibility-trends/`

**Dataset:**  
U.S. Customs and Border Protection (CBP) inadmissibility records (April 2025), obtained through FOIA.

**Goal:**  
Examine trends in grounds for inadmissibility and agency involvement, with an emphasis on transparency, public interest, and data ethics.

**Key Questions:**
- Are there identifiable patterns by charge type or custody transfer?
- How many immigrants were categorized as having gang affiliations, and what other factors might they have in common?


**Methods:**  
Parsed a large, inconsistent government dataset, cleaned and normalized column values, used Pandas GroupBy and visualized the findings to tell a data-driven policy story.

---

## 📁 `ai-robot/` (Voice assistant on Raspberry Pi)

## Goal
Build a voice-controlled AI robot using a Raspberry Pi, microphone, and speaker. It should be able to:
- Listen to voice input
- Process input using a chatbot model (e.g., GPT)
- Speak the response using text-to-speech

## Status
📦 Project planned, not yet started. Currently focusing on data analysis and app development.

## Dependencies (future)
- Python 3
- `speech_recognition`
- `pyttsx3` or `gTTS`
- OpenAI or Hugging Face `transformers`

## Stretch Goals
- Servo motor for movement
- LED responses
- Wake-word activation
