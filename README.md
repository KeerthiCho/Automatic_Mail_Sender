# Automatic_Mail_Sender

# Automatic Email Sender (Gmail)

A simple Python script to send automated welcome emails using **SMTP**.  
This script takes a user’s name and email, then sends them a personalized welcome message.

---

##  Features
- Sends a custom welcome email
- Uses Gmail’s SMTP server
- Takes name and email input directly from the terminal

---

##  Requirements
- Python 3.x
- A Gmail account
- Gmail App Password (for security — normal account password will not work)

---

##  Setup
1. **Enable Gmail App Passwords**
   - Go to your Google Account → Security → Turn on **2-Step Verification**.
   - Generate an **App Password** (choose "Mail" and your device).
   - Copy the 16-character password.

2. **Edit the Script**
   - Replace `"Your Gmail Account"` with your Gmail address.
   - Replace `"Your App Password"` with the app password you generated.
   - Replace `'&&&&&&&&&&&'` with your Gmail address.

Example:
```python
s.login("myemail@gmail.com", "abcd efgh ijkl mnop")
s.sendmail('myemail@gmail.com', email, message)
