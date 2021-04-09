# WEB-APP-FOR-IMAGE-RECOGNITION

Object recognition is done using ResNet50 pre-trained network. We custom trained over the REsNet50 model for recognition of automobile components (Oil filter, Screw, etc.). Then deployed it using FLASK along with HTML, CSS and JS framework into web. <br><br>
The web app can also be deployed in a server using Gunicorn Heroku (for free). <br>
<h2>INSTALLATION</h2>
Some of the basic requirements include Keras, numpy, tensorflow, flask and pillow. For deploying in server, libraries including gunicorn has to be installed. <br><br>

```sh
pip install -r requirements.txt
```
<h2>HOW TO RUN IN LOCAL?</h2>
To run the flask web app in local, run the main python script in terminal (app.py).<br><br>

```sh
python app.py
```
```sh
Then type http://localhost:5000 in browser. 
```
<h2>HOW TO RUN VIA HEROKU?</h2>
First, we will have to install heroku. <br><br>
For Ubuntu: <br>

```sh
sudo snap install --classic heroku
```
For MacOS:

```sh
brew tap heroku/brew && brew install heroku
```
For Windows:<br><br>
Click this link: https://cli-assets.heroku.com/heroku-x64.exe <br><br>

Go to the directory/ repository. Then follow the steps below:
```sh
git init
```
```sh
git add .
```
```sh
git commit -m "My first commit"
```
```sh
heroku create
```
```sh
git remote rename heroku heroku-staging
```
```sh
git push heroku master
```

<h2>THE END!!</h2>
