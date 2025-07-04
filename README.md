# Talk2Fill: Simplifying Banking Through Speech 🗣️🏦

**Talk2Fill** is a voice-based banking assistant that simplifies the process of filling out essential forms like deposit, withdrawal, and account opening slips using speech recognition technology. It is especially helpful for customers who face difficulties with reading or writing.

## 🚀 Project Overview

In traditional banking, users are required to manually fill forms for simple tasks. This can be a barrier for:
- Elderly people
- Illiterate customers
- Visually impaired individuals

**Talk2Fill** addresses these issues using the **Web Speech API** to capture voice input and automatically fill the form fields like:
- Account Holder's Name
- Account Number
- Transaction Type (Deposit/Withdrawal)
- Amount

Users can then **review**, **verify**, and **print** the filled forms.

## ✨ Features

- 🎤 Real-time voice input using Web Speech API
- 🧠 Automatic parsing and extraction of relevant information
- ✅ Form preview and user confirmation
- 🖨️ Print-ready output for submission
- 🔒 KYC-friendly and privacy-aware design

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Speech Recognition**: Web Speech API (built into modern browsers)
- **PDF Generator**: jsPDF
- **Other Tools**: DOM manipulation, basic form validation

## 🏃‍♂ *How to Run the Project*

Follow these steps to run the project locally:

### 1. *Clone the repository*

```bash
https://github.com/swaroop240/talk2fill-banking-speech.git
cd sms-spam-detection
```

### 2. *Install the Required Dependencies*
```bash
pip install -r requirements.txt
```
### 3. *Run The Project*
```bash
python app.py
