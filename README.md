# Early-depression-detection
Coding done alongside research paper in NLP regarding early depression detection. Title of the work was **'Don’t worry, I am not depressed... Or am I?'**. 

The dataset used in this paper contains Reddit posts and comments from 892 different users. 137 users have been diagnosed with depression, and the rest are a control group.
The maximum number of data for each user is limited to
1000 posts and 1000 comments which is Reddit API limit,
and both the posts and the comments are sorted by chronological order, which is important given the task of early
depression detection. The collection was created as a sequence of XML files, one file per user. Users are labeled
as depressive only if they explicitly stated that they were
diagnosed with depression and undepressed users are also
from depression related subreddits but are not depressed,
i.e. someone around them is suffering from depression so
they want to explore it.

If you want to see how we processed the data, what features we extracted or you are just interested in results of the expiriment, conclusion and possible future work please refer to attached pdf file.
