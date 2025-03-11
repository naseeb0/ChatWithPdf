## Setup ENV

1. Go to project folder and run this command

`python -m venv env`

1. Yesle env File create gardincha. You need to activate this everytime when using the application as only that is required is installed seperately in this environment.
2. To activate run this command
3. `env/Scripts/activate`
4. Aaba green color of (env) bhanera dekhayucha terminal ma that means our environment is activateed
5. Now run this command
6. `pip install -r requirements.txt`
   This command will install all the libraries in requirements.txt file
7. Now create a new file called `.env` and paste this line
   `GOOGLE_API_KEY="AIzaSyC6UUX-GG64qixY0WF9Md6GDrKAow6qoQA"`
8. After this aaba sabai setup bhayo just run the command below
   `streamlit run chatpdf1.py`