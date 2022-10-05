
# Boston House Price Prediction

Provide some set of inputs to the trained machine learning model and ML model will give you the estimated price for the house in Boston.



## Table of Contents
1. Deployment
2. Software & Tools
3. Commands
4. Features
5. Developers
6. Feedback
## Deployment

```bash
  boston-house-pricing-cicd.herokuapp.com
```


## Software & Tools

1. Github Account
2. Visual Studio Code IDE
3. Heroku Account
4. Git CLI 
## Commands
1. Create a new Environment
```bash
  conda create -p venv python==3.7 -y
```

2. To Run the Environment
```bash
  conda activate venv/
```

3. Create "requirements.txt"

4. Install all dependencies from "requirements.txt" file
```bash
  pip install -r requirements.txt
```

5. Git Setup
```bash
  git config --global user.name
  git config --global user.email
  git add . 
  git commit -m "commit message" 
  git push origin main
```

6. Run flask app
```bash
  python app.py
```

7. Heroku Deployment

```bash
  Create a Procfile
    web: gunicorn app:app
```
8. Heroku deployment using Docker and Github Actions(CICD Pipeline)
```bash
  Create two folders
    .github
    .github/workflows
  Create .yaml file
    main.yaml
```

9. Github Actions
```bash 
  Go to Repo settings->Secrets ->Actions ->New secret Key ->Add all the keys
```
## Features

1. Model is trained using Linear Regression algorithm based on supervised learning.
2. Attribute Information (in order): 

        - CRIM     per capita crime rate by town
        - ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
        - INDUS    proportion of non-retail business acres per town
        - CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
        - NOX      nitric oxides concentration (parts per 10 million)
        - RM       average number of rooms per dwelling
        - AGE      proportion of owner-occupied units built prior to 1940
        - DIS      weighted distances to five Boston employment centres
        - RAD      index of accessibility to radial highways
        - TAX      full-value property-tax rate per $10,000
        - PTRATIO  pupil-teacher ratio by town
        - B        1000(Bk - 0.63)^2 where Bk is the proportion of black people by town
        - LSTAT    % lower status of the population
        - MEDV     Median value of owner-occupied homes in $1000's

## Developers

- [@aniket53](https://github.com/aniket53) 



## Feedback

Feel free to provide the feedback.

Contact Here:- akhot610@gmail.com
