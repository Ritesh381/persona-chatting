# Persona-Based AI Chatbot
This is the solution to the "Persona-Based AI Chatbot" Prompt Engineering assignment from Scaler Academy.

## Setup Instructions

1. **Clone the repository**

2. **Backend Setup**
   ```bash
   cd backend
   npm install
   ```
   - Copy `.env.example` to `.env`
   - Fill in your `GEMINI_API_KEY` in the `.env` file.
   - Run the server:
   ```bash
   npm run dev
   ```

3. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   npm run dev
   ```

## Features
- Switch between 3 personas: Anshuman Singh, Abhimanyu Saxena, and Kshitij Mishra.
- Each persona has a unique system prompt engineered to emulate their specific communication constraints and teaching style.
- Chat UI with built-in typing indicator, suggestion chips, and error handling.
- Integrated with the Open-Router API.

Enjoy the conversation with the incredible founders and instructors!
