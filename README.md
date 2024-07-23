Translation Application

Overview

This project is a translation application built with Python, leveraging the IBM Model 1 translation model. It is designed to translate sentences from Luhya Logooli to Kiswahili. The application includes a graphical user interface (GUI) developed using Tkinter, allowing users to input Luhya Logooli sentences and receive translated Kiswahili sentences. Additionally, users can load a dataset, clean the sentences, train the translation model, and evaluate the model using the BLEU score.

Features

Sentence Cleaning: Preprocess and clean sentences by removing unwanted characters and converting text to lowercase.

Translation Model: Train an IBM Model 1 translation model using aligned sentences from the provided dataset.

User Interface: A Tkinter-based GUI for user-friendly interaction, including:

Input field for Luhya Logooli sentences.

Display of translated Kiswahili sentences.

Buttons for translating sentences and loading/training the model with a dataset.

BLEU Score Evaluation: Evaluate the quality of translations using the BLEU score.

Requirements

Python 3.6+,
pandas,
nltk,
tkinter.
