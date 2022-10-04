### Boston-House-Pricing
Under Construction :)

### Software & Tools Required 
1. [Github Account](https://github.com)
2. [VS Code IDE](https://code.visualstudio.com/)
3. [Heroku Account](https://heroku.com)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new Environment

...
conda create -p venv python==3.7 -y
... 

To Run the Environment

...
conda activate venv/
...

Create "requirements.txt"

...
pip install -r requirements.txt
...

Run the following Git Commands for Git Setup:-

...
git config --global user.name
git config --global user.email
...

To commit the code to Github:-

...
git add .
git commit -m "v0.1"
git push origin main
...

To run the Flask app:-

...
python app.py
...

Heroku Deployment:-
1. Create a Procfile: web: gunicorn app:app
2. Go to Heroku app create new app and deploy using Github.

Heroku deployment using Docker and Github Actions(CICD Pipeline):-
1. Create Dockerfile
2. Create two folders .github/workflows and inside it create main.yaml
3. Go Repo settings->Secrets ->Actions ->New secret Key ->Add all the keys