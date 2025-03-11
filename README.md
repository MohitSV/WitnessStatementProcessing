# 👥 Witness Statement Processing System

## 📋 Overview
This system processes witness statements using Natural Language Processing (NLP) and Large Language Models (LLM) to extract, analyze, and identify critical information from witness testimonies. The system employs Named Entity Recognition (NER) and dynamic question-answering to build comprehensive case information.

## ⭐ Features
- 🔍 Advanced Named Entity Recognition (NER) for extracting:
  - 👤 Names of individuals
  - 📅 Dates and times
  - 🏢 Organizations
  - 📍 Addresses
  - 🚗 Vehicles
  - 📝 Other relevant entities

- 💭 Dynamic Question-Answering System:
  - ❓ Processes initial crime-related questions
  - 🤔 Generates and answers follow-up questions based on context
  - 🔍 Identifies information gaps

- 🕸️ Graph-Based Information Structure:
  - 📊 Visualizes relationships between extracted entities
  - ⚠️ Highlights missing information
  - 🔗 Maps connections between different statements

- 💾 MongoDB Integration:
  - 📥 Stores processed statements
  - 🔄 Maintains entity relationships
  - 💡 Preserves question-answer pairs

## 🛠️ Setup and Installation

### 🔧 Backend Setup (Flask)
1. Navigate to the backend directory:
   ```
   cd WitnessStatementProcessing/QandA
   ```
2. Start the Flask server:
   ```
   flask run
   ```

### 🎨 Frontend Setup (React)
1. Open a new terminal
2. Navigate to the frontend directory:
   ```
   cd WitnessStatementProcessing/FrontEnd/reactapp
   ```
3. Install dependencies:
   ```
   npm install --legacy-peer-deps
   ```
4. Start the React application:
   ```
   npm start
   ```

## 💻 System Requirements
- 🐍 Python 3.x
- ⚛️ Node.js
- 🗄️ MongoDB
- 📦 Required Python packages (install via pip)
- 📦 Required Node packages (installed via npm)

## 📱 Usage
1. 📝 Input witness statements through the web interface
2. 🤖 System automatically processes statements using NER
3. ❓ Initial questions are generated and answered
4. 🔄 Follow-up questions are dynamically created based on context
5. 📊 Information is stored and visualized in graph structure
6. 💾 Results are saved to MongoDB for future reference

## ⚠️ Note
Ensure MongoDB is running before starting the application. The system requires both backend and frontend services to be running simultaneously for full functionality.
