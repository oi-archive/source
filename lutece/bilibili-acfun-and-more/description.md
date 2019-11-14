
# Content

Some of you may have already noticed, there is a team in our final contest whose name is `UESTC_BiliBilii`, with user id as `ACfun`. Actually, both of them are websites mainly for watching videos.

So in this problem we also deal with video-share websites. When watching videos online, two numbers are very important. One is the playing speed: the speed you play the video, say $X$ KB per second. The other is the downloading speed: the speed the computer downloads the video from the internet, say $Y$ KB per second. Obviously, if $X>Y$, then you may have to pause for some time, since you cannot play something that hasn’t been downloaded!

The playing speed can also be described as the moving speed of the circle at the bottom of the videos, see the pictures below.

![201305171505582061.jpg](/source/lutece/bilibili-acfun-and-more/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMy8yMDEzMTIyODIwMTAxMTExOTEuanBn.jpg)

The circle will move along the blue bar, which is full now, indicating that downloading is already complete.

In this problem, we suppose that $X$ and $Y$ will always be constant.

Kennethsnow has a special habit when watching videos, let me tell you.
First of all, he will wait for some time to download part of the video, say $T$ seconds.
Then, he starts to play the video.

If at a certain time, the video is paused, then kennethsnow will move the cursor(The circle in the picture) instantly to the leftmost position! That means, he will watch the video again, from the very beginning.

He will do this again and again, until the video comes to an end.
Given $X$, $Y$, $T$, and the total size of the video, what is the time kennethsnow needs, to finish his watching?

# Standard Input

The first line of input contains a number $T$, indicating the number of test cases. ($T\leq 1000$).For each case, there will be four integers $X$, $Y$, $T$ and $S$, which is the playing speed, downloading speed, the time kennethsnow will wait before playing, and the total size of video, given in KB. ($1\leq X,Y,T\leq 20$, $1\leq S\leq 100$).

# Standard Output

For each case, output `Case #i: ` first. ($i$ is the number of the test case, from $1$ to $T$). Then output the time kennethsnow needs to finish watching, in decimals, round to $3$ decimal places.

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
<tr><td>3
1 1 2 10
2 1 3 20
3 1 4 30</td><td>Case #1: 10.000
Case #2: 19.000
Case #3: 26.250</td></tr></table>


# Constraints



# Note



# Source


