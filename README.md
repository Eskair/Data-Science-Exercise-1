# Data-Science-Exercise-1
Basic Text File I\O
Introduction to Data Science I (Exercises 01) Basic Text File I/O
1. Open a file (simpleio.txt) in "write mode" and store the following strings in the file:
"This is the first line of text"
"This is the second line of text"
"End of text"
Open the file with Notepad and check the contents.
2. Write a script that collects 3 sets of data from the console (user input).
Username, age, rating (1 – 100)
(i.e. "Norman Romanotti", 35, 75)
Store the data in a python list. Then write all the data to a CSV file (users_01.csv).
 Note: You can have all the values in a line and use the .split() method to separate the words by
 commas, or you can use a set of 3 input statements, it is up to you.
3. We have received a set of files containing some data for some of our sensor locations.
(Download the files from your omnivox account and unzip them. File exer01a.zip)
• We need to read all the data from files which have a name containing a number in
the 100’s.
 Example: exer01a_101.csv (Not exer01b_203.csv)
• For every file selected we need to collect all lines except those that contain the
column Code equal to 3
 Example: 1,Montreal,20.5,10,30.5 (line to be selected)
 3,Montreal,10,20,30 (do not select this line)
• We need to make sure that the location data contains its first letter only 'capitalize'.
Transform the data if required.
• All the selected records must be written to a final output file (text file)
called: outfile.csv
• The data should include headers:
 code,area,value1,value2,value3
