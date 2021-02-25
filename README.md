# crossfit-open
Scraping, cleaning, and analyzing 10 years of CrossFit Open Data.

# Introduction
The CrossFit Games is a once year worldwide fitness competition that aims to find the fittest man and woman on Earth. Though the process to qualify for the CrossFit Games has changed over the years, the Crossfit Open is generally considered the first step to qualify. The CrossFit Open consists of five workouts over five weeks, with each workout released weekly on Thursday and scores due on Monday. After five weeks, the top competitors move on to secondary stages to qualify, or in some years can directly qualify for the CrossFit Games out of the Open. What makes Open unique is that anybody can sign up to participate. There are different versions of eah workout offered for different age groups and skill levels to allow the competition to allow more people the ability to participate. All workouts are either judged or videoed and scores are entered on a worldwide leaderboard for everyone to see their placing.

The Open began in 2011, and I personally have participated each year since 2016. Though I am not an athlete at a CrossFit Games level, I enjoy seeing how my fitness improves from year to year with my Open workout scores as concrete data points that show me what skills I need to improve on to be a more competitive and better athlete. As the sport of CrossFit grows and the overall abilities and fitness levels of athletes rise, I thought it would be an interesting project to pull old Open leaderboard data and create a tool that helps any Crossfit Open participant analyze what they need to work on to improve their scores and their fitness.

# Part 1
crossfit_open_part_1.ipynb is the Jupyter notebook I used to scrape all the available CrossFit Open Leaderboard data. I have pulled all of the data through 2016 and will be pulling the 2015 data next.

# Part 2
crossfit_open_part_2.ipynb is the Jupyter notebook I used to load all the data into a PostgreSQL database to be more easily queried and integrated into future analyses and dashboards.

