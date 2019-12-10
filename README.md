## Give Me Some Credit

My attempt at solving Kaggle's [Give Me Some Credit Problem](https://kaggle.com/c/GiveMeSomeCredit)

### Goal

Predict the probability that someone will experience final distress in the next two years

### Requirements

[Docker](https://www.docker.com/)<br>
[BigML](https://bigml.com/) account<br>
[Kaggle](https://kaggle.com/) account

### Identifiants
Open the auth_sample.env file and follow the instructions

After create it, check your BigML project id on [BigML.com]() and place it in the line :<br>
 `api = BigML(project='project/5d9b851042129f40b70001b0')`


### Available scripts
In the project <code>docker</code> directory, you can run:<br>
<h3><code>docker-compose up</code></h3>
To access to he notebooks follow the instructions after:
<p>
<code>The Jupyter Notebook is running at:</code>
</p>


### Notebooks (Models)

[1. Model Ensemble with BigML](https://github.com/broques91/givemesomecredit-td/blob/master/Give_Me_Some_Credit.ipynb)

[2. Model XGBoost with Sickit-Learn]()

### Kaggle
Private Score BigML:  **0.86187**<br>
Private Score SKLearn:  **0.86680**



