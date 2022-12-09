# Bootstrap implementation

I used bootstrap to implement a drop down navigation bar but I also changed it substantially.

# chart.js

I imported a horizontal bar chart from chart.js

# Background

My name is Antonio D’Amico and I am a Yale third year phd student in film and media studies and Italian studies. My final project is a website displaying visualisations of a dataset I created for cpsc110 using python, pandas, matplotlib, and seaborn. I used a csv file I wrote myself by collecting data about the authors and film directors comprising the Italian studies reading list which students in the department are examined on in their third year, creating 172 rows and several columns such as the year in which a particular book or film was published and the age of the author at the time of publishing to find possible correlations between these various factors and build a linear model predicting the author’s ‘identity’ via scikit-learn. 

# How to

The website has three pages. The home page offers some background information. The model page displays the code I created to build the predictive model alongside visualisations of this model. This reveals the accuracy of the model by showing the predicted results alongside the actual results (after the data is split into train data (0.8) and test data (0.2)) and numerical measurements of the mean squared error. The third and final page is where I implemented an interactive map which I created specifically for CS50.

I used the knowledge I gained in the class to create an interactive map mapping the authors in the canon on a map of Italy using javascript, css, and html. This is where I spent most of my efforts adding javascript functions and making sure that the icons on the map wouldn't change their position when the size of the webpage changes through a mix of relative and absolute positions in the css stylesheet. The map I created is responsive and features a series of buttons (i.e. icons) which change shape when the user hovers over them. When the user clicks on the icons the website  sends them across different areas of the static html page (via javascript OnClick functions) to get more information about a specific author and view a barplot displaying the number of times the words these authors use most frequently are repeated in their work - which I made by creating various dictionaries in python. Moreover, I included quantitative measurements of these texts by applying the algorithm we used for readability to calculate the Coleman-Liau index of some of these texts. I also included three buttons on the left side of the map which send the user to different graph visualizations displaying the year of publising in relation to the age of the author and the gender gap between male and female authors.

Lastly, I used bootstrap to implement a drop down navigation bar to allow users to switch between the three html pages but I also changed it substantially (opacity, background image, etc.). I also imported a horizontal bar chart from chart.js which shows the number of words in a text in a more interactive manner.
