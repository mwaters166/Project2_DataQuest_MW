# Project2_DataQuest_MW
Project2: Hacker News

This DataQuest project involves working with a data set of submissions to popular technology site Hacker News:

"User-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result."

The original data set used for this project can be found here: https://www.kaggle.com/hacker-news/hacker-news-posts; the size of the dataset was reduced by removing all submissions that did not receive any comments, to ~80K rows. The columns of the dataset are as follows:
    -id: The unique identifier from Hacker News for the post
    -title: The title of the post
    -url: The URL that the posts links to, if it the post has a URL
    -num_points: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes
    -num_comments: The number of comments that were made on the post
    -author: The username of the person who submitted the post
    -created_at: The date and time at which the post was submitted

The goal of this project was to determine what kind of posts on Hacker News (HN) website get more comments. I evaluated posts that began with "Ask HN" (asking HN community a question) and posts that began with "Show HN" (post about a project, product, or object of interest) to understand A) which post type receives more comments on average and B) if posts created at certain times receive more comments on average. Project Notebook: https://github.com/mwaters166/Project2_DataQuest_MW/blob/master/Hacker_News_MW_2019.ipynb

Major Conclusions: A) On average, 'Ask HN' posts receive more comments (~14) than 'Show HN' posts (~10). B) Based on the results, to have a higher chance of receiving commnets on Hacker News, 'Ask HN' posts should be created at 3pm (15:00) Eastern Time. On average, posts created at this time received ~40 comments. 
