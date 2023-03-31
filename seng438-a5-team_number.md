**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#: 22       |  |
|-----------------|---|
| Student Names:  |  Topan Budiman |
|                 |  Mark Ngu |
|                 |  Jacob Schon |
|                 |  Muhammed Shah |


# Introduction

The purpose of this lab is to analyze test data using reliability assessment tools using the following two methods: Reliability Growth Testing and Reliability Demonstration Chart (RDC). We will perform tests on a hypothetical system using SRTAT (Software Reliability Testing Analysis Tool) to measure the failure rate, MTTF and reliability of the SUT. The RDC will tell us if the failure rate or MTTF is met.

# Assessment Using Reliability Growth Testing 

![image](https://user-images.githubusercontent.com/65151396/229208958-d5644f1b-07ca-42d1-8de0-6e70d881ef82.png)
**Figure 1:** Plot of Time Between Failure

The graph above is the plot of time between failure. When using the … to model the graph, we see that we get an exponential curve which is what we expected. This is ideally what we want because as the failure number increases, we want the time between each failure to also increase. Since it’s exponential, that means that the time between each failure increases greatly when compared to a linear plot. The acceptable range for time between failure would be the area below the curve. If we were to use an acceptable value for time between failure, we would select where the curve intercepts the Y-axis which is approximately at <br>600-700</br> units of time.

![image](https://user-images.githubusercontent.com/65151396/229209237-7371a4c8-1ad8-492c-bd5e-4813aa06d4d5.png)
**Figure 2:** Error message when trying to plot failure count/failure intensity

Although we weren’t able to plot the graph for failure intensity, the output we would expect is an inverse exponential graph. This is because per every unit of time that goes by, we would want the number of failures to decrease. Ideally, this graph would be exponential as this would show that the amount of failures per unit of time decreases at a much faster rate than a linear plot. The acceptable range of failure rate would be the area below the curve. 

# Assessment Using Reliability Demonstration Chart 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

Since the assignment consisted of two parts, we split into groups of two to complete each section of the assignment. Part one required running a program that could only run on Windows, so Muhammed and Topan took this task one since Muhammed had a Windows computer. Part two was analyzing the results from an Excel file so Gabe and Jacob worked on that section.

# Difficulties encountered, challenges overcome, and lessons learned

A difficulty we encountered during this assignment was that the program required for part one only ran on Windows. This drastically slowed down our workflow since only certain people could work on one section.

# Comments/feedback on the lab itself

This lab was very difficult to do since setting up the environment was very buggy. The program in part one only runs on windows and only one member of our group was able to work on it. 
