
# Content

IELTS is around the corner! love8909 has registered for the exam, but he still hasn’t got prepared. Now he decides to take actions. But when he takes out the New Oriental IELTS Vocabulary, he finds there are so many words. But love8909 doesn’t get scared, because he has got a special skill. If he can make a list with some meaningful words, he will quickly remember these words and will not forget them. If the last letter of some word Wa is the same as the first letter of some word Wb, then you can connect these two words and make a list of two words. If you can connect a word to a list, you will make a longer list.

While love8909 is making the list, he finds that some words are still meaningful words if you reverse them. For example, if you reverse the word `pat`, you will get another meaningful word `tap`.

After scanning the vocabulary, love8909 has found there are $N$ words, some of them are meaningful if reversed, while others are not. Now he wonders whether he can remember all these words using his special skill.

The N-word list must contain every word once and only once.

# Standard Input

An integer $T$ ($T\leq 50$) comes on the first line, indicating the number of test cases.

On the first line of each test cases is an integer $N$ ($N\leq 1000$), telling you that there are $N$ words that love8909 wants to remember. Then comes $N$ lines. Each of the following $N$ lines has this format: word type. Word will be a string with only `a`~`z`, and type will be $0$(not meaningful when reversed) or $1$(meaningful when reversed). The length of each word is guaranteed to be less than $20$.

# Standard Output

The format of the output is like `Case t: s`, $t$ is the number of the test cases, starting from $1$, and s is a string.
For each test case, if love8909 can remember all the words, s will be `Well done!`, otherwise it’s `Poor boy!`

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
6
aloha 0
arachnid 0
dog 0
gopher 0
tar 1
tiger 0
3
thee 1
earn 0
nothing 0
2
pat 1
acm 0</td><td>Case 1: Well done!
Case 2: Well done!
Case 3: Poor boy!</td></tr></table>


# Constraints



# Note

In the first case, the word `tar` is still meaningful when reversed, and love8909 can make a list as `aloha-arachnid-dog-gopher-rat-tiger`. In the second case, the word `thee` is still meaningful when reversed, and love8909 can make a list as `thee-earn-nothing`. In the third case, no lists can be created.

# Source


