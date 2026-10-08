# HW4
This is the template repository for HW4 in CS3 (Traffic)

Baseline it takes 51 seconds to run a day's worth of data
After changing the strange power function to cmath pow the run time is lowered to the same
deleted waste time and be slow, made it to 49 seconds, 2 second increase in speed
removing the double loop at the end of sim_math made it to 28 seconds
Changed compile flag from -O0 or -O3
Deleted ALL(); From main()
removed the second query as it was no longer necessary
bottled necked the percentage output to make it slower/easier on the computer, also removed the strange back and forth vector creation assignment and interation in main
new fastest run time at 1.5 seconds real time
Changed progress strings to speed up run time, real run is now .11 seconds for a day