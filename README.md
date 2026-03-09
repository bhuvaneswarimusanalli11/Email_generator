"""
# AI Personalized Email Generator using GPT-Neo

## Project Overview
This project is an AI-powered email generation system developed during my internship at SmartBridge. 
The system automatically generates personalized and professional emails based on user-provided event details.

The application uses the GPT-Neo language model to generate natural and meaningful email content. 
A simple web interface is built using Streamlit so users can easily enter event information and generate emails instantly.

This project demonstrates the practical application of Natural Language Processing (NLP) and Generative AI.

--------------------------------------------------

## Features
- AI-based personalized email generation
- Generates professional event invitation emails
- Simple and interactive user interface
- Built using Streamlit web framework
- Uses GPT-Neo transformer model for text generation
- Allows customization of closing notes

--------------------------------------------------

## Technologies Used
- Python
- Streamlit
- Hugging Face Transformers
- GPT-Neo (EleutherAI/gpt-neo-1.3B)
- PyTorch
- Natural Language Processing (NLP)

--------------------------------------------------

## Project Workflow

1. The user opens the Streamlit web interface.

2. The user enters event details such as:
   - Recipient Name
   - Event Name
   - Event Date
   - Event Time
   - Location
   - Special Instructions
   - Closing Note

3. The system creates a prompt using the provided details.

4. The GPT-Neo model generates a complete email based on the prompt.

5. The generated email is displayed on the screen for the user.

--------------------------------------------------

## Project Structure
```
AI_Email_Generator/
│
├── app.py                # Streamlit web application
├── email_generator.py    # Email text generation logic
├── model_loader.py       # GPT-Neo model loading
├── requirements.txt      # Project dependencies
└── README.md
```
--------------------------------------------------

## Installation

1. Clone the repository
```
git clone https://github.com/your-username/ai-email-generator.git
```
2. Navigate to the project directory
```
cd ai-email-generator
````
3. Install required dependencies
```
pip install -r requirements.txt
```
--------------------------------------------------

## Running the Application

Run the Streamlit application using the following command:
```
streamlit run app.py
```
After running the command, the application will open in your browser where you can generate emails.

--------------------------------------------------

## Example

Input:
Recipient Name: John
Event: Project Meeting
Date: 10 June 2026
Location: Conference Room

Output:
The system generates a professional email invitation automatically using GPT-Neo.

--------------------------------------------------

## Learning Outcomes

- Understanding transformer-based language models
- Implementing text generation using GPT-Neo
- Building interactive web apps using Streamlit
- Integrating AI models into real-world applications

--------------------------------------------------

## Author

Bhuvaneswari Musanalli

GitHub: https://github.com/your-username

--------------------------------------------------

## Internship

This project was completed as part of an Generative AI internship program at SmartBridge.
"""
