# About Me
I am a junior student at [Olin College of Engineering](http://www.olin.edu/) studying software engineering. I am interested in human computer interaction, robotics, cyber security, and machine learning. I have previously worked at Draper Labs in Cambridge, MA and Locus Robotics in Wilmington MA.

This is where I put the most up to date information about my projects, but you can also check out my [Resume](https://github.com/vickymmcd/portfolio/blob/master/VickyResume.doc%20(4)%20(2).pdf) and [LinkedIn Page](https://www.linkedin.com/in/victoria-mcdermott-264812124/)

# Projects

### Escape the Room Game in C, Spring 2018
#### [Souce Code](https://github.com/vickymmcd/SillyString), [Final Report](https://github.com/vickymmcd/SillyString/blob/master/reports/report.md)
As part of my software systems course in which I was learning the C programming language, I created an interactive, text based, escape the room game using the NCURSES library. The game includes 3 different question types. One is a multiple choice question with a scrolling option menu, one is a mouse click question that takes mouse click input from a certain section of the terminal window, and the last is a free response question which allows the user to type out their response to the puzzle question. A player must answer the series of 3 puzzle question correctly in order to escape the room!

### Digging Deeper: A Dirt to Table Recipe Adventure, Spring 2018
#### [Final Poster](https://github.com/vickymmcd/portfolio/blob/master/final_poster.pdf), [Broad Interaction Map](https://github.com/vickymmcd/portfolio/blob/master/Personal_int_map.pdf), [Requirements Chart](https://github.com/vickymmcd/portfolio/blob/master/Requirements_Chart_Final.pdf)
As part of an engineering design class called, User Oriented Collaborative Design, I had the opportunity to work with a team of four other students to design a product or service that could significantly better the lives of our user group, community farmers. We met with many farmers in the Massachusetts area and learned about their lives. We participated in collaborative design activities with these farmers and considered many ideas before settling on our service, Digging Deeper. The Digging Deeper service aims to aims to create more community involvement and awareness around farming through a scavenger hunt program where participants gather ingredients from around the farm and then use those ingredients to cook a farm fresh recipe at home. The goal of the service is to increase awareness about where our food comes from and to promote healthy eating in the community, something that was valued highly by many of the farmers we spoke to.

### Complex Kinect, Fall 2017
#### [Source Code](https://github.com/ComplexKinect), [Website](http://poe.olin.edu/2017/complexkinect/)
Working with a team of 4 other students, I helped to develop an integrated system which combined mechanial, electrical, and software components as a final project for my principles of engineering course. We developed an interactive art sculpture, meant to be visually appealing while engaging a larger audience. I got to work some on system integration and design, but I worked mainly on developing the software for the system. The software included a Python flask web application which allowed the user to toggle between different input methods for the movement of the flower nodes on our sculpture. The input that I spent the most time on was the motion detection input mode. For this mode, I made use of a raspberry pi camera mounted to the front of our structure to capture and detect motion in six different vertical sections of view and send messages representing the sections of movement to the arduino to move the corresponding servos. I also got the opportunity to learn about threading and processing in Python as I developed code to process video input and send messages to the arduino in parallel.

### Taxation and Evolution in Sugarscape, Fall 2017
#### [Source Code](https://github.com/ComplexityVE/SugarEvax), [Final Report](https://github.com/ComplexityVE/SugarEvax/blob/master/reports/final_report.md)
Working with 1 other student, I replicated and extended on the work done in the paper by Bäck, Vermeulen, and Eiben where they implemented systems of taxation and evolution in a sugarscape model. We used Python to simulate the survival of agents over time and generated graphs for average population and wealth over time with and without taxation. We went on to investigate the role redistributing wealth after taxation could have on the average population over time.

### Cash You, Fall 2017
#### [Source Code](https://github.com/CashYou/CashYou), [Website](http://cashyou.herokuapp.com/)
Working with 3 other students, I built the framework for a social investing web application, called Cash You, at a hackathon at Harvard called HackHarvard 2017. I worked mostly on the front end for the website, creating a flask app to get our backend Python code integrated and setting up our application to be hosted on heroku. We won the best financial hack award at the hackathon for our application.

### Line Following Robot, Fall 2017
#### [Source Code](https://github.com/Follow-That-Line/PoeLab3), [Lab Report](https://github.com/Follow-That-Line/PoeLab3/blob/master/POE_Lab_3%20(1)%20(2).pdf), [Video](https://www.youtube.com/watch?v=Zpd-80-eS0Q&feature=youtu.be)
Working with 1 other student, I created a robot which uses two IR sensors to follow a black line on the ground. I created a Serial interface in Python using the pyserial library to communicate with the Arduino and start and stop the motion of the robot. I wrote most of the control loop logic for line following in the Arduino program. I also worked on the electrical integration of the robot.

### 3D Scanner, Fall 2017
#### [Source Code](https://github.com/vickymmcd/PoeLab2), [Lab Report](https://github.com/vickymmcd/PoeLab2/blob/master/lab2_mcdermott_behrakis%20(3).pdf)
Working with 1 other student, I created a 3D scanner using a pan tilt mechanism. I created a Python script which interfaces with Serial using the pyserial library to communicate with Arduino. This script was able to set the 3D scanner into motion and graph the results of a scan from our scanner using matplotlib. I also worked on Arduino code to sweep our pan tilt mechanism over an area to be scanned.

### Hipster Networks, Fall 2017
#### [Source Code](https://github.com/ComplexityVE/HipsterNetworks), [Final Report](https://github.com/ComplexityVE/HipsterNetworks/blob/master/reports/final_report.md)
Working with 1 other student, I replicated and extended on the work done in the paper by Juul and Porter where they investigated the spread of products in a network with a variety of people classified as hipsters or conformists. We used Python to simulate the spread of ideas on a Facebook dataset. We investigated the distribution of ideas at steady state with varying starting states and parameters.

### Interactive Visualization, Spring 2017
#### [Source Code](https://github.com/vickymmcd/InteractiveProgramming), [Project Website](https://vickymmcd.github.io/InteractiveProgramming/)
Working with 1 other student, I created a program that predicts where someone is from and what their age is based on their responses to a survey. The predictions are updated after every question is answered. We visually depict these predictions using a map of the US and an age line. We used Bayesian statistics and two datasets (one about grammar and one about earthquakes) as background information to make our predictions.

### Software Design Final Project - The Super Shopper, Spring 2017
#### [Source Code](https://github.com/vickymmcd/AmazonSoftDesWarriors), [Project Website](https://vickymmcd.github.io/AmazonSoftDesWarriors), [Web Application](https://super-shoppers.herokuapp.com)
Working with a team of 3 other students, for my final project in Software Design, I created the Super Shopper web application. This application is a flask web app deployed using heroku. We used the Seasonal Auto Regressive Integrated Moving Average (SARIMA) model to predict future prices of oil and electricity based on past prices. We calculated the parameters needed for the model using seasonality and stationarity information. The program is written to be adaptable to any product if you have sufficient data on that product's price history. The idea is that we can help people to save money by purchasing products when they are cheapest in a given time window.

### Text Mining, Spring 2017
#### [Source Code](https://github.com/vickymmcd/TextMining)
I created a program that extracts the 200 tweets published by the accounts of Hillary Clinton and Donald Trump prior to the November 8, 2016 election. I then compiled a list of the most commonly used words by each candidate to determine which words were more effective in convincing the electorate to vote. I also used the sentiment analyzer to determine which candidate used more positive, negative, and neutral language in their tweets.

### Gene Finder, Spring 2017
#### [Source Code](https://github.com/vickymmcd/GeneFinder)
I wrote a script that takes long sequences of DNA as strings and returns the amino acid sequences which are most likely encoded by that DNA.

### Computational Art, Spring 2017
#### [Source Code](https://github.com/vickymmcd/ComputationalArt)
I created a program that generates a random art based on recursive computation of elementary functions.
