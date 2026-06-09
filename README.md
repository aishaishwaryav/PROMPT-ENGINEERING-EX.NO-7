# EXPERIMENT NO: 7  
# DEVELOP A PROMPT-BASED APPLICATION TAILORED TO PERSONAL NEEDS USING LARGE LANGUAGE MODELS

## DATE: 27.05.2026
## REGISTER NUMBER: 212223220003

# AIM

To develop a prompt-based application using ChatGPT that demonstrates how prompts can be used to organize daily tasks, manage schedules, suggest wellness tips, and answer general queries using natural language interaction.

# AI TOOLS REQUIRED

- ChatGPT  
- Google Gemini  
- Microsoft Copilot  
- Python  
- VS Code / Jupyter Notebook  

# INTRODUCTION

Large Language Models (LLMs) such as ChatGPT are capable of understanding natural language and generating intelligent responses. Prompt-based applications use carefully designed prompts to perform real-world tasks such as scheduling, reminders, wellness suggestions, and personal assistance.

This experiment focuses on designing a personal productivity assistant powered by AI. The assistant interacts naturally with users and adapts to user preferences over time.

# PROBLEM STATEMENT

Design a personal productivity assistant that can:
- Manage daily tasks  
- Schedule reminders  
- Suggest wellness tips  
- Answer general queries  
- Interact using natural language  
- Adapt to changing user preferences  

# OBJECTIVES

1. To understand prompt-based application development.  
2. To create prompts for productivity-related tasks.  
3. To simulate user interaction with an AI assistant.  
4. To analyze how LLMs improve daily productivity.  
5. To explore personalization using prompts and memory adaptation.

# PROCEDURE

1. Define the requirements of the productivity assistant.  
2. Construct prompts for task management and scheduling.  
3. Simulate natural user interaction using AI tools.  
4. Generate wellness suggestions using prompts.  
5. Collect user feedback and adapt responses.  
6. Implement simple memory adaptation for personalization.

# CORE FEATURES OF PERSONAL PRODUCTIVITY ASSISTANT

## 1. Daily Task Manager

- Accepts tasks in natural language  
- Organizes tasks by priority  
- Displays pending tasks  
- Generates daily summaries  

### Example Prompt

```text
Remind me to submit my assignment at 7 PM today.
```

### Example Output

```text
Reminder set successfully for 7 PM: Submit assignment.
```

# 2. SMART SCHEDULER

- Schedules meetings and events  
- Detects overlapping appointments  
- Suggests free time slots  

### Example Prompt

```text
Schedule a meeting tomorrow at 10 AM with the project team.
```

### Example Output

```text
Meeting scheduled for tomorrow at 10 AM with the project team.
```

# 3. WELLNESS TIPS GENERATOR

- Suggests hydration reminders  
- Encourages exercise and breaks  
- Provides healthy lifestyle tips  

### Example Prompt

```text
Give me a wellness tip for today.
```

### Example Output

```text
Remember to drink enough water and take a 5-minute break every hour while working.
```

# 4. GENERAL QUERY ASSISTANT

- Answers common questions  
- Provides quick information  
- Supports conversational interaction  

### Example Prompt

```text
What is cloud computing?
```

### Example Output

```text
Cloud computing is the delivery of computing services such as storage, servers, and software over the internet.
```

# SYSTEM DESIGN

```text
User Input
     ↓
Prompt Processing
     ↓
Large Language Model
     ↓
Task Analysis
     ↓
Generated Response
     ↓
User Interaction
```

# SAMPLE PYTHON CODE

```python
tasks = []

while True:
    print("\n1. Add Task")
    print("2. View Tasks")
    print("3. Exit")

    choice = input("Enter choice: ")

    if choice == "1":
        task = input("Enter task: ")
        tasks.append(task)
        print("Task added successfully!")

    elif choice == "2":
        print("\nPending Tasks:")
        for t in tasks:
            print("-", t)

    elif choice == "3":
        print("Exiting Productivity Assistant")
        break

    else:
        print("Invalid choice")
```

# SAMPLE OUTPUT

```text
1. Add Task
2. View Tasks
3. Exit

Enter choice: 1
Enter task: Complete AI assignment
Task added successfully!

Enter choice: 2

Pending Tasks:
- Complete AI assignment
```

# PROMPT EVOLUTION

| Prompt Type | Example | Output Quality |
|---|---|---|
| Simple Prompt | "Set reminder" | Basic response |
| Refined Prompt | "Remind me to attend the AI class at 9 AM tomorrow." | Detailed response |
| Contextual Prompt | "Based on my study schedule, remind me to revise AI topics tonight." | Personalized response |

# BENEFITS OF THE APPLICATION

- Improves productivity  
- Saves time  
- Organizes schedules efficiently  
- Provides personalized interaction  
- Encourages healthy habits  

# APPLICATIONS

- Student task management  
- Office productivity systems  
- Personal wellness tracking  
- Smart scheduling systems  
- AI virtual assistants  

# LIMITATIONS

- Requires internet connectivity  
- AI responses may occasionally be inaccurate  
- Advanced memory adaptation requires databases  
- Complex scheduling may need external APIs  

# ANALYSIS OF AI TOOLS

| AI Tool | Strength | Weakness |
|---|---|---|
| ChatGPT | Detailed responses | May generate lengthy output |
| Gemini | Fast responses | Less detailed explanations |
| Copilot | Coding assistance | Limited conversational interaction |

# EXPECTED OUTPUT

## Personal Productivity Assistant Features

### Daily Task Manager
- Accept tasks via natural language  
- Organize tasks by priority and deadline  
- Provide daily summaries and pending items  

### Smart Scheduler
- Schedule events and reminders  
- Detect overlapping schedules  
- Suggest free time slots  

### Wellness Tips Generator
- Suggest hydration reminders  
- Recommend exercise and breaks  
- Adapt suggestions based on preferences  

# CONCLUSION

The experiment demonstrated how prompt-based applications can be developed using Large Language Models such as ChatGPT. The productivity assistant successfully managed tasks, scheduled reminders, generated wellness tips, and answered user queries through natural language interaction. Prompt refinement improved the quality and personalization of responses.

# RESULT

The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. The experiment helped in understanding prompt engineering techniques, designing personalized AI features, and exploring the practical applications of generative AI in solving everyday productivity problems.
