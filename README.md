# RC2WR_SpeechError_Stat

This repository contains codes for my MA thesis research-- Reading Comprehension Constrains Word Reading: A Tongue Twister Study by Moderating Attentional Control.

SpeechError_Cleaning.Rmd is for preprocessing speech error data for later model usages. 

SpeechError_Model.Rmd contains: 1)the statistical modeling (Poisson Regression) of correlations of Read and Recall task vs. Picture Priming task, Read and Recall task vs. Phonological Focus task using Possion regression with covariances includes order of the experiment, age, gender, multilingual background, self-evaluations of entire focus, self-evaluations of phological task focus.

2)the correlations (Logistic Regression) of each type of speech error with each type of tongue twister reading task. With covariances includes order of the experiment, age, gender, multilingual background, self-evaluations of entire focus, self-evaluations of phological task focus

Both statsitical models are run with (mixed effect)/without(fixed effect) the random effect of the participant.

If you are intersted in the annotated speech error data, please email me at xueying.wang@rochester.edu

Timeline of the research:

01-05.2021: Initialize the idea, construct theory, design experiment, decide statistical plans
06.2021: IRB application, participants recruitment, literature review written
07-09.2021: Data collection, 1st round data annotation, experiment procedure part written
09-11.2021: 2nd and 3rd round data annotation, data preprocessing and analysis, complete draft written
11-12.2021: Thesis for defense submitted to committe members and defensed
02-2022: Thesis edited based on committe memebers' suggestions and submitted to the gratuate school for publication
