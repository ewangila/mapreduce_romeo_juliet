# MapReduce 

A collection of Python scripts demonstrating foundational data processing and MapReduce concepts using the `mrjob` library. This repository explores distributed processing techniques to extract insights from text data.

## What's Inside?

This repo contains various MapReduce jobs, including:
* **Word Frequency Counters:** Maps and reduces text to find basic word frequencies while stripping punctuation.
* **Top N Word Finders:** Multi-step jobs that filter out common stop words (e.g., 'the', 'and') and return the top 5 or 10 most frequently used words.
* **Song Play Aggregator:** Maps streamed lines and reduces them to count total plays per song.
* **Targeted Word Tracker:** A specialized job to track specific entity mentions (like counting 'Romeo' and 'Juliet' in a text).
* **Max Value Finder:** Uses a multi-step MapReduce pipeline to identify the absolute most frequent item in a dataset.

## Tech Stack

* **Language:** Python
* **Framework:** `mrjob` (MapReduce for Python)
* **Concepts:** Big Data processing, Mapper/Reducer logic, Data pipelines

