#ASSIGNMENT2 (5071089 VISHAL VALLAMKONDA)

**AIM**

Using unnamed pipes make philosopher to enter, sit and eat endlessly and makes a philsopher to stop eating and exiting.

**MODULES THAT NEED TO BE INSTALLED BEFORE**

pip3 install random && pip3 install time && pip3 install threading

**EXCUTING THE CODE**

python3 A2.py

**ABOUT THE CODE**

In this assignment i have used threading module to create a processes and communicate with pipe unfortunately I could make with separate shell windows because python doesn’t support it. First  def __init__(self, index):   initialize and start threading.  def dine(self): every professor come and eat for randomly chosen time between 3 to 15 seconds. Then leaves the restaurant.

**EXPECTED OUTPUT OF THE CODE**

Philosopher 3 starts eating.

Philosopher 0 starts eating.

Philosopher 2 starts eating.

Philosopher 1 starts eating.

Philosopher 4 starts eating.

Philosopher 2 finishes eating and leaves the restaurant.

Philosopher 3 finishes eating and leaves the restaurant.

Philosopher 1 finishes eating and leaves the restaurant.

Philosopher 0 finishes eating and leaves the restaurant.

Philosopher 4 finishes eating and leaves the restaurant.


Then waiting for 75 seconds it prints out

Now we're finishing.
