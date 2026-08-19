# flask_pract

# Cloned the Repository
git clone https://github.com/Subash023/flask_pract.git
cd flask_pract

# Created and activated the Virtual Environment
#windows
venv\Scripts\activate

# Installed Dependencies
pip install -r requirements.txt

requirements.txt (added)
Flask
Flask-PyMongo
python-dotenv
pymongo
certifi
pytest
pylint
bandit
black
Werkzeug

# Configure=d environment variables for MongoDB RUI
MONGO_URI=mongodb+srv://subash023_db_user:<db_password>@cluster01.sa9plpn.mongodb.net/

# Run the app
python app.py

# Opened Browser at 
http:127.0.0.1:5000
http:192.168.1.5:5000

project/
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── add_student.html
│   ├── update_student.html
│
├── app.py
├── requirements.txt
└── .env

# Screenshots
<img width="940" height="312" alt="image" src="https://github.com/user-attachments/assets/c81b34ae-83a9-4d14-bec5-db9f5a72943c" />

<img width="940" height="344" alt="image" src="https://github.com/user-attachments/assets/60efd68c-0fde-473d-b487-1dbed3abc43e" />


