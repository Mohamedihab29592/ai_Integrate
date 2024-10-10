# AI_Integrate

AI integrate with flutter app .

## Getting Started

CLone the repo and Local host the Ai Model by following these Instrcutions:

1-Run these commands in the terminal

pip install Flask

python3 -m venv venv

source venv/bin/activate  // for MAC
source venv/Scripts/activate.  // for Windows

python3 -m pip install numpy.

pip install scikit-learn.

python app.py  // to host the AI model and access it through your local host on port 5001.

2- check if your file sucess host success or not by try this IP ('http://127.0.0.1:5001') in your browser.

3- Send your list to the model using POST method use this IP : ('http://10.0.2.2:5001/predict') in your flutter app.
