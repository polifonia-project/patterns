# Datasets and collections

This document provides descriptions of datasets and collections that are or could be used for experiments in pattern extration, mining or analysis. We focus here on symbolic music datasets, i.e. datasets that correspond to collection of tunes, scores or songs that are represented as events (notes, chords, etc.) and features, rather than through an audio representation of their performance. For each dataset, a short description is provided according to the template below, including the tradition represented by the collection as well as reference of other works having used the collection and to experiments that rely on it.

Note that broader lists of datasets are being collected in the project including in:
* https://liveunibo.sharepoint.com/:x:/r/sites/polifonia/_layouts/15/Doc.aspx?sourcedoc=%7B1E4A099A-FB40-4B37-BC02-87A9C3438090%7D&file=MusicDatasets.xlsx&action=default&mobileredirect=true
* https://musow.kmi.open.ac.uk/resources-subject#Symbolic-div 

## Dataset description template

**Link:** Link to the dataset

**Format:** Format of the data in the datasets (e.g. Midi, ABC, Music XML)

**Tradition(s):** Music tradition represented by the dataset (e.g. Dutch folk, Jazz)

**Size:** In number of pieces

**Description:** A short description of the dataset

**Used in related work:** A short description of existing work using the dataset (long descriptions might be found in the related work document)

**Used in experiements:** A description and reference to experiments using the dataset for pattern analysis in Polifonia



## MTC-ANN 2.0

**Link:** TBC

**Format:** *kern

**Tradition(s):** Dutch Folk Songs

**Size:** 360 digitized vocal folk songs

**Description:** The pre-existing data set MTC-ANN 2.0, which is part of
the Meertens Tune Collections (MTC), contains 360 digitized vocal folk songs in
26 tune families from Dutch oral tradition, made available
in symbolic encoding (*kern). These songs have been collected through ethnological field work in the Netherlands
and from written sources such as song books. The collection specialists at the Meertens Instituut grouped the songs
into tune families based on melodic similarity.
The small sample of 360 songs in 26 tune families has
carefully been selected from a larger collection of thousands of songs. The sample is claimed to be representative
for the larger collection concerning the kinds of variety that
occur among variants of a tune family. MTC-ANN 2.0 is provided with several
sets of human annotations including a tune family label for
each melody, but also 1,657 motif occurrences in 102 motif
classes. Each of these motif classes represents an abstract
melodic motif that has a number of concrete occurrences
in songs within a tune family. These motifs are considered characteristic for the tune family in which they occur
by the expert annotators. Therefore, we would expect an
algorithmic pattern discovery method to find patterns that
correspond to some of these annotated motifs.

**Used in related work:** https://arrow.tudublin.ie/cgi/viewcontent.cgi?article=1016&context=fema

**Used in experiements:** TBC



## Weimar Jazz Database (WJazzD) 

**Link:** https://jazzomat.hfm-weimar.de/dbformat/dbcontent.html

**Format:** lots of metadata, scores, midi and csv

**Tradition(s):** Jazz

**Size:** 456

**Description:** a comprehensive and representative database of jazz solo transcription.

**Used in related work:** Jazz pattern http://dig-that-lick.eecs.qmul.ac.uk/

**Used in experiements:** TBC


## Schubert Winterreise Dataset

**Link:** https://zenodo.org/record/4431535#.YNMp9HVKhH4

**Format:** many, including midi and musicxml

**Tradition(s):** Classical

**Size:** 24

**Description:** The Schubert Winterreise Dataset (SWD) is a multimodal dataset comprising various representations and annotations of Franz Schubert's 24-song cycle Winterreise. The primary material (raw data) consists of textual representations of the songs' lyrics, music scores in image, symbolic, and MIDI format, as well as nine audio recordings of performances (only two included due to copyright issues). The secondary material (annotations) comprises information of musical measure positions in sheet music images and audio recordings as well as analyses of chords, local keys, global keys, and structural parts. 

**Used in related work:** TBC

**Used in experiements:** TBC

