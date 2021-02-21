# CS-210

#Summarize the project and what problem it was solving.
For this project, I had to create a clock that displayed the time in both standard and UTC format. It had to allow the user to update the time by selecting from menu options to add either 1 hour, minute, or second to the displayed time and update both clocks accordingly.

#What did you do particularly well?
I was able to get the clock to perform as expected and increment the times as well as display correctly. I also found a way to add a leading zero to single digit times.

#Where could you enhance your code? How would these improvements make your code more efficient, secure, and so on?
An enhancement that would make this project even better would be to allow the program to access the actual current time from the machince, then allow the user to change the time completely, instead of having to incrementally advance the time by 1. Another enhancement could be to allow the user to decrease the time displayed as well, in case they incremented too far ahead.

#Did you find writing any piece of this code challenging, and how did you overcome this? What tools and/or resources are you adding to your support network?
My biggest challenge on this project was adding the leading zero, for which I researched C++ functions to find one that did the job. Another challenge was making sure that after 12:00, the time in standard format went to 1:00, and in UTC format that midnight was displayed as 0:00 instead of 24:00.

#What skills from this project will be particularly transferable to other projects and/or course work?
The conditional statements that I had to write as well as the loops, will most likely be useful in practically anything I write in the future.

#How did you make this program maintainable, readable, and adaptable?
I tried to keep the code clear, with proper indentations, spacing between statements, and plenty of comments to explain what each line/lines of code were meant to do. Someone should be able to easily come in behind me and alter/enhance this code to make the program even more beneficial.
