# Assignment 1: Protests
The past few years in the United States, there has been a surge in protests in support of Black Lives Matter, gender equity, and other social issues. In this assignment, you'll work with data from [CountLove](https://countlove.org/) -- the same data often [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the New York Times -- to learn more about demonstrations over the past few years. 

By completing the assignment, you will demonstrate the following skills:

- Use of **version control** for managing your code
- Declaring document rendering using **markdown** syntax
- Foundational programming skills in R. 


## Background Research
Before diving into this (or any) dataset, it's important to have _domain familiarity_ (i.e., to know something about the topic). As preparation, I'm asking that you read **three articles** about protests in the U.S., and provide a brief 1 - 2 sentence summary or takeaway from each one. 

In the section below, create an **unordered list** of the three articles you found. Make sure to provide an appropriate markdown link (_not_ just the URL) to the article in addition to your 1 - 2 sentence summary.

-[The New York Times](https://www.nytimes.com/interactive/2020/07/03/us/george-floyd-protests-crowd-size.html) wrote an article in July about how the Black Lives Matter protests may be the largest protests in U.S. history. It gives some amazing visual data sets and delves into the who, what, why, where and when that bring to light a lot of surprising statistics.

-An article by [The Washington Post](https://www.washingtonpost.com/national/the-united-states-is-in-crisis-report-tracks-thousands-of-summer-protests-most-nonviolent/2020/09/03/b43c359a-edec-11ea-99a1-71343d03bc29_story.html) talks about how 93% of protests during the summer were non-violent. This contradicts a lot of the unfounded claims from GOP party leaders.

-[The BBC](https://www.bbc.com/news/world-us-canada-52951093) wrote a piece about protests over George Floyd's death across the Unite States. It gives a bit of an outside perspective on what the protests in the U.S. look like to other countries like the UK.

## Accompanying Image 
In this section, please **display one image** to accompany your text, and describe _why_ you included it (~2 - 3 sentences). This will require that you download an image into your project folder. In your description, use **bold** and _italics_ (at least once, for practice) to emphasize some of your points. 

![Protesters In Seattle, Washington](/Users/samsiamon/Desktop/a1-ssiamon05/5ed683b3281d7.image.jpg)

I feel like this image does a great job at emphasizing how **peaceful** these protests truly are. Protesters standing with their hands up, knowing full well that _armed_ officers are point weapons at them, throwing tear gas at them. It is abslolutely disgusting how hard it is to protest without getting hurt in this country.

## Analysis
At this point, you should open up your `analysis.R` script to begin working with the data. The script will guide you through an initial analysis of the data. Throughout the script, there are prompts labeled **Reflection**. Please write 1 - 2 sentences for each of these reflections below:

- What does the difference between the mean and the median tell you about the *distribution* of the data?

The difference between the mean and the median was fairly large, so that means that the distribution is skewed to the right and that there were a few protests that had a significant more number of attendees than the others.

- Does the number of protests in Washington surprise you? Why or why not?

This number did surprise me a little. I was expecting it to be bigger with how often I heard protests going down the Ave during the summer. But at the same time, this was a nation wide movement, so many protests were going on that even about  2% is a lot.

- Looking at the `state_table` variable, what data quality issues do you notice, and how would you use that to change your analysis (no need to actually change your analysis)?

I had noticed that sometimes the state abbreviations in state_table had mixed capitalization, splitting the states into two entries. I changed this by adding the toupper function to my states variable.

- Does the change in the number of protests from 2019 to 2020 surprise you? Why or why not?

This number honestly does not surprise me. With the amount of inequalities that have been put in the spotlight since 2020 started, it makes sense that double the amount of protests have taken place.

- Do a bit of research. Find at least *two specific policies* that have been changed as a result of protests in 2020. These may be at the city, state, or University level. Please provide a basic summary, as well as a link to each article.

[Business Insider](https://www.businessinsider.com/13-concrete-changes-sparked-by-george-floyd-protests-so-far-2020-6#officials-in-washington-dc-and-states-including-california-nevada-and-texas-have-also-banned-chokeholds-and-reviewed-police-reforms-6) talks about how many states have started making changed concerning their police, such as California, Nevada and Texas banning choke holds. This is not even close to enough, however, it is a step in the right direction.

[CNN](https://www.cnn.com/2020/06/13/us/changes-from-protests-george-floyd-trnd/index.html) wrote an article about race-related changed that have happened because of the protests. I feel that a very important one that they note on is the removal of monuments dedicated to confederates. This is long overdue, but I am happy to see it finally happening.

- Take a look (`View()`) your `high_level_table` variable. What picture does this paint of the U.S.?
Viewing my high level table did not give me a lot of information. I think I may have did it wrong. I would assume it paints a pretty sad picture about the injustices that are rampant throughout the U.S.

## Final Thoughts
When you are finished, with your analysis, please answer the following questions in 1-2 sentences each. 

- What about the analysis surprised you?

I was honestly surprised by the amount of protests there were. I knew there were a lot, but I was still blown away by the amount of protests there actually were.

- What parts of this analysis did you find challenging?

I found filtering my data frame with specific vectors like at the end of part 5 to be very hard.

- What types of analysis do you wish you were able to do with the dataset, but currently don't have the technical skills to do?

I wish I was able to create statistics based on each state, but I am not sure if I have the technical skills yet to do so.