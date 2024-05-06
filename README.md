# Readability Score

Java Project @JetBrains Academy

A program designed to analyze text readability using various metrics to determine its complexity level. It accomplishes the following tasks:

- Analyzes text at the levels of words, sentences, and characters.
- Calculates different readability scores, such as Flesch-Kincaid, Automated Readability Index, Coleman-Liau, and SMOG.
- Determines the age required to understand the text based on these readability scores.
- Supports text reading from files.

## Prerequisites

This program requires Java to compile and run.

## Installation

- Download this repository and unzip the .zip file in your desired location.
- Open a terminal, then enter ```cd "Readability Score\task\src"```.
- Compile the program using the command ```javac readability\Main.java```.
- Run the program using the command ```java readability.Main readability\in.txt```.

## Example of use

The symbol > represents the user input. Notice that it's not the part of the input.

```
> java readability.Main readability\in.txt

The text is:
This program allows user to calculate the readability score of the text in a file (the path is accepted as a console 
parameter) and outputs the recommended age to understand it. It also counts the number of sentences, words, characters 
(without spaces), syllables and polysyllables.

Words: 45
Sentences: 2
Characters: 238
Syllables: 85
Polysyllables: 6
Enter the score you want to calculate (ARI, FK, SMOG, CL, all): all

Automated Readability Index: 14.73 (about 0 year olds).
Flesch-Kincaid readability tests: 15.47 (about 0 year olds).
Simple Measure of Gobbledygook: 13.02 (about 25 year olds).
Coleman-Liau index: 13.98 (about 25 year olds).
This text should be understood in average by 31.25 year olds.

```