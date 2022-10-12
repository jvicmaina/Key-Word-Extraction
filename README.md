# Key-Word-Extraction
Extracting key words in python for CVs from job description
The following were files that we used.
1. spaCy
SpaCy is all in one python library for NLP tasks. But, we are interested in the keyword extraction functionality of spaCy.

We will start with installing the spaCy library, then download a model en_core_sci_lg. After that, pass the article text into the NLP pipeline. It will return the extracted keywords.

Each model has its own functionality. If an article consists of medical terms, then use the en_core_sci_lg model. Otherwise, you can use the en_core_web_sm model.

Find the related code below.
