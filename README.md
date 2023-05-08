# Hydar-Raye
Original AI chatbot for Hydar-XYZ
The objective in this bot's development was to make something that speaks in a manner similar to existing users of the site.

## How it works
Raye basically boils down to finding something in the input files that most closely matches with what was asked to her and responding with the response from her files.
In other words, if you ask Raye something, it will see if someone else has asked something similar, and give the response that was given to that previous question. Thus, Raye will emulate prior users' conversations.
What makes it "advanced" is not the overall algorithm but the process of which the user's input is compared to lines from the files, as well as the selection process for determining the appropriate response. 
Additionally, some functions were done in C in order to speed up processing.


## First algorithm - compare strings
