# Information Measure based Anomaly detection using Adjusted Leverage
This repository shows the developed algorithm of adjected leverage for event log and baseline models including Sampling, Naive, OC-SVM, DAE, BINET refered from [2].
The algorithm of adjected leverage is coded using statistical package R and calculate anomaly score of each case in trace level. 
The total performance result was recored in table.csv file.


## Prepared data - 70 artifical logs
We used 7 types of process models including large_log, small_log refered from [1], small, medium, large, huge, wide refered from [1] to generate artificial logs. With 10 times of repetition, there are 10 artifical_logs for each model.  

In process models of large_log and small_log, we injected "replace" anomaly pattern used in [1]. In otherwise, in process models of small, medium, large, huge, and wide, we injected 5 types of anomaly patterns including "insert", "skip", "early", "late", and "rework" used in [2]

## Prepared Data - 12 real-life logs
For real-life logs, we used BPI challenge 2012, 2013, 2015, 2017, 2019 data sets. For each log in BPIC13, BPIC15, BPIC17, there are 3, 5, 2 subsets of logs. 

About anomaly patterns, we injected 5 types of anomaly patterns including "insert", "skip", "early", "late", and "rework" on real-life logs.


## References
[1] Nguyen, H. T. C., Lee, S., Kim, J., Ko, J., & Comuzzi, M. (2019). Autoencoders for improving quality of process event logs. Expert Systems with Applications, 131, 132-147.
[2] Nolle, T., Luettgen, S., Seeliger, A., & Mühlhäuser, M. (2019). Binet: Multi-perspective business process anomaly classification. Information Systems, 101458.









