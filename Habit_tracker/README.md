# What is changed

After finishing the lecture, I found out few problems:
1. This habit tracker was unable to delete or edit the habit we added.
2. It was impossible to set the start/end date of the habit. If we add one habit, it takes the selected date as a start date and the habit exists infinitely.
3. When we mark the habit as completed, it won't let me uncheck the checkbox. So if the user accidentally marks it as completed, they were unable to uncheck the checkbox.  

So I added:
1. Cancel checkbox
2. Make the whole block clickable(Only textarea was clickable of the habit block)
3. Make habit edit&deleteable.
4. Add a function to determine if the invalid string is passed through input. (If it is, it will pop the alert message and not receive the string)
5. Add a function to add habits with date range(Number 4&5 changes were consisted of what I didn't learn yet. So I researched to achieve it)
