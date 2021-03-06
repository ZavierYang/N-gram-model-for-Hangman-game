# Hangman game
The [Hangman game](https://en.wikipedia.org/wiki/Hangman_(game)) is a game whereby one person thinks of a word, which is kept secret from another person, who tries to guess the word one character at a time. The game ends when the guessesing count achieve more than a fixed number (8 in general) of incorrect guesses, or the secret word is guessed.

The aim of this repo is to apply a language model, [N-gram model](https://en.wikipedia.org/wiki/N-gram#n-gram_models), to guess the secret word automatically. Besides, an automatic player needs to make the guessing count as few as possible. The ultimate goal is to be less than 8 since it means that the AI player will not lose the game.

To build the model for N-gram, I used Brown corpus in NLTK. In my implementation, there are random guessesing method (for fun), unigram model, bigram model, and trigram model with smoothing method. Among them, the last method has the least average number (8.102) of guesses. The detail of the implementation are all in notebook.

# Importance
This is a assignment from a NLP course (subject). **If you come to watch because of your course (subject) assignment, DO NOT just copy and paste this code or just modify the variables names. Otherwise, your score is possible to be penalised.** Moreover, The goal of this project is to build and critically analyse some supervised Machine Learning algorithms. Therefore, in this repository, I just tried to implement multiple models to compare their performances. There is no guarantee that these models are the best. 

## Source
University of Melbourne COMP90042 Subject.
