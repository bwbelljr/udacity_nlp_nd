# Project: Part of Speech Tagging (Udacity NLP Nanodegree)

In this project, I use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

I use several techniques, including table lookups, n-grams, and hidden Markov models, to tag parts of speech in sentences, and compare their performance. This project demonstrates text processing techniques that allow me to build a part of speech tagging model. I worked with a simple lookup table, and progressively added more complexity to improve the model using probabilistic graphical models. Ultimately I used a Python package to build and train a
tagger with a hidden Markov model, and was  able to compare the performances of all these models in a dataset of sentences.
