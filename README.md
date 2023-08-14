# word-spin
An NLP-model that edits existing sets of words to create original writing.


## Technologies Used
- BeautifulSoup
- NLTK (Natural Language Toolkit)
- Text processing,
- Tokenization
- Language modeling.
- Numpy and Pandas

## Techniques Used:
- Trigram Language Model
- Text Processing
- Random Sampling


## Functionality
- Model reads positive reviews from a file, tokenizes the text, creates trigrams(three-word pairs)
- The trigram model captures the probabilities of the middle word in a trigram(three consecutive words) based on the surrounding words.
- A function called "random_sample"is used to select a word randomly based on given probabilities.
- The "test_spinner" function randomly replaces words in a chosen positive review with new words based on the trigram probabilities.
- This process results in a "spun" version of the original review, where some words have been replaced while maintaining the general structure.
- The "test_spinner" function is called to demonstrate the process of random sentence spinning on a randomly chosen positive review.




