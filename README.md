# **Judicial ChatBot**

This project is a Judicial ChatBot designed to simplify access to information about the Indian judiciary. The bot leverages a Python backend and a React-based frontend to deliver a user-friendly experience. Follow the instructions below to set up the project and start using it.

---

## **Table of Contents**
1. [Features](#features)  
2. [Prerequisites](#prerequisites)  
3. [Installation Guide](#installation-guide)  
4. [Usage Instructions](#usage-instructions)  
5. [License](#license)  

---

## **Features**
- AI-driven chatbot for judiciary-related queries.  
- Streamlit-based Python backend.  
- React-based frontend interface.  
- Simple PDF loading for additional data.  

---

## **Prerequisites**
Ensure you have the following installed:  
- Python (3.8 or later)  
- Node.js and npm  
- Visual Studio Code (recommended)  

---

## **Installation Guide**

### **Step 1: Create a Virtual Environment**
1. Open Visual Studio Code.  
2. Press `Ctrl + Shift + P` and select **"Select Python Interpreter"**.  
3. Choose **"Create Virtual Environment"**.  
4. Select your preferred Python version.  
5. Choose the `bot/requirements.txt` file to install dependencies.  

### **Step 2: Set Up API Key**
1. Navigate to the `bot` directory.  
2. Create a `.env` file.  
3. Add your Google API key in the format:  
   ```env
   GOOGLE_API_KEY=<your_gemini_api_key>
