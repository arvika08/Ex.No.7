
# **Ex. No. 7 – Develop a Prompt-Based Application Tailored to Personal Needs**

#### Date: 20/11/2025
#### Register No.: 212223060023

---

# **Aim**

To develop a prompt-based application using ChatGPT — demonstrating how to create a personalized **College Timetable & Assignment Manager** that helps organize class schedules, track assignments, set reminders, and manage deadlines using structured and context-aware prompt design.

---

# **Introduction**

This experiment focuses on designing a **prompt-based intelligent academic planner** using ChatGPT. The goal is to transform a general-purpose LLM into a customized tool that manages college routines, class timetables, and academic tasks through natural language interaction.

The assistant functions as a virtual academic organizer that helps students:

* View and update daily/weekly timetables
* Add assignment deadlines
* Track progress on submissions
* Identify free study slots
* Generate reminders and study tips

This lab experiment bridges theory and practice by showing how **prompt engineering techniques** can shape AI behavior to handle personalized student needs.

---

# **AI Tools Required**

| Tool Category        | Specific Tool (Example)             | Requirement Details                                       |
| -------------------- | ----------------------------------- | --------------------------------------------------------- |
| Primary LLM Platform | ChatGPT (or any GPT-based model)    | Used to power the academic planner assistant.             |
| Interface            | ChatGPT Web App / Prompt Playground | Enables interactive conversation and output testing.      |
| Supporting Tools     | Notepad / Google Docs               | For designing, refining, and documenting prompts.         |
| Optional Tools       | Lovable AI / Gemini                 | To further test multi-turn dialogues or build UI mockups. |

---

# **Explanation**

The project centers on building a **College Timetable & Assignment Manager AI (CTAM-AI)** that understands commands such as:

* “Show my timetable for Monday.”
* “Add a DBMS assignment due on Friday.”
* “List this week’s deadlines.”
* “Find free time for studying.”

Through **system-level prompting**, the AI behaves consistently as an academic assistant. It generates structured lists, maintains clarity, and supports natural, conversational inputs.

---

# **Prompt Design Strategy**

The master prompt was divided into three structured layers:

### **1. Role Definition**

Assign the AI the persona of an *Academic Planning Assistant*.

### **2. Functional Scope**

Define key capabilities:

* Timetable management
* Assignment tracking
* Deadline reminders
* Study suggestions
* Progress tracking

### **3. Response Format & Tone**

* Clear, neat bullet-style outputs
* A friendly, encouraging tone
* Include “Today’s Summary” when needed
* Show pending tasks at the end of each reply

---

# **Master Prompt Used (System Prompt)**

> **“You are AcademicBuddy, a smart College Timetable & Assignment Manager. You help students manage class schedules, assignments, deadlines, and study plans.
>
> Every response must include:**
>
> * A friendly acknowledgement
> * Updated timetable or assignment list (whenever changes occur)
> * Deadline highlights (today / this week)
> * A short study tip or motivational line
>
> Maintain a clear, concise, supportive tone. Adapt to the student’s weekly schedule and workload.”**

---

# **Progression from Simple to Advanced Prompting**

| Level            | Prompt Type               | Example                                                               | Impact on Output                                            |
| ---------------- | ------------------------- | --------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Simple**       | Direct Command            | “Add an assignment due tomorrow.”                                     | Adds basic entry; no subject or priority tagging.           |
| **Intermediate** | Contextual                | “Add a high-priority DBMS assignment due Friday evening.”             | Adds task with subject, priority, and timing.               |
| **Advanced**     | Structured & Multi-Action | “Show my Wednesday timetable and list all assignments due this week.” | Generates a combined schedule + deadline summary with tips. |

---

# **Procedure**

1. Open ChatGPT Platform.
2. Create a new session and paste the **Master System Prompt**.
3. Begin designing the assistant structure and interaction flow.
4. Test with simple prompts (add/view tasks).
5. Refine prompts to enable contextual understanding.
6. Test complex, multi-action prompts.
7. Document all observed outputs.
8. Insert screenshots of final app interactions.
9. Prepare final analysis and summary.

---

# **Expected Output & Analysis**


* Home Interface: <img width="1286" height="827" alt="image" src="https://github.com/user-attachments/assets/4138eefc-251a-4644-b5f3-429d814134c2" />
* Timetable Output: <img width="1251" height="717" alt="image" src="https://github.com/user-attachments/assets/bca69071-7f00-4e96-b362-b92eb5ed2ec8" /> <img width="1228" height="841" alt="image" src="https://github.com/user-attachments/assets/97ded067-2625-45c2-a804-7935c097b4ab" />


* Assignment List: <img width="1237" height="836" alt="image" src="https://github.com/user-attachments/assets/07735cbd-6815-4c3e-b032-ece09d7dfb4f" />

---

# **Detailed Feature Breakdown**

### **1. Timetable Manager**

* Stores weekly class timings
* Displays day-wise schedules
* Shows free time slots

### **2. Assignment Tracker**

* Adds tasks with deadlines & subjects
* Marks tasks completed
* Highlights overdue items

### **3. Deadline Reminder System**

* Notifies urgent deadlines
* Shows weekly academic load

### **4. Study Slot Finder**

* Detects free hours in the timetable
* Suggests ideal study periods

### **5. Motivational Feedback**

Examples:

* “You’re doing great—just one more task for today!”
* “Try the Pomodoro technique for better focus.”

---

# **Prompt Engineering Techniques Utilized**

* **Role-Based Prompting:** Gave the system a persona (AcademicBuddy).
* **Context Retention:** Maintains timetable and assignment list during session.
* **Constraint-Based Prompting:** Ensured bullet points and summaries.
* **Few-Shot Prompting:** Demonstrated sample outputs to guide behavior.
* **Iterative Prompt Refinement:** Improved consistency with each test.

---

# **Example Interactions**

### **User:**

“Add a high-priority DBMS assignment due Friday.”

### **AcademicBuddy:**

**Assignment Added**

* **DBMS Assignment**
* **Priority:** High
* **Due:** Friday

**Pending This Week:**

* DBMS Assignment – Friday
* Maths Tutorial – Wednesday

*Study Tip:* Break large tasks into 30-minute focused sessions.

---

### **User:**

“Show my Thursday timetable.”

### **AcademicBuddy:**

**Thursday Timetable:**

* 9–10 AM: Digital Electronics
* 11–12 PM: Python Lab
* 2–4 PM: Mini Project Work

*Free Slot:* 12–2 PM → Perfect for assignment work!
*Tip:* Review your DBMS notes before lab.

---

# **Conclusion**

The experiment successfully demonstrated how a language model like ChatGPT can be shaped into a functional **College Timetable & Assignment Manager** using structured prompt engineering. The assistant understood natural commands, provided organized schedules, reminded deadlines, and adapted its responses based on user interactions.

This exercise proved that **LLMs can be converted into practical academic tools using only prompt design—without any coding.**

---

# **Result**

Students were able to:

* Create a working AI-based academic planner using prompts
* Understand simple → advanced prompt engineering
* Manage tasks, schedules, and deadlines efficiently
* Apply generative AI for personal productivity and real-world academic support

---

