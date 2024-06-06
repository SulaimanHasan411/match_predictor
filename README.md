A Random Forest Classifier Machine Learning model that uses scraped data of premier league games to predict if a team will win or lose their game. 

Webscraper uses Pandas, BeautifulSoup, and Requests to extract, format and clean the data to be used for Machine Learning. Data is scraped from fbref.com

Some pieces of data that are used to train the model include Venue, Day of week, Hour, and opponent. Additional data taken into account with rolling averages includes but is not limited to: Goal For (GF), Goals Against (GA), Shots taken (Sh), Shots on Target (SoT), Distance of shots (Dist), Free Kicks scored (FK), Penalty Kicks scored (PK), Penalty Kicks attempted (PKatt), Expected Goals (xG), Expected Goals Against (xGa)