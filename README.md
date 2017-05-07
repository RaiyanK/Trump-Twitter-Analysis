## Motivation behind the project

To determine the influence Donald Trump's rhetoric has had on the popularity and the messaging of hate groups within the U.S. We focus on Trump's Twitter activity to investigate any similarities between his Twitter feed and those of various domestic hate groups or individual extremists. We think that Trump's rhetoric has changed vastly over the last decade. Considering his shift in tone, we are interested in exploring the evolution of hate speech during this time period. 

We predict that since the beginning of Trump's presidential campaign, and continuing into his presidency, the Twitter activity of hate groups has increased and may even reflect Trump's Twitter activity. 

Based on this, our main research question is: Is Trump's Twitter activity associated with the Twitter activity of hate groups? 

We begin with some text analysis of Trump's tweets using methods such as n_grams and word correlations. We then move on to comparing his Tweets to other extremist groups using methods such as topic modelling. 


## Data 

We obtained data from the Trump Twitter Archive (http://www.trumptwitterarchive.com/). This source compiled Trump's Twitter activity into a dataset that includes information on the date he tweeted, the text he tweeted, and retweet counts. We use Trump's tweets from 2009 to present day.

We also used the Southern Poverty Law Center to gather a list of individuals who have been identified as extremist. They range from being white Nationalist to anti-Islamic or anti-Semitic. We identified their twitter handles, or their affiliated organization's twitter handles, and scraped 1500 of the most recent tweets. 

The final data set, for Trumps tweets, has approximately 30,866 observations, and the hate group data set comprises of a total of 75 individuals and groups and 62,252 observations


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/RaiyanK/tweets-cmrr.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
