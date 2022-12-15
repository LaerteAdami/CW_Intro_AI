# CW - Introduction to AI
Laerte Adami - Erik Duthiers

Used packages: 
- TensorFlow
- Numpy 
- Pandas 
- Sklearn 

The analysis carried out was aimed at developing artificial intelligence models in order to classify the health status of a fetus from certain obstetric measurements. An initial analysis of the data reported the presence of outliers, treated by introducing a threshold value on the standard score, and very unbalanced classes. Several methods were tested in order to select the best technique for the treatment of unbalanced classes, with the final choice being the SMOTE technique.

## Data 

The dataset selected for analysis consists of measurements of fetal heart rate (FHR) and uterine contraction characteristics (UC) on cardiotocograms graded by experienced obstetricians.

The data consists of 21 numerical features for a total number of 2126 fetal cardiotocograms (CTG). These were processed automatically and the respective diagnostic features were measured. CTGs were classified by three experienced obstetricians and each was assigned a consensus classification label. 

The classification was performed both with respect to a morphological pattern, consisting of 10 classes (A, B, C...), and with respect to a fetal status, consisting of 3 classes (N: neutral, S: suspect , P: pathological).

The the features are here listed and briefly described:

- LB - FHR baseline (beats per minute)
- AC - accelerations per second
- FM - fetal movements per second
- UC - uterine contractions per second
- DL - light decelerations per second
- DS - severe decelerations per second
- DP - prolonged decelerations per second
- ASTV - abnormal short term variability
- MSTV - mean of short term variability
- ALTV - abnormal long term variability
- MLTV - mean of long term variability
- Width - width of FHR histogram
- Min - minimum of FHR histogram
- Max - maximum of FHR histogram
- Nmax - numbers of histogram peaks
- Nzeros - numbers of histogram zeros
- Mode - histogram mode
- Mean - histogram mean
- Median - histogram median
- Variance - histogram variance
- Tendency - histogram tendency- 