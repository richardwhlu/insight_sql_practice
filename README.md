# Insight SQL Practice
Practice with a real database on real data.

Data Source: http://insideairbnb.com/get-the-data.html

## Overview
To help practice SQL querying on real data, this short notebook builds on the postgres setup files and adds in tables for airbnb data. As long as the columns are the same (which they should be, though I haven't checked), you should be able to read in any city data into the database with the same code, as long as you download three files from the website above:

- listings.csv (from listings.csv.gz)
- calendar.csv (from calendar.csv.gz)
- reviews.csv (from reviews.csv.gz)

All you need to do is download the data and adjust the file paths, as well as configure the password to your own postgres user password.
