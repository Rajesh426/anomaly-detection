# anomaly-detection
Its is a simple Ipython files for basic Anomaly Detection Algorithm 
# Four Simple Anomaly Detectiona are implemented <br>
# 1. With Standard Anomaly Detection with mean and Standard Devivation <br>
Based on the Anomaly or Outlier are detection is based on the interval <br>
Lower Cut off  = mean - 3* Standard Devivation <br>
Upper Cut off = mean + 3* Standard Devivation <br>

# 2 Using Simple Box plot <br>
Boundaries are based on the median and IQR of the Box plot

# 3 DBScan <br>
Defining a rule that if a sample is having only one or two samples around it then group it as Outlier <br>

# 4 IsolationForest <br>
One technique of finding outliers where a decision tree [IsolationForest]  is implemented .<br>
Here for a data if the ouput is -1 then it is outlier or Anomaly
