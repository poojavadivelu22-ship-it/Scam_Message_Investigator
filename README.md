# Scam Message Investigaton

### Introduction
Scam Message Investigator is an AI-powered application that helps users identify suspicious messages, emails, and job offers. It uses Artificial Intelligence to analyze the given message and detect possible scam activities.

### Features
- Analyze suspicious SMS messages.
- Check emails for possible scam activities.
- Detect fake job offers.
- Identify warning signs in messages.
- Generate AI-based investigation results.
- Provide safety recommendations.

### Technologies Used
- Python
- Streamlit
- Ollama
- Gemma 3:1B
- Requests

### Requirements
Install the required Python packages:

```bash
pip install streamlit requests
```

Install Ollama and download the Gemma model:

```bash
ollama pull gemma3:1b
```

### Project Structure

```text
Scam Message Investigator/
│
├── app.py
└── requirements.txt
```

### How to Run the Project

**Step 1:** Install the required packages.

```bash
pip install -r requirements.txt
```

**Step 2:** Download the AI model.

```bash
ollama pull gemma3:1b
```

**Step 3:** Make sure Ollama is running.

```bash
ollama run gemma3:1b
```

**Step 4:** Open another terminal and run the Streamlit application.

```bash
python -m streamlit run app.py
```

**Step 5:** Open the application in your browser.

```text
http://localhost:8501
```

### How It Works
1. Select the message type.
2. Enter the suspicious message.
3. Click the Investigate button.
4. The AI model analyzes the message.
5. View the investigation result and safety recommendations.

### Output
The application provides an AI-based analysis of the submitted message, including possible scam indicators and recommended safety actions.

### Note
This application provides an initial AI-based assessment. Its results are not a guarantee that a message or link is safe or fraudulent. Always verify suspicious messages through official sources.

### Screenshots
<img width="1282" height="756" alt="image" src="https://github.com/user-attachments/assets/70e03566-a3b9-4fa7-a3a6-c2fd3d1020f9" />
<img width="1630" height="846" alt="image" src="https://github.com/user-attachments/assets/950fe799-eead-4c58-9b27-d87949e01ccc" />



### Conclusion
Scam Message Investigator helps users understand possible online scams and encourages safe digital communication.
