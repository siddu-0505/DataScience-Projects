Project: Fetal Health Data Set - Model Tuning

About the DataSet

Classify fetal health in order to prevent child and maternal mortality

Size of the dataset : 2126 records * 22 features

The datasets consist of several features and Target as shown below :

baseline value : FHR baseline(beats per minute)

accelerations : Number of accelerations per second

fetal_movement : Number of fetel movements per second

uterine_contractions : Number of utereine contractions per second

light_decelerations : Number of light decelerations per second

severe_deceleration : Number of severe decelerations per second

prolongued_decelerations : Number of prolongued decelerations per second

abnormal_short_term_variability : Percentage of time with abnormal short term variability

mean_value_of_short_term_variability : Mean value of short term variability

percentage_of_time_with_abnormal_long_term_variability : percentage of time with abnormal long term variability

mean_value_of_long_term_variability : mean value of long term variability

histogram_width : Width of FHR Histogram

histogram_min : Minimum(Low Frequency) of FHR Histogram

histogram_max : Maximum(High Frequency) of FHR Histogram

histogram_number_of_peaks : Number of histogram peaks

histogram_number_of_zeroes : Number of histogram Zeroes

histogram_mode : Mode of histogram

histogram_mean : Mean of histogram

histogram_median : Histogram Median

histogram_variance : Histogram Variance

histogram_tendency : Histogram Tendency

Target:

fetal_health: 1-Normal 2-Suspect 3-Pathological

What we have done!
1.Perform EDA on given DataSet

2.Build a model

4.Perform Hyper Parameter Tuning

Tools we have used:
1.Numpy

2.Pandas

3.Matplotlib

4.Seaborn

5.Sklearn
