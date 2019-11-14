
# Content

![title](/source/lutece/ferris-wheel-string/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTA2Mi8yMDE1MDQwOTE4MjAzMDQzODguanBn.jpg)

Have you ever been to London? 

Our Master Qiu will tell you how amazing in London and how funny a Ferris Wheel String is.

One day, while our Master Qiu was recovering Great Britain, he was thinking about an interesting problem about string. In front of him, a London Ferris Wheel was revolving. There were some seats on the large Ferris Wheel. However, in Master Qiu's mind, each seat was a lower-case letter so that the Ferris Wheel was a beautiful string that was revolving all the time. Let's call it `Ferris Wheel String`.

#####In the revolving operation, you can put several front letters to the last of the string. Of course, you can also put all the letters to the last, so you will get the string itself. For example, you can change string `abcd` into 4 strings, such as `bcda`, `cdab`, `dabc`, `abcd`. Obviously, in the revolving operation, a string of length $n$ can be changed into $n$ strings.

Master Qiu found out an interesting phenomenon that the Ferris Wheel String spent exactly one second revolving one letter. For example, at the beginning（0 second），the Ferris Wheel String was abcd，after one second，it became bcda ... and after four seconds, it became abcd.

#####Master Qiu is a Romantic guy. He thought after exactly $K$ second(s), the Ferris Wheel String became extremely beautiful.

Now, he would like to ask you a question: 

#####After exactly $K$ second(s), among the $n$ strings obtained by revolving a string of length $n$, how many `distinct` strings are lexicographically smaller than the beautiful string, how many `distinct` strings are lexicographically equal to the beautiful string and how many `distinct` strings are lexicographically bigger than the beautiful string ?

（If you really can not understand Master Qiu's mind, see examples and Hint）

# Standard Input

The first line contains a string of length $n（1 \leq n \leq 2 \cdot 10^5）$ and the second line contains an integer $k（1 \leq k \leq n）$. 

The string only contains lower-case letters.

# Standard Output

Output three integers separated by two spaces that are your answer to Master Qiu. Do not output anything after the last integer.

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
<tr><td>abcabc
1</td><td>1 1 1</td></tr><tr><td>aaaaaaa
3</td><td>0 1 0</td></tr><tr><td>himverihimverihimveri
18</td><td>0 1 6</td></tr><tr><td>lvhqsjtdgckrznjsbargcojiyuf
19</td><td>7 1 19</td></tr><tr><td>abbabaabbaababbabaababbaabbaba
29</td><td>3 1 26</td></tr></table>


# Constraints



# Note

#####Let's define that `<` means lexicographically smaller，`>` means lexicographically bigger and `=` means lexicographically equal.

#####Also, `ans1` means the number of strings < bcabca，`ans2` means the number of strings = bcabca and `ans3` means the number of strings > bacabca.

#####Explain for lexicography :
>#####Let's only consider lexicographical order between two strings when $|S|=|T|$.
>##### If $S<T$, there exits a position $p\ (0 \leq p < |S|)$ satisfying that $S_i=T_i$ when $0 \leq i < p$ but $S_p<T_p$.
>##### If $S>T$, there exits a position $p\ (0 \leq p < |S|)$ satisfying that $S_i=T_i$ when $0 \leq i < p$ but $S_p>T_p$.
>##### If $S=T$, then $S_i=T_i$ for all $i\ (0 \leq i <|S|)$
>##### And we all know that $a<b<c<$ $\cdots$ $<x<y<z$.


#####Explain for the first example :
>#####The Ferris Wheel String is abcabc and $K=1$ , so that the beautiful string is bcabca
>#####After 1 second, it becomes cabcab, cabcab>bcabca；ans3+=1；
>#####After 2 seconds, it becomes abcabc, abcabc<bcabca；ans1+=1；
>#####After 3 seconds, it becomes bcabca, bcabca=bcabca；ans2+=1;
>#####After 4 seconds, it becomes cabcab. But it has appeared. So, do not count it.
>#####After 5 seconds, it becomes abcabc. But it has appeared. So, do not count it.
>#####After 6 seconds, it becomes bcabca. But it has appeared. So, do not count it.
>#####Therefore, ans1=1, ans2=1 and ans3=1.

`Use double hash rather than single hash if you wanna hash.`

# Source


