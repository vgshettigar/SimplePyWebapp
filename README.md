# SimplePyWebapp using Flask
This is a simple webapp using python Flask
1. Install and run the application locally in command prompt.
    - python -m pip install --upgrade pip
    - pip install flask
    - Create the file app.py
    - run python app.py
    
  ## Below are the steps to Containerize app in docker.
1. apt-get update
2. apt-get install -y python
3. apt-get install python-pip
4. pip install flask or apt install python3-flask
5. Crea/copy the application code /opt/app/py
6. Set the entry point, FLASK_APP=/opt/app.py flask run --host=0.0.0.0

