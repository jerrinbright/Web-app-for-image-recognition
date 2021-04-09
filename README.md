# WEB-APP-FOR-IMAGE-RECOGNITION

Object recognition is done using ResNet50 pre-trained network. We custom trained over the REsNet50 model for recognition of automobile components (Oil filter, Screw, etc.). Then deployed it using FLASK along with HTML, CSS and JS framework into web. <br><br>
The web app can also be deployed in a server using Gunicorn Heroku (for free). <br>
<h2>INSTALLATION</h2>
Some of the basic requirements include Keras, numpy, tensorflow, flask and pillow. For deploying in server, libraries including gunicorn has to be installed. 

```sh
pip install -r requirements.txt
```
<h2>HOW TO RUN IN LOCAL?</h2>
To run the flask web app in local, run the main python script in terminal (app.py).

```sh
python app.py
```
```sh
Then type http://localhost:5000 in browser. 
```
