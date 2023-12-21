Contributors : Lucas LALOUE, Julien CRIMOTEL

We predicted long-term (2 years) and short-term (20 days) electricity consumption using LSTM and GRU models.

We considered aggregated consumption data for the entire metropolitan France, excluding Corsica, from 2012 to 2022.
This data is available on the following website : https://odre.opendatasoft.com/explore/dataset/consommation-quotidienne-brute. 

We also considered additional variables to enhance our predictions. We created variables
to encode the day of the week and the month to improve the machine learning models. This
led to an improvement in the quality of predictions over the medium and long term forecasting, because models had information about the year period of the forecast. We also used
meteorological data from the SYNCOP network, available on this website : https://public.opendatasoft.com/explore/dataset/donnees-synop-essentielles-omm/api/.
