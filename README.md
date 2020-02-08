# Fake Face Detector
`
The goal of the detector is to distinguish real faces from generated ones. For this purpose thousands of photos of people (https://github.com/NVlabs/ffhq-dataset) and thousands of pictures of "generated" people (https://futurism.com/incredibly-realistic-faces-generated-neural-network) were used.   The detector was trained with the library FastAI and the technique Transfer Learning. Accuracy was surprisingly good, with over 90% on test data.  Further action in the area of Explainable AI is needed to verify that the model is robust.
` 


## Login
<p align="center"><img src="https://raw.githubusercontent.com/ManuFU/fake-faces--/master/login.png" width="100%"><p>
- Login in with Username: admin Password: admin
<br><br>

## Forward to payment option
<p align="center"><img src="https://raw.githubusercontent.com/ManuFU/fake-faces--/master/payWithCard.png" width="100%"><p>
- Click on "Pay with Card"
  <br><br>
  
## Payment (Stripe)
<p align="center"><img src="https://raw.githubusercontent.com/ManuFU/fake-faces--/master/stripePaymentData.png"><p>
- Fill the boxes<br>
- Use the credit card number 4242424242424242
  <br><br>
  
## Prediction / Inference
<p align="center"><img src="https://raw.githubusercontent.com/ManuFU/fake-faces--/master/uploadPic.png" width="100%"><p>
- Upload a photo with a face on it
- Click on "Predict"
<br><br>


## Setup

- Clone or download repo
- Insert your Stripe API key in app.py
- Deploy at render.com or somewhere else
<br><br>

## Boilerplate
``` 
git clone https://github.com/anfederico/Flaskex
cd Flaskex
pip install -r requirements.txt
python app.py
```
<br><br>
<p align="center"><img src="https://raw.githubusercontent.com/anfederico/Flaskex/master/media/flaskex-demo.png" width="100%"><p>
  
## Features
- Encrypted user authorizaton
- Database initialization
- New user signup
- User login/logout
- User settings
- Modern user interface
- Limited custom css/js
- Easily customizable


<br><br>
  



