# Require Environment:
pip install tweepy
pip install geopy
# Description
This is populatiry analysis based on twitter API. The official accounts of attractions in NYC are seleced to gather information such as likes, reweets, and number of favorites. Then tweets that have topic related these attractions are colleted to apply sentimental analysis. 

The whole process will take hours to finish since twitter API have limit requests in every 15 minutes. To keep the data up to date, once program start running, it will check if the last time the data was modified to decide if we need to update the data.
