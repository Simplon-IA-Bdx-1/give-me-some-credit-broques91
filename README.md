## Give Me Some Credit

My attempt at solving Kaggle's [Give Me Some Credit Problem](https://kaggle.com/c/GiveMeSomeCredit)

### Goal

Predict the probability that someone will experience final distress in the next two years

### Requirements

[Docker](https://www.docker.com/)<br>
[BigML](https://bigml.com/) account<br>
[Kaggle](https://kaggle.com/) account

To use the Kaggle API, sign up for a Kaggle account at https://www.kaggle.com. Then go to the 'Account' tab of your user profile (https://www.kaggle.com/<username>/account) and select 'Create API Token'. This will trigger the download of kaggle.json, a file containing your API credentials. Place this file in the location ~/.kaggle/kaggle.json (on Windows in the location C:\Users\<Windows-username>\.kaggle\kaggle.json, place it in your repo folder if you are on Unix based system the code will place it for you.

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

[1. Model Ensemble with BigML](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-broques91/blob/master/1_GiveMeSomeCredit_BigML.ipynb)

[2. Split with Sickit-Learn](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-broques91/blob/master/2GiveMeSomeCredit_Split_Sickit.ipynb)

[3. Model XGBoost with Sickit-Learn](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-broques91/blob/master/3_GiveMeSomeCredit_Sklearn.ipynb)

[4. Predict one input](https://github.com/Simplon-IA-Bdx-1/give-me-some-credit-broques91/blob/master/4_GiveMeSomeCredit_Predict_Input.ipynb)

### Kaggle
Private Score BigML:  **0.86187**<br>
Private Score SKLearn:  **0.86680**



