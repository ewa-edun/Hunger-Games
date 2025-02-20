# **🔥 "Hunger Games: The Real Battle"🔥**  
## **"Hunger Games: The Real Battle – Can You Survive When Every Meal is a Choice?"** 🍽️🔥
🚀 A **text-based interactive survival game** where players navigate real-world food scarcity scenarios, making tough decisions that impact their survival.  

---

## **🎯 Core Objectives for MVP**
1. **Realistic & engaging gameplay** → Players experience food scarcity through different characters and choices.  
2. **Educational impact** → Raises awareness about food nutrition, budgeting, and survival in crisis situations.  
3. **Achievable within 4 days** → Prioritizing must-have features while leaving room for future improvements.  

---

## **🌍 Game Concept**
- Players **assume the role of a struggling character** (e.g., homeless youth, single parent, war refugee).  
- They make **critical food-related decisions** that affect their survival over a set period (e.g., 7 days).  
- Choices impact **hunger, health, and money meters** (survival bar).  
- **Multiple endings** based on decisions (e.g., thriving, malnutrition, hospitalization, death).  

---

## **🛠️ Features Breakdown**  
### **✅ Must-Have Features (MVP)**
| Feature | Description | Status |
|---|---|---|
| **Character Selection** | Choose from 3 different survival scenarios (e.g., Single Parent, Homeless Youth, War Refugee). | 🔥 Required |
| **Text-Based Adventure** | Players read scenario text and pick choices to progress the story. | 🔥 Required |
| **Survival Meter** | Tracks **Hunger**, **Health**, and **Money**. Each choice affects these stats. | 🔥 Required |
| **Branching Choices** | Different outcomes based on decisions (e.g., buying cheap fast food = health drop, but hunger filled). | 🔥 Required |
| **Basic UI** | Simple interface to show text, choices, and survival meter. | 🔥 Required |
| **3-Day Game Cycle** | Players must survive 3 days in-game, making decisions each day. | 🔥 Required |

### **💡 Nice-to-Have (If Time Allows)**
| Feature | Description | Status |
|---|---|---|
| **More Scenarios** | Expand to 5+ different survival stories. | ✨ Extra |
| **Mini-Games** | Small budgeting or food scavenging mechanics. | ✨ Extra |
| **Dynamic AI Dialogues** | Adaptive story text based on user actions. | ✨ Extra |
| **Character Save System** | Saves player progress. | ✨ Extra |
| **Visual Storytelling** | Background images representing locations (e.g., shelters, streets, grocery stores). | ✨ Extra |

---

## **🖥️ Tech Stack & Implementation**
### **🚀 Frontend (React and CSS)**
- **Displays story text & choices**  
- **Updates survival meters based on decisions**  
- **Simple UI: text box, buttons for choices, progress bars for survival stats**  

### **🖥️ Backend (Flask)**
- **Handles game logic & story progression**  
- **Processes and updates user choices**  
- **Stores character scenarios, choices, and results**  

### **📦 Database (Firestore or JSON)**
- **Stores branching storylines** (Character, Day, Choices, Outcome)  
- **Tracks survival stats changes**  

---

## **📝 Game Flow (Logic & Branching)**
1. **Choose a character scenario**  
   - Example: **Homeless Youth** → Living in a shelter, limited money, must find food.  
2. **Start Day 1**  
   - Player is given **$5 and 3 hunger points**.  
   - Three choices appear:  
     - 🥪 **Buy a cheap sandwich ($3)** → Hunger +3, Money -3.  
     - 🗑️ **Scavenge for food** → 50% chance of food, 50% risk of sickness.  
     - 🚶 **Look for a job** → Earns $5 but skips a meal (hunger -2).  
3. **Survival Meter Updates** → Hunger, health, and money adjust based on choice.  
4. **Repeat for 3 days** → Choices get harder, limited food options.  
5. **Endings Based on Survival Stats**  
   - **Good Ending**: Balanced nutrition, stable money = Character finds long-term help.  
   - **Neutral Ending**: Barely survived but remains struggling.  
   - **Bad Ending**: Malnutrition or starvation → Game over.  

---

## **📅 Execution Plan (4 Days)**
| Day | Task |
|---|---|
| **Day 1 (Today)** | Setup React & Flask, define characters & story structure, basic UI wireframe. |
| **Day 2** | Implement story progression (text, choices, survival meters), link frontend & backend. |
| **Day 3** | Add branching logic, balance gameplay, bug testing, UI improvements. |
| **Day 4** | Final testing, record hackathon video, submit project. |

---

## **🎬 Hackathon Submission Requirements**
1. **3-Minute Video Demo**  
   - Show **gameplay**, **features**, and **impact**.  
   - Explain **food scarcity connection**.  
   - Discuss **real-world impact & future improvements**.  
2. **GitHub Repo**  
   - Must have **working code & README**.  
3. **Pitch Deck (Optional, if extra time)**  
   - **Problem Statement, Solution, Tech Stack, Real-World Impact**.  

---
