# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.
# Name: PRADEEP V
# Register no: 212223240119
# Aim: 
To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

## AI Tools Required: 
ChatGPT / OpenAI API (Core engine for prompt interaction)

Prompt Engineering Techniques (Role prompting, structured prompts, parameterized prompts)

# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

# Project Concept: “Your Personal Productivity Assistant”
The assistant will:

1.Organize daily tasks         

2.Schedule reminders

3.Suggest wellness tips

4.Answer general questions

5.Adapt to user preferences through prompts

# PHASE 1 — Basic Prompt (Manual)
# Prompt:
“Help me plan my tasks for today.”
# Example Output:
```
Your Tasks for Today:
- 8:00 AM – Check emails
- 10:00 AM – Attend team meeting
- 1:00 PM – Work on project
- 7:00 PM – Exercise
```
This is the most basic interaction — no customization, just a simple to-do list.

# PHASE 2 — Structured Prompt
# Prompt:

“Plan my daily schedule.
I have meetings at 10 AM and 3 PM.
I also want to include 2 hours for project work, 30 mins for wellness, and some personal time in the evening.”

# Example Output:
```
📅 Daily Schedule:
8:00 – 9:00 AM: Morning routine & exercise  
10:00 – 11:00 AM: Team Meeting  
11:30 – 1:30 PM: Project Work  
3:00 – 4:00 PM: Client Call  
6:00 – 7:00 PM: Personal Time (Hobby/Family)  
9:00 – 9:30 PM: Wellness Activity (Meditation/Reading)
```
Here, we’re giving structured input so ChatGPT can create a more personalized plan.

## PHASE 3 — Role Prompt + Format Instruction
# Prompt:

“You are my personal productivity assistant.
Create a detailed daily plan with the following:

Meetings: 10 AM, 3 PM

Project work: 2 hours

Wellness: 30 minutes

Output format: table with time, activity, and notes.”

# Example Output:
| Time           | Activity        | Notes                      |
| -------------- | --------------- | -------------------------- |
| 8:00–9:00 AM   | Morning Routine | Light exercise & breakfast |
| 10:00–11:00 AM | Meeting         | Team standup               |
| 11:30–1:30 PM  | Project Work    | Deep work (focus)          |
| 3:00–4:00 PM   | Client Call     | Status update              |
| 7:00–7:30 PM   | Wellness        | Meditation                 |
| 9:00–10:00 PM  | Personal Time   | Reading or hobby           |

Now the assistant sounds more professional and gives structured output.

# PHASE 4 — Advanced Prompt (Adaptive & Interactive)
# Prompt:

“You are my AI productivity assistant.
Consider my preferences:

I like exercising in the morning.

I prefer focusing on creative work before noon.

I want reminders for drinking water every 2 hours.
Create a daily plan and include reminders + wellness suggestions.
Respond in a friendly, natural tone.”

# Example Output:
```
🌞 Good Morning! Here’s your personalized daily plan:  
- 7:00 AM — Morning jog 🏃‍♂️ + hydration reminder 💧  
- 8:00 AM — Breakfast & prep for the day  
- 9:00–11:00 AM — Creative work session ✍️ (focus time)  
- 11:00 AM — Hydration reminder 💧  
- 1:00 PM — Lunch & short walk 🚶‍♂️  
- 3:00 PM — Team meeting 🧑‍💻  
- 5:00 PM — Wrap up work + light stretch 🧘‍♀️  
- 7:00 PM — Wellness activity (meditation or reading) 🌿  
- 9:30 PM — Personal time 🌙
```
This shows how the assistant can adapt to user preferences, make suggestions, and talk naturally.

# PHASE 5 — Turning Prompts into an Application
Feature Flow:

User inputs → Meetings, work duration, preferences, goals

App generates structured prompt → Sends to ChatGPT

ChatGPT → Returns personalized plan

App displays as table, timeline, or chatbot-style conversation

Optional: Store preferences for next sessions

# Example User Input UI:
```
- Meeting times: [10 AM, 3 PM]
- Work duration: 2 hours
- Wellness time: 30 min
- Preferences: morning exercise
```

# Output UI:
```
📅 Daily schedule
🔔 Reminders list
🌿 Wellness tip of the day
🧠 Smart suggestions
```
# PHASE 6 — Extra Examples (Other Use Cases)
| Feature                | Example Prompt                                                                      | Example Output                        |
| ---------------------- | ----------------------------------------------------------------------------------- | ------------------------------------- |
| ✅ Daily task organizer | “Organize my daily work for 8 hours including meetings, breaks, and learning time.” | Structured daily schedule             |
| 🧘 Wellness reminders  | “Give me hydration reminders every 2 hours.”                                        | Wellness + hydration tips             |
| ⏰ Smart reminders      | “Remind me to drink water every 2 hours and stretch after lunch.”                   | Reminder list                         |
| 💬 General queries     | “What’s a good 5-min stretch after sitting for long?”                               | Helpful tip                           |
| 📈 Adaptation          | “Remember that I prefer working at night.”                                          | Future schedules adjust automatically |

# Prompt Engineering Techniques Used:
| Technique              | Example                               | Why It Helps                |
| ---------------------- | ------------------------------------- | --------------------------- |
| 🧑 Role Prompting      | “You are my productivity assistant”   | Creates consistent persona  |
| 🧾 Structured Output   | “Give in table format”                | Easy to display & integrate |
| 🧠 Parameter Prompting | “I prefer mornings for exercise”      | Personalization             |
| 🪄 Natural Language    | “Respond in a friendly tone”          | Better user experience      |
| 🧭 Adaptive Prompting  | “Remember my preference for mornings” | Evolves with usage          |


# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.
