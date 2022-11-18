# examplary-code-1-NLP-for-Open-ended-Survey

This program illustrates topic modeling of open-ended survey responses using LDA.

The survey was given to a school district's students, staff, and parents about their views of (Q1) technology challenges to support remote learning during the onset of COVID-10 pandemic, and (Q2) their recommendations of how to improve students' remote-learning experiences. We preprocessed the raw text responses by combining all responses from all three groups together for each question. 

We tracked metadata for the source of each response (student, staff, parent): 

For Q1 technology challenges: 7040 documents by 1093 terms
For Q2 improving remote learning: 8659 documents by 1642 terms

Additional processing:
Convert terms to lower case and remove punctuation; 
Remove stop words: these are common words that don’t add much semantically (e.g. “a”, “and”, and “or”)
Stem words: removing suffixes to reduce to root word; 
Filter infrequent terms


