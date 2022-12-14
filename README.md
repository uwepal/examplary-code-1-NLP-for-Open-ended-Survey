# Examplary-code-1-NLP-for-Open-ended-Survey

This program illustrates topic modeling to analyze open-ended survey responses using Latent Dirichlet Allocation (LDA).

A pulse survey was given to a school district's students, staff, and parents about their experiences of (Q1) technology challenges during remote learning at the onset of COVID-19 pandemic, and (Q2) their recommendations of how to improve students' remote-learning experiences. 

We preprocessed the raw text responses by combining all responses from all three groups together for each question. We tracked metadata for the source of each response (student, staff, parent): 

    For Q1 technology challenges: 7527 documents by 1206 term; 
    For Q2 improving remote learning: 8967 documents by 1840 terms

Additional processing:
    (1). Convert terms to lower case and remove punctuation; 
    (2). Remove stop words: these are common words that don’t add much semantically (e.g. “a”, “and”, and “or”); 
    (3). Stem words: removing suffixes to reduce to root word; 
    (4). Filter infrequent terms.

We then use LDA topic modeling to analyze the latent semantic themes in the open-ended responeses. This topic modeling works best for questions that ask respondents to discuss a wide-range of ideas. LDA requires researchers to specify the number of topics. We used both diagnostic model statistics and human expert coders' evaluation to choose the best model fit. We also build visulation of topic modeling results to facilitate expert coders' evaluation of topic loadings and patterns by respondent types (students, staff, and parents) and by school locations.


