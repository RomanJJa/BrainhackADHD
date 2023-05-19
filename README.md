# BrainhackADHD
This is a repository for my ADHD project as a part of the Brainhack School.

## Project goals
I will look for differences in function and functional connectivity between ADHD and non-ADHD participants. That means that I will first look at general differences in variance of the BOLD signal within participants and then try to explain that with questionnaire data and functional connectivity.
- Variance of differential signal over different brain areas.
- Averaging time series with an Atlas and extracting time series from those brain areas
- correlating the average signals (maybe also over different time lags)
The goal is not to create a highly efficient program but to present and visualize each step of the analysis so that we know what is going on in this analysis. This should especially help newcomers to fMRI (like myself).

The goal is that anybody is able to apply this script (or at least some of it) to their own data by changing the parameters that I will highlight. When testing for variance and covariances and their differences between subjects, I will include statistical tests (such as voxel-wise F-tests) that include leave-n-out to avoid false positive test results.

### Project GitHub repository
Github.com/RomanJJa/BrainhackADHD

### Discord handle of the project leader
@RomanJJ

### Hub of the project
Paris

### Data and tools to use
ADHD patient study of the University of Innsbruck (Austria) and all participants have been scanned with the same scanner and the same adjustments. Unfortunately, statistics of this study have not been published yet so I cannot offer them up yet. But I will try to write this script so that any other data would be applicable to these scripts. I have already preprocessed the data (but not smoothed).
I will use Python and the R programming language for more complex statistical analysis.

