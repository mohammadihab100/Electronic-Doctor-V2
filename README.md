# Hackathon
# eDoctor program



**This is a machine learning program used to predict if you have heart disease or diabetes. Then, send to the patient his results through email.**

1- You should read the comment carefully because these are some medical symbols used in the program.

2-  If you want to put data for only one person who suffers from health disease, you should go to the prediction section in heart disease and then fill all data from his row except the last cell from this row as it is already used for other purposes. (The prediction section is shown in the next data.)

```python
# Prediction

    inputData = [ 40 , 0 , 0 , 140 , 289 , 0 , 0 , 172 , 0 , 0 ]
 
    inputDataArray = np.asarray(inputData)

    inputDataReshaped = inputDataArray.reshape( 1 , -1 )

    prediction= model.predict(inputDataReshaped)

    
```

 

3-  When entering an email address, the program will only accept users registered in the Google Cloud App Project, and then the app will require access to the Gmail and calendar to send/receive emails and events.



4- Spam detector is not used in the application. It is used for another purpose which is securing Gmail.
