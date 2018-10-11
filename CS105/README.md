## Overview
This repository includes the tutorials I completed while taking BerkeleyX CS105x
 - Introduction to Apache Spark at edX. Personal notes and highlights are
 included. Note that since results cannot be displayed in the correct format at
 github interface, the results have been removed for readability.

## Table of contents
#### (1a) Spark tutorial
The following transformations are covered:
* select(), filter(), distinct(), dropDuplicates(), orderBy(), groupBy()  

The following actions are covered:
* first(), take(), count(), collect(), show()

Also covered:
* cache(), unpersist()

#### (1b) Word count lab: building a word count application  
Transformations employed:
* select(), where(), orderBy(), groupby()

Actions employed:
* show(), count(), mean(), head()

Also employed:
* Data transformation and cleaning using regexp_replace(), trim() and lower()  

The code could also be scaled to larger applications, such as finding the most
 common words in Wikipedia.

## Requirements
[Databricks Community Edition](https://community.cloud.databricks.com/) is required to run these Apache Spark notebooks.
