# Data manipulation using pandas and other relevant libraries in ML

I used 3 standard and well known data sets: RacketSports, MIT-BIH and PTB. The first measures teh accelerometer and gyro vaues of a badminton player and the other 2 measure the heartbeat for different kind of hear affections.

After loading the datasets, I plotted them in order to visaulize the balance of the classes. It is simple to observe that in some cases, the number of samples in a class is significantly higher than the other classes, which may cause false predictions from the trained model.

Next, I visualized some time series for each of the datasets, to get a better understanding of the class disttributions.

After this, I manually exctracted attributes, selected the relevant ones and used those to apply classic ML algorithms, such as: RFC, SVM and Grid Search.
