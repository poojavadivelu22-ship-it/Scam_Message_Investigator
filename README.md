## Scam Message Investigator

## Live Demo
https://scammessageinvestigator-pmahydfw4u46gouekmisse.streamlit.app/

## About the Project

Scam Message Investigator is an AI-assisted cybersecurity application developed using Python and Streamlit. It helps users identify suspicious messages from SMS, WhatsApp, emails, and other platforms.

The application analyzes message content and detects possible scam patterns using rule-based detection and optional AI-based explanations.

## Features

- **Scam Detection:** Identifies possible fraudulent messages.
- **AI Explanation:** Provides additional explanations using Ollama AI.
- **URL Detection:** Checks website links for suspicious patterns.
- **Risk Score:** Calculates an estimated risk percentage.
- **Analysis History:** Stores previous analysis results during the current session.
- **Safety Tips:** Provides useful recommendations to avoid online scams.
- **Dashboard:** Displays message classification and analysis statistics.
- **Language Support:** English and Tamil message support (where supported by detection rules).

## Detection Categories

1. Bank Fraud
2. OTP Fraud
3. Job Scam
4. Lottery Scam
5. Phishing Scam
6. Payment Scam

## Technologies Used

- Python
- Streamlit
- Ollama
- Gemma 3:1B
- Pandas
- Plotly
- Regular Expressions

## Project Structure

```text
Scam-Message-Investigator/
│
├── app.py
├── requirements.txt
└── README.md
```

## Installation and Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

### Step 2: Open the Project Folder

```bash
cd Scam-Message-Investigator
```

### Step 3: Install Required Libraries

```bash
python -m pip install -r requirements.txt
```

### Step 4: Run the Application

```bash
python -m streamlit run app.py
```

The application will open in your browser at:

```text
http://localhost:8501
```

## Ollama Setup (Optional)

To enable AI-based explanations, install Ollama and download the Gemma model.

```bash
ollama pull gemma3:1b
```

Start Ollama and enable the AI Explanation option in the application.

The application can also perform rule-based detection without Ollama.

## How to Use

1. Open the Scam Message Investigator application.
2. Enter an SMS, WhatsApp message, or email.
3. Click the Analyze Message button.
4. View the scam classification and risk score.
5. Read the warning reasons and safety recommendations.
6. Use the URL Checker to check suspicious website links.
7. View analysis statistics in the Dashboard.

## Project Objective

The main objective of this project is to help users recognize possible online scams, understand warning signs, and follow safe online practices.

## Disclaimer

This application is an educational cybersecurity tool. Detection results are estimates and cannot guarantee whether a message or website is genuine or fraudulent. Always verify suspicious messages through official sources.

## Future Enhancements

- Improved Tamil language scam detection.
- Real-time scam URL reputation checking.
- Database-based analysis history.
- Email and SMS integration.
- Improved AI-based fraud detection.

