# US_Bikeshare_Data
Using Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. I write code to import the data and answer interesting questions about it by computing descriptive statistics. I also write a script that takes in raw input to create an interactive experience in the terminal to present these statistics.

The data provided by Motivate, a bike share system provider for many major cities in the United States was used to uncover bike share usage patterns. I compare the system usage between three large cities: Chicago, New York City, and Washington, DC.
<h3> check https://drive.google.com/drive/folders/1Qw1F7XjyKeH_CYVf7_B89Fhm68WqIMTg?usp=sharing for csv files</h3>

<h2>The Datasets</h2>

Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)

End Time (e.g., 2017-01-01 00:20:53)

Trip Duration (in seconds - e.g., 776)

Start Station (e.g., Broadway & Barry Ave)

End Station (e.g., Sedgwick St & North Ave)

User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns: #Birth Year #Gender

<h2>Statistics Computed</h2>

I learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. I write code to provide the following information:

#1 Popular times of travel (i.e., occurs most often in the start time)

most common month most common day of week most common hour of day #2 Popular stations and trip

most common start station most common end station most common trip from start to end (i.e., most frequent combination of start station and end station) #3 Trip duration

total travel time average travel time #4 User info

counts of each user type counts of each gender (only available for NYC and Chicago) earliest, most recent, most common year of birth (only available for NYC and Chicago)

<h2>An Interactive Experience</h2>

The script takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions on the previous page will change! There are four questions that will change the answers:

Would you like to see data for Chicago, New York, or Washington?

Would you like to filter the data by month, day, or not at all?

(If they chose month) Which month - January, February, March, April, May, or June?

(If they chose day) Which day - Monday, Tuesday, Wednesday, Thursday, Friday, Saturday, or Sunday?

The answers to the questions above will determine the city and timeframe on which data analysis will be done. After filtering the dataset, users will see the statistical result of the data, and choose to start again or exit.
