Hi Dears,

The goal of the data challenge is to propose you to resolve a use case in data analysis, which is usually taken from real scientific projects and real data (in a simplified form). You will be given with some omics data and a goal (challenge). You are then free to use any approach and technique to succeed. Depending on the question, sometimes it would be more appropriate to use classical statistical methods, sometimes skills in machine learning may be helpful.

This challenge aims to use statistical or machine learning models (e.g. linear models, support vector machines) to predict the expression of the first gene using provided multi-omics and clinical observations.

The challenge provides 2 data.frames (data_test and data_train, see below) of low grade glioma samples described by sex, age, histology, genes expression and DNA methylation values (multi-omics). The goal of this challenge is to predict the expression of the first gene (ALS2). The gene expression values are log normalized : log2(DESeq2_normalized(raw_counts) + 1)

Secret URL is: 
  https://competitions.codalab.org/competitions/28931?secret_key=156ec53c-3ae2-4788-ac69-1eb11c467910  

A presentation is also available there: 
  https://youtu.be/dyk8CAQVWHE
  
And an extented starting kit including a guided report there:
  https://github.com/fchuffar/starting_kit_expred3.0

We hope you will enjoy the challenge.


--<br/>
The Gene Expression Prediction Challenge 3.0 (expred3.0) Team
