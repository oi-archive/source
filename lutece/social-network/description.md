
# Content

<p class="text-right"><i>In case of fire, exit building before tweeting about it.</i></p>

Nobody is surprised nowadays hearing a story about someone writing to a blog or a social network about an accident before calling the rescue service. Knowing this attachment to internet technologies, the Japanese authorities suggest people to use Twitter to alert their friends and relatives about an earthquake. Indeed, since the propagation velocity of seismic waves is no more than five kilometers per second, people who are far enough from the epicenter will be able to read about the earthquake several seconds before the wave hits them. These seconds may become crucial for some of them…

Each Twitter user has a list of followers. A tweet (message) of a user is seen by all of his followers. Each of them can retweet this tweet. As a result, it will become available to all their followers. These followers can in turn retweet the retweet, and so on… Retweet gets the string `«RT @nick: »` appended to its beginning, where nick is the name of the user whose tweet (or retweet) is retweeted. Since the length of a tweet must not exceed 140 symbols, any retweet violating this restriction will not be sent.

The Japanese Fire and Disaster Management Agency wants to test the idea of Twitter alerts by conducting an experiment. They have chosen a group of people and want to calculate how many of them will learn about an earthquake, if only person will be notified of it.

# Standard Input

There are many test cases in this problem,ended by EOF.

Every test case, The first line contains the number $n$ of Twitter users chosen for the experiment ($2\leq n \leq 100$). 

In order to make the problem much easier,the next $n$ lines, the $i+1$ line desribe the information for the $i\_{th}$ user, each line contains information as showed below.
```
name_length number_of_followers followers_list
```

`name_length` is the length of the $i\_{th}$ user's name, 0number_of_followers is the number of followers in the user's follower list, then list the followers list for the user.

The last line contains a tweet about an earthquake sent by the user whose name is the first in the input. It means that the tweet is sent by the user whose ID is $1$. The tweet is a nonempty string consisting of symbols with ASCII codes in the range from $32$ to $127$; the length of the string is at most $140$ symbols.

# Standard Output

In the first line output the number of users who will learn about the earthquake. Then output their names in increasing order of their ID, one name per line.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>5
6 1 2
3 1 3
4 2 1 2
6 1 5
4 1 4
Hidamari is going to collapse!!!</td><td>3
1
2
3</td></tr></table>


# Constraints



# Note



# Source


