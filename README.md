WellHVR is an AI-powered Ayurvedic health assistant designed to make holistic healthcare accessible, personalized, and secure. It combines ancient Ayurvedic knowledge with modern AI to provide wellness guidance, women’s health tracking, private self-notes, and conversational support through an intelligent chatbot.
Tech Stack
Backend: Python, JavaScript (Node.js / Express)


AI & LLMs: LangChain, Ollama (Mistral)


Vector Database: Qdrant (for Retrieval-Augmented Generation)


Infrastructure: Docker (containerized services), AWS (optional / future deployment)


Architecture
The user interacts with the web UI (homepage, women’s health, chatbot).


Inputs (queries, cycle data, notes) are securely sent to the backend.


Relevant Ayurvedic knowledge is retrieved from Qdrant using embeddings.


LangChain orchestrates retrieval + prompt construction.


LLM (via Ollama / Gemini) generates contextual, Ayurvedic responses.


Sensitive user data (cycle tracking, private notes) is stored securely in the database.


Responses are returned to the frontend in real time.


Key Features
AI Ayurvedic Chatbot: Provides quick, context-aware natural remedies and wellness guidance.


Women’s Health Tracking: Automatically calculates and stores cycle data using period date and average cycle length.


Private Self-Notes: Encrypted personal notes section for tracking symptoms, moods, and observations.


Secure & Ethical Design: Privacy-first handling of sensitive health information.



