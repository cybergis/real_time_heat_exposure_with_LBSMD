# Mapping Dynamic Human Sentiments of Heat Exposure with Location-Based Social Media Data

This github repo is attached to the manuscript Mapping Dynamic Human Sentiments of Heat Exposure with Location-Based Social Media Data. The code can be directly run on the platform CyberGISX at https://cybergisxhub.cigi.illinois.edu/ with confidential. This study aims to explore the possibility to used location-based social media data to map people’s exposure to heat by analyzing real-time social media Twitter.

How to Use this code on CyberGISX?

1. Generate a ssh key by: ssh-keygen

2. Retrieve your ssh key and send it to email flu8@illinois.edu

3. Authorized used will be given the permission to retrive Twitter data on Keeling

4. Clone this repo to CyberGISX

5. Use the notebook provided for real-time analysis of your own/reproduce the result in the manuscript

Notebook description:

1. Chicago_HE_Twitter.ipny -> Used to generate city level heat exposure with real-time twitter data

2. National_HE_Twitter.ipny -> Used to generate national-level heat exposure with real-time twitter data

3. data_collection.ipny -> Use API to retrieve United State Census Bureau ACS data for socioeconomic data

4. analysis.ipny -> post-analysis of national scale heat exposure map

Folder description:

1. Census_track -> Chicago Census Track level shapefile

2. data_explore -> Notebook for prelimery exploration of twiiter data

3. geo/data20000.txt -> heat dictionary

4. geo -> chicago border shapefile

5. output_2021091312 -> the output in the case study in the manuscript, reproduce this with exact same date & time

6. US -> US county shapefile
