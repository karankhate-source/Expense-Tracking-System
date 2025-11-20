🚀 Expense Management System

A modern Expense Tracking System built with a FastAPI backend and a Streamlit frontend, designed for quick data entry, smooth UI, and scalable backend operations.

This project demonstrates clean architecture, API-driven design, and full-stack development using Python.

📁 Project Structure
expense-management-system/
│
├── frontend/        # Streamlit UI for interacting with the system
├── backend/         # FastAPI server with all endpoints
├── tests/           # Unit tests for frontend & backend
│
├── requirements.txt # Project dependencies
└── README.md        # Project documentation

✨ Features

📊 Add, view, and manage expenses

⚡ FastAPI-powered backend with clean and modular endpoints

🎨 Streamlit UI for a simple, interactive expense dashboard

🧪 Test suite included for backend and frontend logic

🔌 API-first design enabling integration with external apps

🗂️ Clean, scalable folder structure

🛠️ Tech Stack
Layer	Technology
Frontend	Streamlit
Backend	FastAPI, Uvicorn
Database MySql
Testing	Pytest
Language	Python 3.10+
🚀 Getting Started
1. Clone the Repository
git clone https://github.com/karankhate-source/Expense-Tracking-System.git
cd Expense-Tracking-System

2. Install Dependencies
pip install -r requirements.txt

3. Start the FastAPI Server
uvicorn backend.server:app --reload


By default, the API will be available at:

http://127.0.0.1:8000


Swagger Docs:

http://127.0.0.1:8000/docs

4. Run the Streamlit App
streamlit run frontend/app.py


The app will launch in your browser automatically.

📌 API Endpoints (Sample)
Method	Endpoint	Description
POST	/expense/add	Add a new expense
GET	/expense/all	Fetch all expenses
DELETE	/expense/{id}	Delete an expense

(Modify these examples based on your actual endpoints.)

🧪 Running Tests
pytest

📈 Future Enhancements

📦 Add persistent DB (SQLite / PostgreSQL)

📊 Add charts for monthly spending insights

🔐 Authentication system (JWT)

📱 Convert into a PWA/mobile-friendly interface

🌐 Deployment on Render / Streamlit Cloud / Railway

🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you’d like to improve.

⭐ Show Your Support

If you found this project useful, consider giving it a star ⭐ on GitHub — it helps a lot!

