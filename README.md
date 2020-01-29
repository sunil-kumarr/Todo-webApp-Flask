# Todo-webApp-Flask
A flask demo app for leraning purpose only

## Setup
* Install python3 or python2 : Ubuntu 18 </br>
  ` sudo apt update ` </br>
  ` sudo apt-get install python3 `
* Install python3-pip </br>
  ` sudo apt-get install python3-pip `
* Install virtualenv for python2 (python3 have venv) </br>
  ` pip install virtualenv `

## Virtual Enivronment
* Create python virtual envirnoment to contain project dependencies only </br>
  ` python3 -m venv flask_Vir_Env `
* Now run the requirements.txt to install all flask dependencies </br>
  ` flask_Vir_Env/bin/pip install -r requirements.txt `
   </br> **OR** </br>
  ` pip install flask `

 **Congrats 😍😎 you are all done**

 ## Running Flask App </br>
 * ` export FLASK_APP = app.py ` </br>
 * ` flask run `                  </br>
 **Running on http://127.0.0.1:5000/**

 ## Depoly on heroku </br>
  Read this by heroku.com to deploy on heroku for free of cost: </br>
  https://devcenter.heroku.com/articles/getting-started-with-python

 </br> Resource : </br>
 https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask </br>
 https://flask.palletsprojects.com/en/1.1.x/quickstart/
