# About

This is a Python Script that when provided with a bunch of iOS/iPadOS/watchOS Analytics Files, parses them and returns your iDevice's Battery Stats.

This script is directly inspired by the Battery Stats Shortcut provided by Payette Forward. 

The original shortcut can be found at the following URL:
https://www.payetteforward.com/shortcut-check-your-iphones-battery-cycle-count/

When the Analytics file becomes too big (typically in betas), the shortcut times out and doesn't return the battery stats. Hence, this python script.

# Usage:
The Notebook will create 2 folders "iDevice Analytics" and "Battery Stats" next to the notebook.

Drop your Analytics Files into the folder "iDevice Analytics".

The Analytics Files can be found at Settings/Privacy & Security/Analytics & Improvements/Analytics Data.

There will be a bunch of files there. The ones you'll need are of the format "Analytics-YYYY-MM-DD-TTTTTT.ips.ca.synced".

Click on the file and once it opens, click on the sharesheet icon located at the top-right corner and once in the sharesheet, Airdrop to your Mac and then in Finder, move the Analytics file to "iDevice Analytics"

Once you run the script, your battery stats will be saved in the folder "Battery Stats" as a txt file.
