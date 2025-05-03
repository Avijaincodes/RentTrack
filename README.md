Step 1. You can directly download the zip file or follow next 2 steps to clone the repo. Install latest version of git. Open the above github repository link in browser. Click on the code button as shown in the figure and copy the marked https url (shown in the figure).

Step 2. Create new folder and open git bash inside that folder write command-
git clone https://github.com/Avijaincodes/RentTrack.git

Step 3. Install latest version of python and a code editor (Pycharm or Visual Studio Code).

Step 4. Create a local host connection and click on Server Tab then select Data Import. You can see that there are two options import from self-contained file and import from dump project folder choose the option import from self-contained file and browse to the location where the database.sql file is present and click on start import which is on the bottom right of this window. Then go to the schemas tab and click on refresh to see the new database named database added. The database setup is completed.

Step 5. Open the project files in the code editor. Open main.py file and if your MySQL username and password are not root then you can replace the username and password written in main.py file with your MySQL username and password.

Step 6. Installing Packages

For Visual Studio Code do the following:

Open New Terminal

And now run the following commands in the terminal:
python -m venv env
pip install flask
$env:FLASK_APP = "main"
pip install bcrypt
pip install flask_mysqldb
pip install flask_mail
flask run
Or run requirements.txt file :
pip install -r requirements.txt
Now run the main.py file and click on the localhost link of the project or go to http://127.0.0.1:5000/ to see the project.
