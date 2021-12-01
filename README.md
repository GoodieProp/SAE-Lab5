# SAE-Lab5
## How to run

First, After this, you will verify you have python3 install by doing 'python3 --version'. If you do not have it install do 'sudo apt install python3'

Next locate where your want to set up the virtual environment, then make a directory
Inside your terminal type in 'mkdir app', or whatever name you want to call it.

After that you will 'cd' into your created folder and then type in 'sudo python3 -m venv ~/filePath/app/venv'. 

Then within the same folder, git clone this repository. 'git clone https://github.com/GoodieProp/SAE-Lab5.git'

Once this is done, you have to activate your virtual environment by typing in 'source venv/bin/activate'.

You will see a (venv) to the left of your name, meaning you're inside the virtual environment.

Next, you will type in 'sudo pip install django', to install django. If you do not have pip installed do 'sudo apt install pip'.

Final step is to run the server.

You will cd in the cloned repository by typing in 'cd xgon_proj' and then run the server by typing in 'python manage.py runserver'. If you get error about django not being able to import, that might mean that django was installed on a different version of python. To fix that, you can check what python version you have by typing in 'python' into your terminal and hold tab. If you have Python 3.8 installed, do 'python3.8 manage.py runserver' and it should work. 

You should see in the terminal that it is performing system checks and it will start the development server at 'https://127.0.0.1:8000'.

After this, open your web browser, I use Firefox, and type in either '127.0.0.1:8000/hello/' or 'localhost:8000/hello'.

You should able to see the JSON response in your web browser.

All commands in case laziness kicks in:
```
python3 --version
sudo apt install pip
mkdir app
git clone https://github.com/GoodieProp/SAE-Lab5.git
sudo python3 -m venv /app/venv
source venv/bin/activate
sudo pip install django
cd xgon_prj
python manage.py runserver
or
python3.8 manage.py runserver
```

