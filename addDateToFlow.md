# Added the Date Option to the Flow
Time: 45 Minutes
## Added An Option to Include Only the Reports that Had Been Made That Day
- Currently the Survey123 updates the same excel sheet. I wanted to put in an option that only included issues reported in a certain time period. This was a
huge missing piece of the puzzle, as before the Flow would just run on whatever reports were there and iterate through them.
- First I initialized a variable called date
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/f515a45b-ed0c-4cac-a90f-979d01989487)
- Formatted the current date to just include the month, as this was the monthy report
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/7b9843c3-e50b-4005-bd45-7a1e007ffa60)
- Added a condition to the action value
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/c7c73e84-ff32-485a-bd6a-8fe85f90734c)
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/f0e510cf-9ec2-494c-a531-8771242e7f98)
- If the current month was equal to the month in row, the count variable would be incremented
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/4b5369b1-2db0-47d9-b672-3fca389d16a6)
- Took me many different tries to get the date right. Power Automate formats days as dd, years as yyyy, but months as MM (case sensitive)
- Also put the date in the report as dynamic content
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/7947967a-1dbc-4b84-9422-b604acd12f1e)
- The report is the the following
- ![image](https://github.com/MayaIvimey/logs/assets/146374490/47e0de8b-a342-41a8-998e-8c23fc48fbea)
## Next Steps
- Because of the date format, it is easy to do monthy and daily reports. However, figuring out weekly reports will be a challenge
- other increment actions can be used to calculate different values for the report, eg how many fences were broken, how many people were hurt. 

