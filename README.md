# QLS-600-2023-Assignment

## Purpose
In this group assignemnt, you will learn how to collaborate on a reproducible project. 
The goal is to annotate research articles for demographic information. 

## Here are the steps : 
1. you will find the articles in [this folder in the annotation repo](https://github.com/neurodatascience/labelbuddy-annotations/tree/main/projects/participant_demographics)
2. Choose a set of article to annotate in the ones already in the git repository (don't add articles). 
   Each student could do about 10, overall we should have about 100 articles annotated 
3. Use the tool [labelbuddy](https://jeromedockes.github.io/labelbuddy/labelbuddy/current/) to annotate and save annotations. You should annotate the number of samples in groups of participants (overall and by sex), their age range, whether these are healthy controls or a patient group.  
4. Push your annotations on [this folder in the annotation repo](https://github.com/neurodatascience/labelbuddy-annotations/tree/main/projects/participant_demographics/annotations)
5. Once the annotations are done (question: how are they done ? can you document your process ? could someone look at what was done and reproduce the results or continue the work?), analyse the results to answer the questions
  5.a. Do studies working on normal control have larger sample size than studies working on diseases ?
  5.b  Is the group age different in healthy controls and patient groups ?
  5.c  Are there differences in demographic information across diseases ?

Notes:
1. How to annotate will generate questions. You will use predefined labels, but in a paper you will find that there maybe several groups / studies. 
  The recommendation is to add labels like "study-01", "study-02" to differentiate if that is the case.
2. The code to analyse the annotations should have its own git repository. 
3. The difficulty - and interest - of the assignment lies on how the group will organize itself. 
   I recommend that you decide on some organization / leadership early in the process. I will suggest also to use slack or equivalent tool for coordination.
