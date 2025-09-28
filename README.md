# Chatbot for Customer Service
The Customer Service Chatbot is an interactive Python application designed to simulate a real-world customer support assistant. It helps users get answers to common queries like service hours, refund policies, payment options, and order tracking.

# Customer Service Chatbot (GUI Version)

An interactive Python chatbot designed to simulate a real-world customer support assistant. The bot answers queries about service hours, refunds, payments, order tracking, and more using **rule-based keywords** and **NLP similarity matching**.

# Features
- **Graphical User Interface (GUI):** Built with `tkinter`, featuring a scrollable chat window and input field.
- **Interactive Order Tracking:** Users can provide an order ID and receive a simulated order status.
- **Rule-Based + NLP Matching:** Combines keywords and `TfidfVectorizer` similarity for accurate responses.
- **Conversation Logging:** Saves all chats with timestamps in `conversation_log.txt`.
- **Extensible:** Easily add more responses, keywords, or advanced features.

# Technologies Used
- Python 3
- `tkinter` for GUI
- `scikit-learn` (`TfidfVectorizer`, `cosine_similarity`) for NLP matching
- `re` module for text preprocessing


