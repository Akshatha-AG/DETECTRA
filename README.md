#  Detectra  
Multilingual Scam Detection using Explainable AI (XAI)

AI-powered platform for detecting scam SMS messages and call transcripts with explainable insights using modern NLP and deep learning techniques.

---

Problem Statement

With the rapid growth of digital communication, scam messages and fraudulent calls have increased significantly. These scams often attempt to steal sensitive information such as OTPs, bank details, or personal data.

Existing systems only classify messages as spam without providing any explanation, leading to low user trust and lack of awareness.

---

Solution

Detectra is an AI-powered system that:

- Detects scam messages using deep learning
- Supports multilingual inputs
- Provides explainable predictions using XAI (LIME)
- Improves user awareness and trust

---

Features

### 📩 Input Handling
- SMS message input
- Voice-based input (call simulation)

Multilingual Support
- English
- Hindi
- Kannada
- Tamil
- Hinglish

Scam Detection
- DistilBERT-based classification
- Scam / Genuine prediction
- Confidence score

Explainable AI (XAI)
- LIME-based explanation
- Highlights important words influencing prediction

Scam Categorization
- OTP Fraud
- Phishing
- KYC Scam
- Banking Scam
- Lottery Scam

Analytics Dashboard
- Total messages processed
- Scam vs Genuine distribution
- Pie chart visualization

Report Generation
- Downloadable report
- Includes predictions and logs

Cybersecurity Measures
- Alerts for risky messages
- Safe usage suggestions

---

Architecture

```
User Input (Text / Voice)
        ↓
Translation (Multilingual → English)
        ↓
Tokenizer (DistilBERT)
        ↓
Classification Model
        ↓
Prediction (Scam / Genuine)
        ↓
LIME Explanation
        ↓
UI Output + Analytics + Report
```

---

Technologies Used

AI / ML
- Python
- DistilBERT (Transformers)
- LIME (Explainable AI)

Data Processing
- Pandas
- NumPy

 UI
- Streamlit

Additional Libraries
- SpeechRecognition
- deep-translator
- Matplotlib

---

How to Run

1. Install dependencies
```
pip install -r requirements.txt
```

2. Run the application
```
streamlit run detectra_ai_xai_app.py
```

3. Open in browser
```
http://localhost:8501
```

---

Example Output

- Prediction: SCAM (92%)
- Important Words: OTP, urgent, verify
- Explanation: Message contains urgency and sensitive data request

---

Challenges Faced

- Handling multilingual inputs
- Integrating LIME with deep learning model
- Designing accurate scam detection
- Managing voice input and transcription
- UI design and responsiveness

---

Future Improvements

- Real-time call integration
- Mobile application deployment
- Advanced AI models
- Live scam alert system
- Enhanced fraud classification

---

Project Details

- Department: CSE-AIML & CSE-Cyber Security  
- Project ID: CI05  
- Guide: Dr. Naveen N C & Mrs. Asmathunnisa N  

---

👥 Team Members

- 1MS22CI038 – Manasavi  
- 1MS23CI404 – Monica D  
- 1MS23CY401 – Akshatha G Dhongadi  
- 1MS23CY404 – Naolin Gregory Vaz  

---

 License

This project is developed for academic and educational purposes.

---

⭐ Author

Final Year Engineering Project  
AI + Cyber Security Domain
