# MonsieurCan
Chatbot NLP FLASK PYTORCH

This gives 2 deployment options:
- Deploy within Flask app with jinja2 template
- Serve only the Flask prediction API. The used html and javascript files can be included in any Frontend application (with only a slight modification) and can run completely separate from the Flask App then.

#Installation
flask
pytorch
nltk.download('punkt')
numpy


## Initial Setup:

$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```
#Utilisation
Now for deployment follow my tutorial to implement `app.py` and `app.js`.


## Credits:
This repo was used for the frontend code:
https://github.com/hitchcliff/front-end-chatjs

backEnd
(https://github.com/python-engineer/pytorch-chatbot)

Tuto
[![Alt text](https://img.youtube.com/vi/a37BL0stIuM/hqdefault.jpg)](https://youtu.be/a37BL0stIuM)  
[https://youtu.be/a37BL0stIuM](https://youtu.be/a37BL0stIuM)

Documentation
https://github.com/hitchcliff/front-end-chatjs
https://github.com/python-engineer/chatbot-deployment.git


