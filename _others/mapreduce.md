---
title: "MapReduce"
collection: others
permalink: /others/mapreduce
---
## About the project
  The project investigated the scalability efficiency of the two popular words co-occurrence algorithms: “pairs” and “stripes”. The project was an implementation of MapReduce in Java.

## Goal
  The project compared the two words co-occurrence algorithms: “pairs” and “stripes” in term of the time efficiency. The purpose of the project was to determine which approach is better for scaling.

## Data
  The project used the Common Crawl dataset, made available by Amazon S3.

## Methodology
  The algorithms were tested against variables including: data size, number of mappers, number of reducers and number of slave nodes.
  The context of co-occurrence is the closest 2 words in the same sentence.
## Outcomes
  Overall,the “stripe” approach performs better than the “pairs” approach in all the testing environments.
## What I've learned from this project
  1. Choosing the best algorithm

      In order to maximise time efficiency and minimise running cost, we are required to understand not only which algorithm is better, but also how each algorithm thrives in practical context.
  2. Working with AWS

      The best way to learn a new tool is do emerge yourself in the practical environment and be curious. In addition, the learning process benefits from making lots small mistakes, then recover/learn from those errors quickly.

You can [download the R markdown report](https://minhphan88.github.io/assets/mapreducereport.pdf) here
You can [download the code](https://minhphan88.github.io/) here

The project demonstrates the ability to work tools including
  1. A complete MapReduce implementation in Java with some components of Natural Language Processing.
  2. Amazon EMR Management.
  3. *Amazon S3 bucket, Eclipse,Apache Hadoop, Maven*.
