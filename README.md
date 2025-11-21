# Discord Message Automation GUI Tool

A Python-based graphical interface for experimenting with Discord bot messaging, webhook testing, and GUI development using Tkinter.  
This project is intended **for educational purposes only**, such as:

- Learning how Discord bots send direct messages  
- Testing Discord webhooks  
- Exploring Tkinter-based GUI applications  
- Understanding threading + asyncio interaction in Python  

⚠️ **Important Notice**  
This project must **NOT** be used to spam, harass, or automate unwanted messages.  
Sending unsolicited or bulk automated messages violates Discord’s Terms of Service and can result in account termination. Use responsibly.

---

## 🚀 Features

### ✔ Tkinter-Based GUI  
A full graphical interface with:
- Main menu  
- Bot message tester  
- Webhook tester  
- Input fields for settings  
- Start/stop buttons  
- Status display  

### ✔ Discord Bot Direct Message Testing  
Allows experimenting with:
- Logging in a bot  
- Sending controlled, rate-limited messages  
- Testing message delivery to a specific user ID  

### ✔ Webhook Message Testing  
Send messages to a webhook (for personal servers/testing only).

### ✔ Multi-Threaded Execution  
The app uses Python threading to keep the GUI responsive while running asyncio Discord tasks.

---

## 📌 Requirements

- Python 3.9+
- discord.py  
- requests  
- tkinter (built-in for Windows/macOS)

Install dependencies:

```
pip install discord.py requests
```

---

## ▶️ Running the Application

```
python main.py
```

This will open the main GUI window.

---

## 🔧 Project Structure

```
├── main.py          # Entire GUI + logic
└── README.md
```

---

## ⚠ Disclaimer

This project is provided strictly for:

- Learning Python GUI development  
- Understanding how bots interact with Discord APIs  
- Testing webhooks you own  
- Developing your own bot tools  

Do **NOT** use this tool for:

- Spamming  
- Harassment  
- Unauthorized automation  
- Violating rate limits  
- Anything against Discord ToS  

The developer is **not responsible** for misuse.
