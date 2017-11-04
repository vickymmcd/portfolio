# About Me
I am a sophomore student at [Olin College of Engineering](http://www.olin.edu/) studying software engineering. I am interested in human computer interaction, cyber security, and machine learning. I have previously worked at Draper Labs in Cambridge, MA.

This is where I put the most up to date information about my software projects, but you can also check out my [Resume](#) and [LinkedIn Page](https://www.linkedin.com/in/victoria-mcdermott-264812124/)

# Projects

### Line Following Robot
#### [Source Code](https://github.com/Follow-That-Line/PoeLab3), [Lab Report](https://github.com/Follow-That-Line/PoeLab3/blob/master/POE_Lab_3%20(1)%20(2).pdf), [Video](https://www.youtube.com/watch?v=Zpd-80-eS0Q&feature=youtu.be)
Working with 1 other student, I created a robot which uses two IR sensors to follow a black line on the ground. I created a Serial interface in Python using the pyserial library to communicate with the Arduino and start and stop the motion of the robot. I wrote most of the control loop logic for line following in the Arduino program. I also worked on the electrical integration of the robot.

### 3D Scanner
#### [Source Code](https://github.com/vickymmcd/PoeLab2), [Lab Report](https://github.com/vickymmcd/PoeLab2/blob/master/lab2_mcdermott_behrakis%20(3).pdf)
Working with 1 other student, I created a 3D scanner using a pan tilt mechanism. I created a Python script which interfaces with Serial using the pyserial library to communicate with Arduino. This script was able to set the 3D scanner into motion and graph the results of a scan from our scanner using matplotlib. I also worked on Arduino code to sweep our pan tilt mechanism over an area to be scanned.

### Interactive Visualization
#### [Source Code](https://github.com/vickymmcd/InteractiveProgramming), [Project Website](https://vickymmcd.github.io/InteractiveProgramming/)
Working with 1 other student, I created a program that predicts where someone is from and what their age is based on their responses to a survey. The predictions are updated after every question is answered. We visually depict these predictions using a map of the US and an age line. We used Bayesian statistics and two datasets (one about grammar and one about earthquakes) as background information to make our predictions.

### Software Design Final Project - The Super Shopper
#### [Source Code](https://github.com/vickymmcd/AmazonSoftDesWarriors), [Project Website](https://vickymmcd.github.io/AmazonSoftDesWarriors), [Web Application](https://super-shoppers.herokuapp.com)
Working with a team of 3 other students, for my final project in Software Design, I created the Super Shopper web application. This application is a flask web app deployed using heroku. We used the Seasonal Auto Regressive Integrated Moving Average (SARIMA) model to predict future prices of oil and electricity based on past prices. We calculated the parameters needed for the model using seasonality and stationarity information. The program is written to be adaptable to any product if you have sufficient data on that product's price history. The idea is that we can help people to save money by purchasing products when they are cheapest in a given time window.

### Text Mining
#### [Source Code](https://github.com/vickymmcd/TextMining)
I created a program that extracts the 200 tweets published by the accounts of Hillary Clinton and Donald Trump prior to the November 8, 2016 election. I then compiled a list of the most commonly used words by each candidate to determine which words were more effective in convincing the electorate to vote. I also used the sentiment analyzer to determine which candidate used more positive, negative, and neutral language in their tweets.

### Gene Finder 
#### [Source Code](https://github.com/vickymmcd/GeneFinder)
I wrote a script that takes long sequences of DNA as strings and returns the amino acid sequences which are most likely encoded by that DNA.

### Computational Art
#### [Source Code](https://github.com/vickymmcd/ComputationalArt)
I created a program that generates a random art based on recursive computation of elementary functions.
