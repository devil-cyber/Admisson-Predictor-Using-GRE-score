## Admisson-Predictor-Using-GRE-score
#### uses Kaggle open source dataset for admisson prediction
#### Linear Regression Algorithm
#### Flask framework for the webapp
#### Google cloud for deployment

## Model
#### The model has been saved in binary file format
### saving the model to the local file system
filename = 'finalized_model.pickle'<br>
pickle.dump(reg, open(filename, 'wb'))<br>

### prediction using the saved model.
loaded_model = pickle.load(open(filename, 'rb'))<br>
prediction=loaded_model.predict(([[320,120,5,5,5,10,1]]))<br>

## Google sdk link
https://dl.google.com/dl/cloudsdk/channels/rapid/GoogleCloudSDKInstaller.exe


