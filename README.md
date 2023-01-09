# Blind-Search-vs.-Heuristic-Search
An extremly simple program that solves a sliding puzzle program showcasing the difference in search step quantity between IDDFS and A*Heuristic Search. This project was done as an assignment for the class COSC 3P71 (AI).

![sliding puzzle game](https://user-images.githubusercontent.com/121593919/211230121-3644957c-e9e8-483a-98d9-2bc5ebd5ccf5.PNG)

# Background Knowledge

The sliding puzzle game is a game played with nxn tiles arranged in a square formation as shown in the image above. The goal is to get the nxn tiles in left to right, top to bottom, numerical order with the 'X' in the very last position.

# Requirements
Firstly, download the two files, "puzzles.txt" and "Search Algorithm Comparison.py", that I have posted. Take note this program was program was coded in Python 3.10.


# Instructions for Use
Once installed, assure that the two files, "puzzles.txt" and "Search Algorithm Comparison.py", are within the same folder. Next, look within "Search Algorithm Comparison.py" to find the two lines of code listed below.
![Pick One](https://user-images.githubusercontent.com/121593919/211229789-1a8c08a5-967b-4859-835f-07103541f4bd.PNG)
 By commenting one of these out, you can run the search algorithm that you want to. You can also leave both uncommented to run both algorithms in sequence.
 
 If you want a different input than the one provided in "puzzles.txt", simple change the first line in the "puzzles.txt" file to your new matrixes n value (nxn matrix), and type out a new square matrix in the same format as the old one, but with the same dimensions. No duplicate numbers are allowed and puzzles should begin at the number 1, and contain a singular 'X' square.
 
 You can now contrast the amount of steps taken by each algorithm.
 
 Now you may compile and run "Search Algorithm Comparison.py". Your results should print to the console and look something like this image below.

![print](https://user-images.githubusercontent.com/121593919/211230612-c3f9164d-1f16-4daf-b3db-4b9d671621a8.PNG)
