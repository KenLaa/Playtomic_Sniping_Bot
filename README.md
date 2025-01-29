# Playtomic-Sniping-Bot

![Padelbot](logo.jpg)

A bot that specifically recognizes free slots in Playtomic and draws the user's attention to them by e-mail. Filter criteria can be used to configure the times and duration searched for as well as preferred courts. Can be operated both locally and via GitHub Actions. 

The following must be considered in order to use it:
- Write the necessary data in the config file (if the bot is to be operated locally)
- Store the necessary secrets in Github (if the bot is to run in GitHub Actions)
- The bot is in German by default, so adjust the mail notification in the language of your choice if necessary. 
- Customize the Playtomic-Booking URL of your club (@main.py).
- Set the filter criteria by setting parameters for start_time, days, court_names and min_duration. 
