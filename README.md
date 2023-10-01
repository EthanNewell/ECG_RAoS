## This repository includes: a sample of clean and dirty data, heart rate analysis with noise removal (optional), Bayevsky stress index, prediction of ECG signal behavior, OBS cam settings

## The first part of the research involves preparing the received ECG signal for training the neural network 
1) We filter the signal from noise.
2) We split it into parts by time intervals 
3) Highlight R-R intervals
4) Find x coordinates where R-R intervals occur
5) Get the distance between R-R intervals 
6) Find the most frequent value of R-R intervals
7) Calculate stress index according to Baevsky index 

>Stress index formula
>si = AMo / (2 * VR * Mo)
where  
R-R interval - the time delay between consecutive heartbeats (assumed to be the inverse value of the bpm)  
Mo - mode - most frequent R-R interval value  
AMo - mode amplitude - % of the intervals corresponding to Mode  
VR - variational range - the difference between min and max R-R intervals

## The second part is neural network training 
in progress 
