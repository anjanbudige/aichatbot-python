# AI Chat Bot Python

This project demonstrates the deployment of a chatbot created using Flask and JavaScript.

## Overview

In this project, we deploy the chatbot using Flask. Two deployment options are provided:

- Deploy within Flask app with custom model training
- Serve only the Flask prediction API. The HTML and JavaScript files used can be included in any frontend application with only slight modifications and can run completely separate from the Flask App.

## Initial Setup

This repository contains the starter files.

Clone repo and create a virtual environment
```
git clone https://github.com/anjanbudige/aichatbot-python
cd aichatbot-python
python3 -m venv venv
. venv/bin/activate
```
Install dependencies

```
pip install Flask torch torchvision nltk
```

Install nltk package

```
python
>>> import nltk
>>> nltk.download('punkt')
```

Modify `intents.json` according to your model.

Run

```
(venv) python train.py
```

This will dump data.pth file. And then run
the following command to test it in the console.

```
(venv) python chat.py
```


## Anaconda Environment

1. Create New Environment
2. Download Files
   ```
   git clone https://github.com/anjanbudige/aichatbot-python
   cd aichatbot-python
   ```
3. Go to Environment (Activate)
4. Install Dependencies
   ```
   pip install Flask torch torchvision nltk flask-cors
   ```
5. Install NLKT Package
   ```
   python
   import nltk
   nltk.download('punkt')
   ```
6. Train Model
   ```
   python train.py
   ```
7. Run API
   ```
   python app.py
   ```
8. It Runs in backend you can connect your frontend applications.

---

If you have any questions, feedback, or suggestions, feel free to open an issue or contact me.


