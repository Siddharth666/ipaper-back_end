Create a virtual environment (venv)
python -m venv venv

To activate venv
.\venv\Scripts\activate

To install all dependencies
pip install -r requirements.txt

To start Project locally
uvicorn main:app --reload

APIs
1. http://127.0.0.1:8000/upload

2. http://127.0.0.1:8000/fetch_papers
   http://127.0.0.1:8000/fetch_paper/{file_id}


Notes: 
Make sure to make 'Key' as 'file' (In postman/swagger as well as in react codebase)
Make sure to add your front-end domain in CORS origin in Main.py
Add mongo url in database.py

Upload
![image](https://github.com/user-attachments/assets/64f5d889-e9c6-4f9c-b2d4-f4b72e77f3e2)


Get paper
![image](https://github.com/user-attachments/assets/a6b214a1-93fa-4def-b057-67206c690dbf)


