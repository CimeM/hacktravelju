# Smart flexy tickets

- Team: White Harbor

### Technical implementation

#### Machine learning and predicting time series data

Python worker that uses prediction algorythm that uses time series data for creating a forcast in sales in flight popularity.

This is a feature that relys on historical information of the flight relation. We did not find the data available through available APIs on tequila, so we uset google trends to see the trends within search results from google.
Kiwi could get this information by scraping internal databases.

Features used for algorithm:
- Historical data from kiwi.com (not available)
- Faire prices
- Frequency of searches for a specific relation

More research can reveal more information about the releavant features to be used to train the model.

##### ARMIA model

We used ARMIA model for time series forcasting together with python.
Research paper: https://journals.sagepub.com/doi/full/10.1177/1847979018808673

The code is published in ARMIA.py

Link to presentation:
https://readymag.com/u37053732/1409808/
Google sheets link:
https://docs.google.com/presentation/d/1ka1-Qax6-R7iEn3olsu9JyJbFzs0Z8QF3mb3AT2YCyY/edit?usp=sharing
