Basketball Reference and NBA.com use different characters for certain names, especially with European players, so joining on name does not work very well.
This code uses the fuzzywuzzy package combined with matching stats to best join together the two tables. It works pretty well. 
It can be applied to any time you need tracking data from nba.com while also using bbref for salaries, positions, BPM, etc.
