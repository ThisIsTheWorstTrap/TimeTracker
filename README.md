# TimeTracker

config.ini file format

--------
[config]
minSizeButtonsWidth=numberPixels
minSizeButtonsHeight=numberPixels
maxSizeButtonsWidth=numberPixels
maxSizeButtonsHeight=numberPixels
buttonTextSize=fontSize

[categories]
taskCategory1=priorityTaskCategory1
taskCategory2=priorityTaskCategory2

[taskCategory1]
task1=taskPriority1
task2=taskPriority2

[taskCategory2]
task3=taskPriority3
task4=taskPriority4

-------------------

The priorities are used to set the order of the visible tasks, according to their corresponding categories.
The categories must not have the name "category" or "categories" in them or the time tracker will not print the tasks.

timeTrackingFile.txt file format

------------------------------------------------------
taskCategory1::task1=year-month-day hour:minute:second
pause=year-month-day hour:minute:second
---------------------------------------

the date corresponds to the moment the task was started and the "pause" corresponds to a moment no task was active



the ---- delimits the file format
