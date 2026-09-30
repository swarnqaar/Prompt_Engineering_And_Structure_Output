## how to run
1. go to hire_me_ai file --> cd hire_me_ai
2. activate environment --> .\.venv\Scripts\Activate.ps1
3. install requirements.txt if required --> pip install -r requirements.txt
4. go to backend folder --> cd .\backend\
5. reload the backend part --> uv run uvicorn main:app --reload
6. go to backend folder --> cd .\frontend\
7. Open the frontend --> Double-click index.html to open it in Chrome, Edge or Firefox.
(If you use VS Code, you can instead right-click the file and choose "Open with Live Server" (this needs the Live Server extension). Or serve it from a second terminal:) --> python -m http.server 5500  
8. Then go to http://localhost:5500/index.html.