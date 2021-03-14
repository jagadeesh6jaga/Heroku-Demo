# salary prediction with Heroku-Deployment 


this is the small demo about how to deploy machine learning model in heroku .



<h3> requirements.txt </h3>

in this file you need to specify libraries  which help  to execute this model .

here i mentioned  below libraries 

Flask==1.1.1
gunicorn==19.9.0
itsdangerous==1.1.0
Jinja2==2.10.1
MarkupSafe==1.1.1
Werkzeug==0.15.5
numpy>=1.9.2
scipy>=0.15.1
scikit-learn>=0.18
matplotlib>=1.4.3
pandas>=0.19


<h3> procfile </h3>

this file contains  :  web: gunicorn app:app


this is usefull to specify which file in  heroku should execute first . 

in my case app.py so i specified first app , and second app indicates the name of the flask .


<h3> app.py</h3>

this file contains the main flask api

<h3> model.pkl</h3>

this pickle file contains the main machine learning model to predict the salary .

<h3> final result after deployment </h3>


to predict salary based on experience , test_score , interview-score, click below link :

https://salaryprediction-apijagadeesh.herokuapp.com/
