# QLS-600-2023-Assignment

## Purpose
In this group assignemnt, you will learn how to collaborate on a reproducible project. 
The goal is to annotate research articles for demographic information. 

**Deadline for presentation: March 7**

**Deadline for assignment: March 10**

## Here are the steps : 
1. you will contribute to [this repository of annotations](https://github.com/neurodatascience/labelbuddy-annotations/)
1. annotations are done with [labelbuddy](https://jeromedockes.github.io/labelbuddy/labelbuddy/current/).
You will need to install the current [pre-release](https://github.com/jeromedockes/labelbuddy/releases/tag/v0.0.10-alpha)
The [installation instructions](https://jeromedockes.github.io/labelbuddy/labelbuddy/current/installation/) should be straightforward, but the links in there point to the latest *stable* release of labelbuddy (0.0.9).
Make sure you **install the latest pre-release** instead, which is a more recent version (0.0.10), found[here](https://github.com/jeromedockes/labelbuddy/releases/tag/v0.0.10-alpha).
In particular it is not available through the ppa so on Linux you should use the `AppImage`.
Don't hesitate to ask about any difficulties you may encounter.
1. Fork the [repository of annotations](https://github.com/neurodatascience/labelbuddy-annotations/).
You will work on the `participants_demographics` project.
You can have a look at the instructions on [getting started](https://neurodatascience.github.io/labelbuddy-annotations/contributing_to_this_repository.html), and the [specific instructions](https://neurodatascience.github.io/labelbuddy-annotations/projects/participant_demographics.html) for the `participants_demographics` project.
The repository and its documentation are still a work in progress and we are available to provide help; we hope that your feedback (possibly provided directly on GitHub) will help improve the project.
1. Once you have created annotations, export them (either from the labelbuddy interface or with the helpers provided in the repository), push them to a branch *on your fork of the repository* and open a Pull Request.
1. Once the annotations are done (question: how are they done ? can you document your process ? could someone look at what was done and reproduce the results or continue the work?), analyse the results to answer a scientific question, for example:

    - Do studies working on normal control have larger sample size than studies working on diseases ?
    - Is the group age different in healthy controls and patient groups ?
    - Are there differences in demographic information across diseases ?


Notes:

1. How to annotate will generate questions.
You will notice that for some papers, key information is missing, the structure of the participant groups is unclear, etc.
Some papers are also not relevant (eg animal studies, studies that do not involve the brain).
It is up to you to decide what to do with such studies; it is perfectly acceptable to exclude some of them.
1. The code to analyse the annotations should have its own git repository. 
1. The difficulty - and interest - of the assignment lies on how the group will organize itself. 
   I recommend that you decide on some organization / leadership early in the process. I will suggest also to use slack or equivalent tool for coordination.
