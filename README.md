Download link :https://programming.engineering/product/galactic-trade-routes/

# Galactic-Trade-Routes
Galactic Trade Routes
The time for an interstellar trade route has come! The plaque sent out on the Pioneer probes was decoded by an alien civilization, and they have imparted to us the secrets of interstellar travel. Your job is to nd the two stars near-est to each other in our galaxy, and begin your trade route between these two star systems. Well assume that you can pick any two stars to begin your trade route; you dont have to start at Earth. Being as our galaxy has a lot of stars (up to 400 billion), your algorithm will need to be e cient.

For this assignment, we’ll assume that our galaxy is 2-dimensional, so you’ll need to handle star locations in 2D

space. The coordinates will range from -50,000 to +50,000 (the Milky Way is 100,000 light years in diameter). Your trading ships cannot travel more than 10,000 light years, and any input case that has no stars closer than this will need to indicate such.

Input

The input will consist of a number of test cases (more than one per le!). The rst line of each test case will contain n, the number of stars for that case: 2 n 100; 000. The following n lines will contain the (x,y) coordinates of successive stars. Each x and y coordinate will be a real number with a minimum value of -50,000 and a maximum value of 50,000. The coordinates will be given to two decimal places of accuracy. The input will terminate when n=0

Output

For each test case, your output should contain a single line that is the minimum distance between two points, to four digits of accuracy after the decimal point. You should not print the stars that are closest; only the distance. If there are no points closer than a distance of 10,000, you should print out in nity.

Grading

You will pass this assignment if you pass enough test cases AND submit an acceptable report. You must have the following:

1. Submitted code that uses divide-and-conquer and passes at least 8 out of 10 of the test cases.

Sample Input

2

1.25 6.11

1.64 1.50

2

0 0

10001

3

-6.47 2.24 8.90 6.53

-1.45 5.05

Sample Output

4

2.77

-9.81

4.6265

-0.19 4.85

infinity

1.38

9.05

5.7530

-4.95 3.93

4.4838

10

3.2257

8.15

6.21

-5.64 -4.31

-0.03 7.05

5.98

-4.64

1.49

-1.59

4.34

0.67

-2.79 -0.93

-7.41

2.89

-1.79

-6.22

-0.98

1.74

0

