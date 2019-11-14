
# Content

Usually people don’t recognize what they really talk about when they make a talk, and that’s why we want to help them to explore their mind. After a long-period research, we find that what people talk about can be mainly captured by what they say the most times. We call such contents the core of dialogues. For example, Alice and Bob are lovers and here is their dialogue when they’re having a lunch:

Alice: It's nice to eat such pine mushroom with you, honey.

Bob: Yes, the mushrooms are as delicious as your lips.

According to our research, Alice and Bob were actually talking about mushroom. That is to say, the core of their talk is “mushroom”.

And that’s what you see here. Our research is based on such a topic: what we talk about when we talk about love.

In order to make it further, we need you, the most intelligent programmer, to do a favor. We require you to count the maximum number of times that a string occurs in a dialogue. Due to the demands of our research, you just need to focus on the strings which contain at least $5$ characters.

Please note that the core might be a substring of a word. When you’re counting the times of occurring for each potential core, you should not count it twice if the strings are overlapped. For example, considering the virtual word `mushroomushroom`, the substring `mushroom` appears only once, but `ushroom`or `mushroo`appears twice.

Besides, you should ignore the difference between uppercase letters and lowercase letters. Not surprisingly, `Mushroom` has the same meaning as `mushroom`.

# Standard Input

The first line of input is a single integer $T$, indicating the amount of dialogues.

For each test case, the first line is a single integer $N$, indicating there are $N$ words in this dialogue. The following lines contain $N$ words totally. Each word either contains only alphabet letters or contains alphabet letters and ends with a `:`. If a word ends with a `:`, it is just to mark the speaker of the dialogue and you should ignore such words. Between any two words there may be several blanks or newlines.

You may assume that the length of each word is no more than $50$, and the total length of all words in the input file will be no more than $5\times 10^5$. $T$ is no more than $1500$.

# Standard Output

For each test case, if you find the core, output the times that it occurs. Otherwise,output `Not Found` instead.

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
<tr><td>2
22
Alice:Itis nice to eat such pine mushroom with youhoney
Bob:Yes the mushrooms are asdelicious as your lips
6
Tom: ILoVe
YoUIsabella: HeHe</td><td>2
Not Found</td></tr></table>


# Constraints



# Note

In case $1$, `mushroom`, `mushroo`, `ushroom`, `mushro`, `ushroo`, `shroom`, `mushr`, `ushro`, `shroo`, `hroom` are all the cores, because they all appear twice. The substring `ou`appeared $3$ times, it doesn’t count because its length is less than $5$. So the answer is $2$.

In case $2$, the length of all the words (except the name of the speaker)is less than $5$, and thus there’re no cores here.

# Source


