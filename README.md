# Playtomic-Sniping-Bot

![Padelbot](logo.jpg)

This bot detects available time slots on Playtomic and notifies the user via email when matching slots are found. You can configure filter criteria to search for specific times, durations, and preferred courts. The bot can be run either locally or through GitHub Actions.

Important considerations for usage:

- Enter the required data in the config file if the bot is to be run locally.
- Store the necessary secrets in GitHub if the bot is to run via GitHub Actions.
- The bot is set to German by default, so make sure to adjust the email notification language if necessary.
- Customize the Playtomic booking URL for your club in the @main.py file.
- Set the filter criteria by defining parameters like start_time, days, court_names, and min_duration.
