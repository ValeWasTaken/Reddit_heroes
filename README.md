# Reddit_heroes
Scrapes the reddit.com/r/overwatch subreddit every two hours, reading the last 200 comments posted to the channel. Then the script records all of the hero mentions (while accounting for hero nicknames such as people referring to "Roadhog" as "hog" and so forth.) These records are then kept in a text file and updated to add each set of new data every two hours indefinitely. (With the goal being to see which heroes are the most discussed on the subreddit.)
