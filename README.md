# Computational_Linguistics

1. write a python program that reads a para and:    
    a. tokenizes the text into words;  
    b. removes punctuations and converts all words to lowercase;  
    c. performs stemming and lemmatization.

2. Extract digits, Phone number, and email id from give sentence.

3. Implement simple rule based tokenizer for the English language, using regular expressions. The tokenizer should consider punctuations and special symbols as separate tokens. contractions like 'isn't' should be regarded as two tokens: is and n't, also identify abbreviations(eg: USA) and internal hyphenation (ice-cream) as single tokens

4. Implement a text classifier for sentiment analysis using Naive Bayes Theorem

5. Perform POS Tagging for an Indian lang (hindi since malayalam is too tough) using a pretrained model or dataset.   
Task:
    - Load a small set of sentences in the target lang.
    - Use libraries such as Stanza(?), IndiaNLP, or NLTK to tag parts of speech.
    - Identify common tag types and compare with english tags.
    - Discuss the challenges of POS tagging in morphologically rich lang.


6. Write a program or a script that corrects a single non-word spelling error based on the noisy channel model.            
Instructions:        
Corpus and Dictionary:        
Create a simple dictionary (V) of at least 5 common words.        
Error Simulation and Candidate Generation:        
Choose one word from your dictionary (e.g., "word") and introduce a single-character error (e.g., a substitution or transposition) to create a non-word misspelling (e.g., "wrod").        
Manually generate a candidate set of at least 3 plausible corrections for your misspelled word. These candidates must be real words from your dictionary.         
Calculating Probabilities:        
For each candidate word w and your misspelled word s, you need to calculate P(s∣w). You will need to make some assumptions for this part, as you don't have a real confusion matrix.        
Assumption: For a single-edit error, you can assign a fixed, small probability value (e.g., 0.001) for the channel model, representing the likelihood of that specific error type.        
Finding the Best Correction:        
Using the formula w=argmax w∈V P(s∣w)P(w), calculate the final score for each candidate in your set.        
Your program should output the candidate with the highest score as the corrected word.


7. Implement a word clustering using word embeddings(WordeVec) and plot clusters using PCA or t-SNE.


8. Write a program to compute translation probabilities p(f/e) and p(e/f) from a parallel corpus consider a paralle corpus of english and malayalam containing 5 sentences(manually construct it).


9. Design and implement a Finite State Automata(FSA) that accepts English plural nouns ending with the character 'y', e.g. boys, toys, ponies, skies, and puppies but not boies or toies or ponys. (Hint: Words that end with a vowel followed by 'y' are appended with 's' and will not be replaced with “ies” in their plural form).
