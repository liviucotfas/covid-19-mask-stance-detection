# Overview
This repository contains the annotated dataset, the unigrams, bigrams and trigrams referenced in the paper **"Unmasking People’s Opinions behind Mask Wearing during COVID-19 Pandemic – a Twitter Stance Analysis"** submitted to the **Symmetry** journal.

The tweets have been collected over a one-year period, bewteen **January 9, 2020** and **January 8, 2021**, as described in our paper. **January 9, 2020** is the date when the **first tweet** to ever mention **mask wearing** in the context of the **COVID-19** pandemic has been published, marking the begining of the ongoing debate surrounding mask wearing.

> Note: The tweets have been minimally pre-processed before extracting the n-grams by removing stop words and duplicated white spaces.

Repository structure:
- dataset: contains a balanced dataset with 9426 tweets annotated in the categories "against" (-1), "neutral" (0) and "in favor" (1);
- n-grams-daily: daily unigrams, bigrams and trigrams extracted from the cleaned dataset (excludes retweets), sorted by the number of appearances;
- n-grams-monthly: monthly unigrams, bigrams and trigrams extracted from the cleaned dataset (excludes retweets), sorted by the number of appearances;
- n-grams-one-year: unigrams, bigrams and trigrams extracted from the cleaned dataset (excludes retweets) for the considered one-year period, sorted by the number of appearances;

# Usage
In accordance with the Twitter policy, in the annotated dataset, only the tweet ids have been provided. The tweets can be hydrated using a tool such as Twarc (https://github.com/DocNow/twarc) or Hydrator (https://github.com/DocNow/hydrator).
