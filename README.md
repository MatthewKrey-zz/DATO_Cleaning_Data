# Cleaning Data with Dato

Solid Saturday Stat Study with Dato & Python. I recently discovered
Dato after seeing one of their [Events](https://dato.com/events/) posted
on Twitter and have been enjoying learning more about how to use their
platform tools for rapid and powerful Machine Learning prototyping.

This repo reflects my open thoughts following along with one of the lessons
found in the [Dato Gallery](https://dato.com/learn/gallery/).

## Cleaning Messy Data

*https://dato.com/learn/gallery/notebooks/datas_messy_clean_it.html*

As we read in numerous blogs or in any conversation that you may have with
anyone that works with data regularly, it would be wonderful if all data came
to us in precisely the format we would like so we could immediately begin diving
into all of the super exciting analyses, visualizations, etc. that we love. But,
this is rarely the case and we need tools in our toolkit to help us with our
[data munging](https://en.wikipedia.org/wiki/Data_wrangling) tasks.


### Autotagger Tool

The GraphLab Create [autotagger](https://dato.com/learn/userguide/data_matching/autotagger.html) tool matches
unstructured text queries to a reference set of strings, a.k.a tags, which are known beforehand. Adding tags
to unstructured text gives readers a quick intuition about the content of the text as well as anchors for
quicker navigation and statistical summaries.

Autotagging is closely related to the task of searching for user-specified queries in unstructured text,
but it differs in that autotagging is typically done with a fixed set of tags, and treats the unstructured
documents as queries, rather than the tags.


### Composite Distance Function

*https://www.siam.org/meetings/sdm12/wang_sun_part1.pdf*


### Jaccard Distance
*https://www.youtube.com/watch?v=Vbdki_gnnYM*
*https://en.wikipedia.org/wiki/Jaccard_index*
*http://mathoverflow.net/questions/18084/is-the-jaccard-distance-a-distance*

### Levenshtein Distance

*https://en.wikipedia.org/wiki/Levenshtein_distance*

### Febrl (Freely extensible biomedical record linkage)

*http://datamining.anu.edu.au/projects/linkage.html*

Record or data linkage techniques are used to link together records which relate to the same entity
(e.g. patient, customer, household) in one or more data sets where a unique identifier for each
entity is not available in all or any of the data sets to be linked.

Record linkage is an important initial step in many research and data mining projects in the biomedical
and other sectors, where it is used to improve data quality and to assemble longitudinal or other data
sets which would not otherwise be available.

### _A Theory for Record Linkage_

*http://courses.cs.washington.edu/courses/cse590q/04au/papers/Felligi69.pdf*

1969 paper by Fellegi and Sunter describing implementation of "classical" approach to probabilistic
record linkage and a model for doing so. 
