java c ITP4206 Proprietary Mobile Application Development
Individual Assignment 2023-24 (20% of overall marks)
Objective: 
By completing the assignment, students can
• be familiar the basic features of the Swift programming language.
• practice through the steps to develop iOS app using the Xcode SDK.
Overall Task
• You are required to create an App to Pixel Editor.
• You don't need to make a 100% replicate of the example apps.
• You can choose either UIKit or SwiftUI to complete the tasks.
• Complete the tasks as many as you can.
Task 1- The Basic Task
Create a dartboard contains 256 cells, in a 16 by 16 grid. It is allowed to use 
a single view for the app and is suggested as shown on right hand side.
1. The app start with an empty art board. 
2. There are at least seven color available for selection. (Hints, user number 
to indicate color: 0 - red, 1 - yellow, 2 - green and .... or use hex code to 
indicate color) 
3. There are at least two tools - a draw tool and an eraser tool. 
4. In draw tool mode, when the user taps on each pixel, a corresponding 
color is set and displayed. In eraser tool mode, when the user taps on each 
pixel, a corresponding color is set and displayed.
The Constraints: 
• It is suggested to use array (Array) to store the values of a pixel, otherwise many variables are 
required to store the input data and the computation logic will be complicated. 
• A separate class is required in the project to perform the pixel drawing logic after the each pixel / 
button is pressed.
• Good coding standard is required – appropriate comments, error handling, well-structured coding 
and good naming convention.
 
Reference:
 Task 2 - Fill Tool
Add an additional tool "Fill Tool". Use the 4 directions ﬂﬂood ﬁﬁll algorithm to implement ﬁﬁlling 
of pixels.
Pseudo code of a ﬂﬂood-ﬁﬁll algorithm. 
Reference: 
https://en.wikipedia.org/wiki/Flood_ﬁﬁll
 
Task 3 - Undo / Redo functions
For each action, the app will store the data of the canvas (the array). 
• When the user press undo, the canvas will show the last committed canvas. 
• When the user press redo (after performing an undo), the canvas will show the next committed 
canvas. • When the user press undo and then draw on the canvas, all redo record will be replaced by the 
drawing. 
• No matter press the undo / redo, there will be no action taken if there is no more data for undo / redo.
• Tips: You can choose to just use an array or the iOS's UndoManager to manage the undo/redo. 
Task 4 - Data Persistence
• User can save the art board and load the art board for further editing. (By using UserDefault, JSON, 
CoreData or whatever solution you can think of.)
• If you can complete the following task, more marks will be awarded:
• Save multiple ﬁﬁle, and you can choose to load which ﬁﬁle to edit.
• Export and save the image to iOS's album. 
Flood-fill (node): 
 1. Set Q to the empty queue or stack. 
 2. Add node to the end of Q. 
 3. While Q is not empty: 
 4. Set n equal to the first element of Q. 
 5. Remove first element from Q. 
 6. If n is Inside: 
 Set the n 
 Add the node to the west of n to the end of Q. 
 Add the node to the east of n to the end of Q. 
 Add the node to the north of n to the end of Q. 
 Add the node to the south of n to the end of Q. 
 7. Continue looping until Q is exhausted. 
 8. Return.Marking Scheme (Full marks – 100) 
 
Remarks: Poor coding style (e.g. no suitable comments for methods and variables, poor indentation, and 
etc.) in the source codes will cause a maximum of 10 marks deduction.
 
Submission
• Hand in via moodle.
• Due date and time for submission: 21st December 2024 (Saturday) before 23:59pm.
 
Demonstration
• Submit a video demonstration to Moodle.
 
For Challenger 
You can choose to take the challenge to add even more extra feature on your app. 
• Art board with frame options and able to preview the art board animation.
• Export the animated art board in GIF animation.
Challengers who can complete one or more task will get the priority to choose the time slot for ITP4206 
project presentation and FYP interim presentation. :) 
• Basic Tasks 55 marks
• Fill Tool 10 marks
• Undo only / Undo and Redo 5 marks / 10 marks
• Data Persistence 5 marks (+5 marks for each extra features)
• Good Looking User Interface 10 marks

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
