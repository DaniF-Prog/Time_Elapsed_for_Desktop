# Time_Elapsed_for_Desktop
  This is a simple program to find the difference in hours and minutes between two times in the day. This program does not work 
across date lines (for example trying to enter the period of 23:00 monday to 1:00 tuesday will not work) and all times must be 
entered using 24hr time format (use 13:00 instead of 1:00PM when using this program). You will be promped to the starting and
ending time hours and minutes, these should be entered as if reading off a digital clock. So if for example you want to find
the time elapsed between 11:32AM and 4:01PM the starting hour would be 11, the starting minutes would be 32, the ending hour 
would be 16, and the ending minute would be 1 (01 would work too though). The program will then time that elapsed between these
two times in the format of hours and then the additional minutes. 


TimeElapsed.c is the original source code

TimeElapsed.sh is the linux version which should be run in the terminal
