<h1>IN PROGRESS NOT COMPLETED TO DO need to modify the inference to put the latest prediction as the next pm2.5</h1>
<p>Just an experiment to use LSTM for time series data. I used the UCI's pm2.5 dataset (Beijing polution). This model uses 23 previous measuresments of the polutions and their coresponding features to predict the next one. </p>
<p>Random search was performed to select the hyper-parameters, number of hidden units, keep_prob for drop out, and time steps for LSTM. model was saved at epoch 150, 180 ,and 200 checkpoints.</p>
<p>Following is a graph for predicted and actual:</p>
<img src="images/Beijing model.png"/>








  

