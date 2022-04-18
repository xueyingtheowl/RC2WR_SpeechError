# RC2WR_SpeechError_Stat
Statistical Modeling for the MA linguistic thesis--READING COMPREHENSION CONSTRAINS WORD READING: A TONGUE TWISTER STUDY BY MODERATING ATTENTIONAL CONTROL

SpeechError_Cleaning.Rmd is for preprocessing speech error data for later model usages. 

SpeechError_Model.Rmd  contains:
1)the statistical modeling (Poisson Regression) of correlations of Read and Recall task vs. Picture Priming task
Read and Recall task vs. Phonological Focus task using Possion regression with covariances includes order of the experiment, age, gender, 
multilingual background, self-evaluations of entire focus, self-evaluations of phological task focus.

2)the correlations (Logistic Regression) of each type of speech error with each type of tongue twister reading task.  
with covariances includes order of the experiment, age, gender, multilingual background, 
self-evaluations of entire focus, self-evaluations of phological task focus

Both statsitical models are run with (mixed effect)/without(fixed effect) the random effect of the participant. 
