---
title: 재현 가능한 연구 
subtitle: Concepts and Ideas
author: Keon-Woong Moon
job: Professor of Cardiology, St.Vincent's Hospital
widgets: [mathjax, bootstrap, quiz]
github:
  user: ramnathv
  repo: slidify
url:
  lib   : ../../libraries
  assets: ../assets
copy_libraries: true

---

These slides are modified from **slidify** library (ramnathv)

--- &radio .quiz



## Question 1 ##

Suppose I conduct a study and publish my findings. Which of the following is an example of a **replication** of my study?

1. An investigator at another institution conducts a study addressing a different scientific question and publishes her findings.
2. I take my own data, analyze it again, and publish new findings.
3. _An investigator at another institution conducts a study addressing the same question, collects her own data, analyzes it separately from me, and publishes her own findings._
4. I give my data to an independent investigator at another institution, she analyzes the data and gets the same results as I originally obtained.

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 2 ##

Which of the following is a requirement for a published data analysis to be reproducible?

1. The data analysis is conducted using R.
2. _The investigator makes the analytic data publicly available._
3. The analysis is conducted on a variant of the Unix operating system.
4. The investigator's final publication is made available free of charge.
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 3 ##

Which of the following is an example of a reproducible study?

1. The study's analytic data and computer code are not publicly available, but the study was simple enough to be repeated by an independent investigator.
2. _The study's analytic data and computer code for the data analysis are publicly available. When the code is run on the analytic data, the findings are identical to the published results._
3. The study's analytic data are publicly available, but the computer code is not.
4. The study's original authors re-run their computer code on their analytic data and confirm publicly that the findings match those of the published results.
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 4 ##

Which of the following is a reason that a study might NOT be fully **replicated**?

1. The original study was conducted by a well-known investigator.
2. The original study had null findings.
3. The original study was published in a high impact journal and is considered authoritative.
4. _The original study was opportunistic in its timing and it would be difficult to find a similar context in which to repeat it._
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 5 ##

Which of the following is a reason why publishing **reproducible research** is increasingly important?

1. Computing power is limited today, making it difficult to apply sophisticated statistical methods.
2. Most studies today are small-scale and easily replicated.
3. The statistical methods for most studies can be accurately described using plain language.
4. _New technologies are increasing the rate of data collection, creating datasets that are more complex and extremely high dimensional._
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 6 ##

What is the role of *processing code* in the research pipeline?

1. It transforms the computational results into figures and tables.
2. _It transforms the measured data into analytic data._
3. It transforms the analytic data into computational results.
4. It conducts the statistical analysis of the primary outcome.
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 7 ##

Which is a goal of literate statistical programming?

1. Ensure that data analysis documents are always exported in PDF format.
2. _Combine explanatory text and data analysis code in a single document._
3. Require that data analysis summaries are always written in LaTeX.
4. Separate figures and tables from other data analytic summaries.
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 8 ##

What does it mean to weave a literate statistical program?

1. _Transform the literate program into a human readable document._
2. Compress the literate program so that it takes up less space.
3. Transform a literate program from R to python.
4. Transform the literate program into a machine readable code file.
   

*** .hint

This is a hint

*** .explanation

This is the explanation


--- &radio .quiz

## Question 9 ##

Which of the following is required to implement a literate programming system?

1. _A programming language like R._
2. A web server for publishing documents.
3. A program that views PDF files.
4. A cloud-based computing service for running computations.
   

*** .hint

This is a hint

*** .explanation

This is the explanation

--- &radio .quiz

## Question 10 ##

What is one way in which the knitr system differs from Sweave?

1. knitr was developed by Friedrich Leisch.
2. _knitr allows for the use of markdown instead of LaTeX._
3. knitr is written in python instead of R.
4. knitr lacks features like caching of code chunks.

*** .hint

This is a hint

*** .explanation

This is the explanation
