
# Content

You have been cast as the computer genius hero-of-the-day for the season finale of the show C.S.I.: P15 (coming this fall). Somewhat unsurprisingly,there is that camera feed that needs to be analyzed. The camera in question is recording pictures in HD-9000 quality with extra regression and the stream is then internally matched by a re-inverted isomorphic bit coefficient matrix, then plasma shifted five times for good measure. You then view the feed through Netscape Navigator 4 Platinum Edition. (Note that "internally" is just fancy talk for "inside the camera".)

![title](/source/lutece/c-s-i-p15/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vNzIwLzIwMTQwOTAxMTg1NDQzNjIzMzUucG5n.png)

Unfortunately, a saboteur turned on ASCII mode on the camera and set the camera in picture burst mode. So now all you have is a bunch of still ASCII images. And now,for reasons that will be revealed later in the show, you are to design and implement a deterministic algorithm for counting the number of flowers and birds in a given still image.
The pictures always include the ground,which will show up as a contiguous row of `=` characters. The ground will always be the bottom-most row of "ASCII pixels". There will never be anything else on that row (though, on one of the pictures taken before the sabotage there is a stray electron that a someone will accidentally find by zooming in too far, but that is for a later episode).

Air is marked in the feed as a `.` (a dot). The ground is the last line of the feed, and it looks like this: `===========`. A flower is defined as any $8$-connected component which consists of characters from the set { `|`, `/`, `\`, `-`, `@`}, and which is also connected to the ground. Two cells belong to the same $8$-connected component if there is a path between them that goes through elements from the forementioned set only, such that each step in the path is to an $8$-connected neighbour (horizontally, vertically, or diagonally adjacent cell). A bird is an occurence of `/\/\`, such that all neighbouring cells are either air or edges of the image. So if you see something that looks like a bird on the ground, it is a flower (possibly an ex-parrot, but that is also a flower for our purposes).


# Standard Input

The first line of the input consists of a single integer $T$, the number of test cases. Each of the following $T$ cases then begins with a line of two integers separated by a space,the height $H$ and width $W$, and ends with $H$ lines describing the picture. Each line of the picture has exactly $W$ characters. All lines but the last consist of only the following characters: { `.`, `|`, `/`, `\`, `-`, `@`}. The last line consists of `=` characters only.

$0 < T \le 100$

$0 < W \le 30$

$0 < H \le 30$

# Standard Output

For each test case, output two lines. If the number of flowers is $F$ and the number of birds is $B$, the output should read
``` 
Flowers: F
Birds: B
```

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
<tr><td>1
12 28
............................
............................
\@/.../\/\..../\/\..........
.|..........................
.|....\@/.........../\/\....
.|.....|.............|......
.|.....|.............|......
.|.....|..\@/....\@/.|......
.|.....|....\..../...|.|-|..
.|.....|.....\../....|.|.|..
.|.....|......\/.....|.|.|..
============================</td><td>Flowers: 5
Birds: 2</td></tr></table>


# Constraints



# Note



# Source


