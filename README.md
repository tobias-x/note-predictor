# note-predictor

Problem: A pianist is playing in an empty room. They are playing a simple 
repeating melody, with each discrete note being recorded and appended to a pandas 
dataframe containing only the note and the timestamp that the note was played. 
They are then joined by several other pianists, each playing a distinct melody, 
but with all notes and corresponding timestamps being appended to the 
same dataframe. These pianists are then joined by a class of school students, 
who each play random notes which are similarly appended to the dataframe.

Time->
______________________________________________
E|              X     X
______________________________________________
D|           X     X     X           X
______________________________________________
C|        X                 X     X     X
______________________________________________
B|     X                       X           X
______________________________________________
A|  X
______________________________________________

Goal: Given the following three scenarios, build a model that can 
generate probabilities for each note being played next, and prove that the 
results of this model are statistically significant:
- The pianist playing by himself
- The pianist playing with other pianists
- The pianist playing with the students

 

