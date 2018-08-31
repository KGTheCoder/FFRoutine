# FFRoutine
I am doing a workout routine called "Fierce Five." To track my progress, I created a program that allows the user to enter their lifts for each required workout.
# How to run
When asked:
```
Are you appending data, or submitting a new week? A for APPEND, N for NEW: 
```
Please enter "N" for a new entry. 
Next, enter a date.
The routine is split into A and B (consisting of different lifts) preformed every other day, 3 times a week. For example:
```
Monday:
A
Wednesday:
B
Friday:
A
```
Assuming this is your first entry, pelase select "A."
Enter the amount of weight you preformed for each lift:
```
Squat: 200
```
Once completed, a ".txt" file will be created, and once opened, will look like:
```
7/17/2018
------------------ 
A:
Squat 3x5: 180 lbs
Bench 3x5: 125 lbs
Pendlay row 3x5: 110 lbs
Face pulls 3x10: 20 lbs
Calf raises 2x15: 135 lbs
Tricep pressdowns 2x10: 20 lbs
```
To append data, such as adding workout "B," change "w" to "a." Example:
```
f = open("Fierce_Five.txt", "w")
```
to 
```
f = open("Fierce_Five.txt", "a")
```
This allows the user to append data, instead of writing new data.
When prompted:
```
Are you appending data, or submitting a new week? A for APPEND, N for NEW:
```
Select "A" to append data. 

# Acknowledgements
Special thanks to the creator of the "Fierce Five Novice Routine:" Bodybuilding.com user "davisj3537."
