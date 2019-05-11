# Smart flexy tickets

- Team: White Harbor

### Idea
The idea of our solution is to use machine learning to predict prices and confidence levels on ticket sales. Kiwi would purchase tickets in bulk and sell them when the prices get higher.

The insurance that kiwi tickets would get sold relies solely on data prediction. Because kiwi has resources on historical data for flights.

This way, we can offer customers a special insurance or "kiwinsurance" that offers them to get better returns if they cancel their flight.
The canceled ticket can be offered to other customers as a last-minute ticket. 

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
