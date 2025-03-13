# azoniAi-discord

# 📚 Azoni AI Discord Bot Documentation

*A multi-functional AI-powered bot that integrates with Google Calendar, processes files, plays games, and responds intelligently to user messages.*

---

## 🌟 Core Functionalities

### 💬 AI-Powered Chat

- The bot **engages in casual conversations** and avoids sounding robotic.
- It considers:
  - **Recent conversations**
  - **User's known facts**
  - **Sentiment analysis**
  - **Upcoming calendar events**
- It adjusts responses **based on your schedule**, ensuring:
  - **No conflicts when making plans**
  - **Awareness of your free time**

#### Example Interactions:

- **User:** "Hey, what's up?"  
  **Bot:** "Not much! You have a gym session at 6 PM today. Planning to go?"

- **User:** "Let's do lunch tomorrow."  
  **Bot:** "You and Jane already have a meeting at 1 PM. How about 11:30 AM instead?"

---

## 📅 Google Calendar Integration

The bot **syncs** with both **Charlton's** and **Jane's** calendars.

### 🔍 Check Today’s Schedule

**Command:**

```bash
.today
```

**Response:**

- Lists **today’s events** from both calendars (removes duplicates).
- Shows **who is attending**.
- AI gives a **summary of the day**.

---

### 📆 Check Any Day’s Schedule

**Command:**

```bash
.day <day>
```

**Example:**

```bash
.day Friday
```

**Response:**

- Fetches events **for the requested day**.
- Merges duplicate events.
- Provides **daily reminders**.
- AI **summarizes** the day's importance.

---

### 📅 View Upcoming Events

**Command:**

```bash
.events
```

**Response:**

- Shows **upcoming events** (from both calendars).
- **Sorted by date**.

---

### 📌 Add a Calendar Event

**Command:**

```bash
.add_event <title>, <description>, <start time>, <end time>, [attendee1@example.com, attendee2@example.com]
```

**Example:**

```bash
.add_event Lunch with Sarah, Catch up, tomorrow at 12PM, tomorrow at 1PM, sarah@example.com
```

**Response:**

- Adds an event **to Charlton's calendar**.
- Sends invites to attendees.

---

## 📂 File Processing

The bot can **read and summarize** files.

### 📝 Supported File Types

- **PDFs**
- **Word Documents (.docx)**
- **Images** (For AI processing)

**Process:**

- Upload a file and mention the bot.
- It extracts text and **summarizes** long documents.

---

## 🎭 Fun Features

### 🧈 Rock-Paper-Scissors

**Command:**

```bash
/rps <choice> [opponent]
```

**Example:**

```bash
/rps rock
```

**Modes:**

- **Play against the bot** 🤖
- **Challenge a friend** 🆚

---

### 🎤 GIF Search

**Command:**  
Mention the bot and include "gif" in your message.

**Example:**

```bash
Azoni, show me a funny gif!
```

**Response:**

- Fetches a **random GIF** from Tenor.

---

## 🛠️ Utilities & Database Features

### 📝 Save & Recall Facts

The bot can **store and recall facts** about users.

#### Save a Fact

**Command:**

```bash
.add_fact <username> <fact>
```

**Example:**

```bash
.add_fact Charlton loves pizza.
```

**Response:**  
"Fact about Charlton has been recorded."

#### Retrieve Facts

**Command:**

```bash
.facts <username>
```

**Example:**

```bash
.facts Charlton
```

**Response:**

- Lists all **stored facts**.

#### Show All Stored Facts

**Command:**

```bash
.all_facts
```

**Response:**

- Displays **all saved facts** from the database.

---

### 🛠️ Delete Facts

**Command:**

```bash
.clear_db *
```

**Response:**

- **Deletes everything in the database**.

**Command:**

```bash
.clear_db <keyword>
```

**Example:**

```bash
.clear_db pizza
```

**Response:**

- **Removes all entries** that mention *pizza*.

---

### 🗃️ View Chat History

**Command:**

```bash
.history
```

**Response:**

- Shows **your last 10 messages**.

---

## 📅 Updates & To-Do List

### 📅 See Recent Updates

**Command:**

```bash
.updates
```

**Response:**

- Shows **new features and improvements**.

---

### 👉 View To-Do List

**Command:**

```bash
.todo
```

**Response:**

- Lists **planned improvements** for the bot.

---

## 🔗 How the AI Works

- Uses **OpenAI** for conversation generation.
- Reads **Google Calendar** for **smart scheduling**.
- **Processes images & files** for analysis.
- Uses **sentiment analysis** to adjust tone.

---

## 💌 Example Conversations

### 📅 Scheduling Help

```bash
You: Let's meet tomorrow.
Bot: You have a meeting at 1 PM. Does 3 PM work instead?
```

### 🎭 Fun & Personality

```bash
You: Hey, what's up?
Bot: Just chilling! You’ve got a gym session later today. Feeling ready?
```

### 📆 AI Summarization

```bash
You: What’s happening this week?
Bot: Here’s what your week looks like:
📅 Meeting with John - Monday at 10 AM  
📅 Date Night - Friday at 7 PM  
📅 Gym - Saturday at 9 AM  
```

---

## 👉 Summary of Features

✅ **Casual, AI-powered responses**  
✅ **Google Calendar integration** (Charlton + Jane)  
✅ **Event creation & conflict detection**  
✅ **File processing & summarization**  
✅ **Rock-Paper-Scissors game**  
✅ **GIF search feature**  
✅ **Fact storage & retrieval**  
✅ **Chat history lookup**  
✅ **Custom to-do list & updates**

---

## 🚀 Future Improvements

- **More natural conversation memory**  
- **Better image analysis**  
- **Additional utility commands**

Let me know if you want to add or tweak anything! 🚀

