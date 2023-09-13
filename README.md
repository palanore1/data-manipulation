# Data manipulation using pandas and other relevant libraries in ML

I used 3 standard and well known data sets: RacketSports, MIT-BIH and PTB. The first measures teh accelerometer and gyro vaues of a badminton player and the other 2 measure the heartbeat for different kind of hear affections.

After loading the datasets, I plotted them in order to visaulize the balance of the classes. It is simple to observe that in some cases, the number of samples in a class is significantly higher than the other classes, which may cause false predictions from the trained model.

![image](https://github.com/palanore1/data-manipulation/assets/101025098/2bec6dd0-8f70-4ec2-9c57-22f2095c8558)
Class balance for RacketSports

![image](https://github.com/palanore1/data-manipulation/assets/101025098/96b1aca3-7b26-4193-a568-df7ba869165e)
Obvious class imbalance for MIT-BIH

Next, I visualized some time series for each of the datasets, to get a better understanding of the class disttributions.
![image](https://github.com/palanore1/data-manipulation/assets/101025098/7ad6355a-eb67-47a6-9204-719bf391adb2)
Time series for Racket Sports

After this, I manually exctracted attributes, selected the relevant ones and used those to apply classic ML algorithms, such as: RFC, SVM and Grid Search.

![image](https://github.com/palanore1/data-manipulation/assets/101025098/661cc8d5-1ec3-4b40-85b9-a7019c7d9dcb)
Features extracted and applied RFC on RacketSports
