# Comparing Average Heart Rate Between Author’s VR Boxing and Brazilian Jiu-Jitsu Workouts

Matt Haffner\
Metropolitan State University\
DATA 211 - Data Science & Visualization\

## Abstract

This project looks to compare the average intensity of the author's two main forms of exercise. The exercise regimes consisted of Brazilian Jiu-Jitsu sparring (BJJ) and Virtual Reality (VR) Boxing (Thrill of the Fight on Meta Quest 2). The hypothesis is that the average inensity of the author's BJJ sessions was less than that of VR boxing sessions. Average intensity was determined with average heart rate. The Apple Fitness app on an Apple Watch Series 6 was used to collect heart rate data. The goal was to collect 30 minutes of heart rate data with no warm up.

Analysis of heart rate data was conducted with R Studio with paired T-Test and visualized graphically with ggplot2. The mean average heart rate for BJJ was lower than VR boxing, but the difference bwas not found to be significant (p > 0.05). It is likely that low sample sized prevented significant results. Technical issues with heart rate collection likely lowered the average reat rate for BJJ, which would have mistakenly pushed the analysis towards significance. Data collection often stopped early during BJJ workouts.

Exploratory analysis was conducted with linear regression to see the link between exercise duration and average heart rate to see if that could explain the lower mean average heart rate for BJJ sessions. The length of exercise sessions between exercise groups did show a significant positive correlation (p < 0.05, r = 0.070). Within BJJ workouts the correlation was not found to be significant (p > 0.05). It is likely that the lack of signifance in correlation was due again to low sample size. For future studies, a better heart rate monitor and larger sample size should be used.
