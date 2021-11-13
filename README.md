# NLP Chat Bot for Wikipedia 

NLP Chat Bot that dynamically locates wikipedia sources and applies NLP to answer questions

# Project Overview
- Chat Bot wrapper
- Wikipedia content locator
- NLP question answering


**Modules:**

Application.py - Main Applicaiton
DocumentRetrival.py - Retreiving Wiki pages based on user query.
ContextExtraction.py - Extract only the Necessary Paragraphs from the Wiki pages.
DataWrangling.py - Perform Data Wrangling tasks.
ContextSimilarity.py - Perfrom Context Similarity using google universal sentence encoder and retreive only topN out of it.
MLModel.py - Pass the TopN similarities from ContextSimilarity to Roberta model and select only topN predicitons that matches user query.

Finally ML model Predictions are shown and saved in file.
