# Conta Stone Data Science Challenge

This is the solution proposed to [Stone Case for Data Science Role](https://gist.github.com/caiotaniguchi/a4c5229445a0adcf4dcb91111ea63152). You just need to run archives sequentially and everything should work out. I've run everything on a SageMaker environment, using a ml.m5.4xlarge (64GB) machine, so, even though it is not at all a small machine, it is one that someone working in the fintech environment should have access to.

The files contained in this project are the following:

- relational_schema.png: What I could infer from the Relational Schema of the tables from what I've studied.
- 01_DownloadFiles.ipynb: In this, I download the files mentioned in the case link, so I won't need to send them to git whenever I make a push.
- 02_InitialEDA.ipynb: Where I study the downloaded dataframes and try to infer how each table connects to each other.
- 03_Joins.ipynb: Where I join the tables to create a single one that can be used for the modelling process.
- 04_CreatingBooks.ipynb: Where I create some behaviour data regarding the customers transactions. Also here I show why I won't try to make any denylists using this data.
- **05_Modelling.ipynb:** Should be the heart of the case, where I develop the model, explain and evaluate it, make all the feature engineering process *et cétera*.
- 06_Policy.ipynb: Where, using the information given by the case, I explain how I think the model should be used.

Feel free to give me any sugestions and feedbacks!