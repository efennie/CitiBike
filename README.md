# Analysis Citi Bike

This project was designed to visualize citi bike data and identify trends within the data.

I chose to look at the data pertaining to the first six months of the COVID-19 pandemic. I was curious about ridership during the beginning of lockdown, which age groups were renting bikes, which genders were renting bikes, and how busy the start and stop stations were. 

To achieve this I created a jupyter notebook file and pulled in data from 6 csvs I downloaded from Citi Bike's website: https://www.citibikenyc.com/system-data then I combined them all into one big dataframe and exported them as a csv. 

Next I added the combined csv into tableau and created a map to visualize the popularity of each station. In this process I discovered that during February - August of 2020, the following stations were the most popular: Grove Street Path, Newport Parkway, and Liberty Light Rail. They were the top three most used both as starting stations and as ending stations. 

I was curious to see what ridership looked like each month during the first six months of COVID and found that we did see a steep drop in rides from February to April. There were about 22,000 riders in February, ~17,000 riders in March, and by April the numbers plummeted to around 9,000 riders. There was little that Citi Bike could have done to improve the ridership during those first few months aside from promises of some sort of hand sanitizers or wipes for the bike handlebars and seats. May saw better rider numbers that steadily climbed until August 2020 that saw ~43,000 riders. I would like to compare those numbers to August of 2019 and August of 2021 to see how normal that spike is. Anecdotally, we could say that there were some restless New Yorkers that by summertime needed some outdoor stress relief and sought out biking. It is also possible that few felt safe on public transit and felt more comfortable using bikes to get around.

I decided to compare gender and user types to look at average trip length and overall number of trips. What I found was interesting. The trend is that men took more frequent trips but on average took shorter trips than women. Comparison can't be made on the unknown gender category, but I advise that Citi Bikes adds an option for non-binary users and an option that says "prefer to not disclose". That way we can also look at how non-binary users are trending with bike data. 

Subscribers, those riders with a yearly subscription, seemed to take more trips than the passholders which we expect.

The next set of data I wanted to look at was the age of riders. I created a calculation field in tableau to subtract the user's birth year from 2020 to get an age for each rider. There are limitations with this approach, because it is unlikely that all riders had birthdays before they rode on the bikes so the age data could be a year short if their birthday hadn't passed yet. With this margin of error in mind, I took a look at user types and their ages. The distribution at first appears like a normal bell curve with 31 year olds as the median. As you scroll to the right however, we find that there is a huge peak in 51 year old users. It is possible that our 20/30 year old users are using the bikes for rides to work and the 51 year olds are using them for leisure, but this is just one possibility. 
