# Requirements
##  Introduction
A Quiz is a form of Game or Mind Sport in which Players Attempt to Answer Questions Correctly about a certain or Variety of Subjects . Quiz can be used as a Brief Assessment in Education and similar fields to Measure Growth in Knowledge , Abilities or Skills . They can also be Televised for Entertainment Purposes often in a Game Show Format.

## Research
![](https://viralsolutions.net/wp-content/uploads/2019/06/shutterstock_749036344.jpg)


## Features 

- Participants Can Start the Quiz by Giving their Name.
- Its an MCQ Type Quiz.
- No Time for every question.
- Its Provide Report of Questions and Answers.
- Winner gets the rewards.

## SWOT Analysis

**Strength** 
It is Easy to Use and It is User Friendly.
**Weekness**
Only Two Rounds can be Played.
**Opportunities**
You Can Set a High Score and You can Challenge Your Friends.
**Threats**
There is No Time Limit.


## 4W's and 1'H

# Who
Anyone can take the Quiz and Enjoy the Quiz.
# What
The Project Main Aim is tha Anyone Can Gain Knowledge in this Quiz.
# When
Students with Basic C Program Knowledge Can Participate because the Quiz is based on C Language.
# Why
The Project is for Students to Get More Knowledge on C.
# How
The user can take the Quiz by Entering the Name.

## High Level Requirements

| HLR_ID | 	Description | Status |
| ------ | ------ | ------ |
| HLR_1 | Entering the Quiz | IMPLEMENTED |
|  HLR_2 | Participates in Quiz | IMPLEMENTED |

## Low Level Requirements

| HLR_ID |Description | Status |
| ------ | ------ | ------ |
| LLR_1_HLR_1 | Participants give Y to enter N to exit in char type | IMPLEMENTED |
|LLR_2_HLR_1 |	Show "Give proper response", when give other than Y (or) N| IMPLEMENTED |	
|LLR_3_HLR_1 |	Continue quiz if Y given , exit when N is given| IMPLEMENTED |
|LLR_1_HLR_2 |	Show preview of quiz to the participants| IMPLEMENTED |
|LLR_2_HLR_2 |	Enter name to participates in quiz in char string type| IMPLEMENTED |
|LLR_3_HLR_2 |	Provide question with options by entering into new functions question1| IMPLEMENTED |
|LLR_4_HLR_2 |	Participares have to choice one choice in th given choices| IMPLEMENTED |
|LLR_5_HLR_2 |	Show "Give proper response", when give other than given choices| IMPLEMENTED |



# Design
##  High Level Design
![High Level Design](https://user-images.githubusercontent.com/94219350/143287462-ea81058c-b50d-4446-9da6-f995019bf532.jpg)
##  Low Level Design
![Low Level Design](https://user-images.githubusercontent.com/94219350/143287780-cbdd2dd1-efe9-465b-953d-74628103c6ce.jpg)



# Test Plan

## High Level Test Plan

| ID | 	Description |Expected I/P |	Expected O/P |	Actual O/P  |	Type of Test Status |
| ------ | ------ | ------ | ------ | ------ | ------ |
| HP01 | User Interface | Character Y| Enter the answer | Pass | Requirement |
## Low Level Test Plan

| ID | 	Description |Expected I/P |	Expected O/P |	Actual O/P  |	Type of Test Status |
| ------ | ------ | ------ | ------ | ------ | ------ |
| HP01 | User Interface | Character Y| Enter the answer | Pass | Requirement |
|LP02|	User has an Option to Exit |	Character N |	Exits|	Pass|	Requirement
|LP03|	User can View the Score |	Character Y|	Opens results|	Pass	|Requirement

# Manual
## Setup to run Project
- An Integrated Development Environment (Suggested Visual Studio Code).
- GCC Compiler to Compile the Project.
- "make" to Run the Makefile Smoothly.

## Steps To run Project

1. First Clone the Repository from the Github.
2. Open the Repository in an IDE (Suggested Visual Studio Code).
3. The Next Step is to Build the Project with the Help of Make Command :-
   - make all
4. Next Step is to Run the Project with Help of Make Command :-
   - make run
5. If you want to Run the Test Cases then Run the Following Command :-
   - make test
6. Clean All Executable Files by the Following Command :-
   - make clean

