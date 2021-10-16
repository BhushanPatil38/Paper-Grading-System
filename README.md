# Paper-Grading-System

#### The paper grading system will take answers as input and would compare them with the ideal answer to grade students. The answers will be processed and broken down into root words to compare with the ideal answers.
#### Using semantic analysis, the similarity between words will be measured by similarity index which would return a score. Even if different synonyms are used, the program maps the synonyms using Ontology and generates a perfect score. Hence, if different words are used and the same meaning is conveyed, then the student would get full marks. 

#### Steps followed in processing-
##### 1. Read Data from File
##### 2. Identify and remove the stopwords
##### 3. Use the Lemmatizer to tokenize the words and fetch it's root form (example - "drinking" becomes "drink")
##### 4. Calculate similarity Index and based on a threshold, return the grade.
