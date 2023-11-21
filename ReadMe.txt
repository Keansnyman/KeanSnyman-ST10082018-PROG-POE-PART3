Project Name: Prog7312_POE_Part1_ST10082018_V2
=========================================================

Author: Kean Snyman - ST10082018
==========================================================

Description:
==============
The Finding Call Numbers Quiz is a Windows Forms Application designed to both entertain and educate users on the Dewey Decimal Classification (DDC) system, primarily used in libraries. This quiz game challenges users to correctly identify call numbers based on provided descriptions. Featuring engaging background music and a sleek, user-friendly interface, it offers an immersive learning experience. This quiz is a part of a three-part project series from which this is the third part

Getting Started
===============

Prerequisites
-------------
1. Windows Operating System
2. .NET Framework 4.8 or higher
3. NAudio Library
4. Newtonsoft.Json Library

Installation:
-------------
- Open the project in Visual Studio or any compatible IDE.
- Restore NuGet packages, particularly NAudio and Newtonsoft.Json.
- Build and run the project to start the quiz.

Classes For Part 3:
-------------------
- Section.cs
- Division.cs
- MainClass.cs
- FindingCallNumbersForm.cs
- DeweyDecimalData.txt

How To Play
===========

Main Menu
---------
- Upon launching the application, click on Finding Call Numbers.
- The game rules is displayed, click ok.
- The game begins immediately after the user clicks the "Start Game" button.

Gameplay
--------
1. Objective
   - Select the correct call number based on the given description. The quiz progresses through different levels, each representing a part of the Dewey Decimal System.

2. Controls
   - Use the mouse to interact with the quiz interface.
   - Select your answer from the list of options.
   - Click the "Submit" button to confirm your answer.
   - The "Pause Music" button allows for toggling the background music on/off.

3. Features
   - Timer: Each quiz session is timed, giving users 60 seconds to complete the quiz.
   - Levels: The quiz comprises three levels - Main Class, Division, and Section.
   - Audio Feedback: Different sounds are played for correct and incorrect answers.
   - Background Music: Accompanies gameplay and can be toggled.

4. Scoring
   - Points are earned for correctly completing all three levels of a question. The aim is to achieve the highest score before time runs out.

5. End of Game
   - The game concludes when the timer runs out or when the "Reset Game" button is clicked. The user's final score is displayed, and the option to restart the quiz is presented.

