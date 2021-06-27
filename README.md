# LDA-Modeling-Python-Challenge
LDA Classification Model
Challenge Question- Please use R or Python – submissions using R-markdown or Jupyter notebook are preferred. 
If you don’t feel comfortable using these feel free to submit a commented script file and a word document with written responses.

Estimated time to complete ~60 minutes. 

1)	The three consecutive integers 110, 111 and 112 are all multiples of the sum of their digits…
a.	Using a brute-force search, find all 4 consecutive 3-digit integers that are like this. 

b.	Are there 17 consecutive 3-digit integers, such that they cannot be divided by the sum of their digits? 18?

c.	If your search range was expanded to [102, 1012] – Please discuss how would you speed up or optimize your search algorithm without any additional computational resources? What utilities, functions or packages would you use during testing to benchmark performance? 

2)	Download the phoneme dataset (CSV) from https://web.stanford.edu/~hastie/ElemStatLearn/datasets/phoneme.data.

The dataset is [4509 x259] and contains frequency measurements for five (5) phonemes sampled at 16 kHz for 256 measurements per observation. Predictor features are labeled "x.1" - "x.256" and the response is labeled “g”, the phoneme. The “speaker” column contains a unique identifier for each the speaker used to generate the observed data – ignore this field.

Full dataset information is available in https://web.stanford.edu/~hastie/ElemStatLearn/datasets/phoneme.info.txt.

a.	Perform a quick exploratory analysis with summary statistics and plots. 

b.	Implement an LDA classification model of {g ~ x.1 + x.2 + … + x.256} for the “g” response using cross validation or other sampling methods if deemed necessary. 

i.	Print model performance statistics, generating plots as necessary and write a quick narrative summarizing results. 

ii.	What are some considerations that should be made before implementing LDA? Does your exploratory analysis suggest that this is a good modeling technique to use for this data? 

