📘 IELTS Speaking Test Platform
This project was built as part of Assignment 11 and Assignment 12 of the PFSD course.

It connects a React + Vite frontend to a Flask backend, allowing users to fetch speaking test questions and submit responses.

📂 Project Structure
bash
Copy
Edit
assignment/
├── backend/                  # Flask backend
├── ielts-speaking-test/       # React frontend (Vite)
└── README.md                  # This file
🚀 Features
✅ Fetch speaking test questions dynamically from Flask backend
✅ Submit user responses to test questions via a POST API
✅ Responsive and clean UI using React and Axios
✅ Error handling and user feedback for API calls

⚙️ Technologies Used
Frontend: React, TypeScript, Axios, Bootstrap

Backend: Flask, Flask-SQLAlchemy, Flask-Migrate, SQLite

Other Libraries: flask-cors, python-dotenv, pytz

🛠️ Setup Instructions
1. Clone the repository:
bash
Copy
Edit
git clone https://github.com/yourusername/ielts-speaking-test-assignment.git
cd ielts-speaking-test-assignment
2. Backend Setup
bash
Copy
Edit
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

pip install -r requirements.txt
pip install pytz flask-cors python-dotenv

python app.py
✅ Backend will start on:
http://localhost:5000

3. Frontend Setup
Open new terminal tab:

bash
Copy
Edit
cd ielts-speaking-test
npm install
npm install axios bootstrap
npm run dev
✅ Frontend will start on:
http://localhost:5173

