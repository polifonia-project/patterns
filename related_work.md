# Related work

This document lists work related to pattern extraction, pattern mining and pattern analysis in music data. It is separated in three subtopic: Music representation for pattern analysis in music data, pattern mining techniques for music data, and pattern assessement metrics for music data. Naturally, some works will fall into multiple categories.

There are, or course, several surveys, workshops and other collections that provide sources of multiple elements that are mentioned here. Those include:
* The PhD Thesis of Berit Janssen, especially chapter 3: https://pure.uva.nl/ws/files/21009127/Thesis.pdf
* the Tunes and Tales workshop: http://tunes-and-tales.github.io/TTT/  

## Music representation for pattern analysis

Even if we focus, in this work, on symbolic music representaton, some pre-processing is generally required to repesent music data in a form that is suitable for pattern mining. In most cases, this will require simplifications that will lead to focusing on certain types of patterns. In the descriptions of the possible representation below, references to works having used them as well as to the kind of patterns they enable are included.

### Vector of note pitch

### Vector of note intervals

### Vector of note pitch class

### Vector of note duration

### Vector of note events

### Parson's representation 

### Melodic shapes

### ABC 

While ABC is a format which includes all information, in theory, to represent a tune or piece of music, since it represents this as a string, it can be used for pattern mining or more general data processing methods. For example, in [1], the ABC notation is used directly with a language model for music generation. 

## Pattern mining techniques for music data

Below is a list of techniques which have been found in various works to be used for extracting patterns from symbolic music data. For each techniques, references to the work using them as well as to the types of patterns they enable is included. 

### Sequence mining

### N-Grams

### Language models

The similarity between music and language, and therefore the possibility to use language models for music analysis has been considered multiple times. Due to their popularity, the idea of using neural language models in particular has led to multiple works. In [1], for example, GPT-2 is used to generate music in the ABC notation. 

## Pattern assessment metrics

Below we list possible metrics to be used to assess the found patterns. Some pattern mining techniques can come up with very large number of patterns and ideally, metrics should be used to rank or select them in a way that is musically relevant. As above, the description of each metrics is made with reference to the works that used them. 

### Frequency

This is the most comment metrics used. Also called support.

### TF-IDF

When looking at patterns in specific pieces of music, as they appear in a broader collection.

### Similarity 

Similarity of music generated using patterns can be considered a possible way of evaluate patterns, as for example done in [1]. 

## Reference

[1] https://www.aclweb.org/anthology/2020.nlp4musa-1.10.pdf
