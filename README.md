
# House Price Prediction

The project is for predicting **House Price** from Scratch to Deploment. I have built a ML model  
using Liner Regression alogorithm and Boston Hourse Price Dataset. The dataset contain 506 
instances of 14 different attributes. After creating the model, I have build a Heroku app and   
deployed the app to cloud platform so that user can easily access the app. 





## Software and Tools used
### Software And Tools Requirements

1. [Github Account](https://github.com/zianafique)
2. [HerokuAccount](https://dashboard.heroku.com/apps)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)
5. [Postman](https://www.postman.com/)
6. [Docker](https://www.docker.com/)
7. [Flask](https://flask.palletsprojects.com/en/2.2.x/)


## How to Run the script:
 
First, user needs to build a virtual envioronment in the command prompt using this command:
```bash
conda create -p venv python==3.7 -y
```
Once the Virtual envioronment has been created then, the user need to clone this repository by :
```bash
git clone "https://github.com/zianafique/house_pricing_deployment.git"
```
Then the user will find all the scripts and folders has been downloaded to their local device.  

After that the user needs to install all the dependencies of this project by this command:
```bash
pip install -r requirement.txt
```
Finally the user is ready to run the Notebook **(price_prediction.ipynb)** to train the model again  
or can run the python script **(app.py)** to view the app. 
## Final Interface Looks:

<div align="center">
  <img src="https://github.com/zianafique/house_pricing_deployment/blob/main/templates/screen1.jpg?raw=true"><br>
</div>

From the above image you can see that, **"House Price Prediction App"** requires the users to
pass values for 
different attributes, which I have got from our trained model. 
The  attributes infomration has also passed for users reference. Once the value has been given,
by clicking on 'Submit' buuton  users can get the estimate price of a specific house.

## How to Access the app:
In order to access the app and test with your values, users can move two ways:  
  	1. [Click Here](https://price-house-prediction.herokuapp.com/). This link will redirect the 
      users to the app.  
    2. Users can also use this github repo to access the app. Inside the repo, there is a **"Environment"**
      option, from there the users need to clic on **"View Deployment**
## Documentation 
- [The Documentation of the whole project](https://docs.google.com/document/d/1KJ5YFKWS7OukRwMg8_5TpUx1s05KSw81E38jwS9RqLc/edit?usp=sharing)
## Authors

- [@afiquezian](https://github.com/AfiqueAye)

