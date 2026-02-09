# Newton 🍎

**Local AI Agent with Semantic Memory**

Newton is your personal AI assistant that runs on your computer. It manages your files, automates tasks, and actually remembers what you tell it - not just for one conversation, but across all your sessions.

---

## What Newton Does

**Manages Your Files**
- Organizes directories and finds files instantly
- Creates, reads, edits, and moves files through conversation
- Lists directory contents and checks file properties
- Handles all file operations without touching your mouse

**Remembers Everything**
- Stores facts you tell it (your preferences, project names, important info)
- Searches through past conversations semantically - just ask "what did I mention about X?"
- Builds a knowledge base from your interactions over time
- Recalls context from weeks ago when you need it

**Automates Your Work**
- Executes multi-step tasks through simple requests
- Runs terminal commands (with your approval for safety)
- Chains operations together - "organize these files AND create a summary"
- Handles repetitive tasks so you don't have to

**Stays Private**
- Everything runs on your local machine
- Your files never leave your computer
- Conversations stored locally, not in the cloud
- You own all your data

---

## Setup

**1. Get Python 3.8+** (if you don't have it already)

**2. Download Newton**
```bash
git clone https://github.com/yourusername/Newton.git
cd Newton
```

**3. Install**
```bash
pip install -r requirements.txt
```

**4. Add your API key**
```bash
# Windows PowerShell
$env:GROQ_API_KEY="your-key-here"

# Mac/Linux
export GROQ_API_KEY="your-key-here"
```

**5. Run**
```bash
python newton.py
```

---

## Example Conversations

**"Create a folder called 'Projects' and list everything in my current directory"**  
→ Newton creates the folder and shows you all your files

**"Remember that I prefer Python for scripting tasks"**  
→ Newton stores this fact for future reference

**"What did we talk about regarding my project last week?"**  
→ Newton searches its memory and recalls the relevant details

**"Move all my .txt files into a 'Documents' folder"**  
→ Newton organizes your files automatically

**"Run 'git status' and tell me what it says"**  
→ Newton executes the command and shows you the output

---

## Why Use Newton?

**It actually remembers** - Unlike ChatGPT, Newton recalls your past conversations  
**It's your machine** - All your data stays local and private  
**It takes action** - Doesn't just advise, it does the work  
**It learns you** - Builds a knowledge base about your preferences over time

---

## Project Structure

```
Newton/
├── agent/
│   └── agent.py          # Core agent logic and tool calling
│   └── tools.py          # All tool implementations
│   └── tools.json        # Tool definitions
├── configuration/
│   ├── AGENT.md          # System prompt
│   ├── config.json       # Model configuration
├── memory/
│   ├── memory.json       # Key-value memory storage
│   ├── vector_memory.json
│   └── vector_embeddings.json
├── newton.py             # Main entry point
└── requirements.txt      # Dependencies
└── README.md             # This file 😁

```

---

💼 [Check out my LinkedIn](https://www.linkedin.com/in/tawfic-kobtan) for more projects and updates!

