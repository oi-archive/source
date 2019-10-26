
# Content

Do you know a software called "WeiXin", a kind of chatting tool? There is an application called "Shaking for a while". Once you shake your cellphone, you can find those who shake their cellphone at same time.

One day when Tom was shaking his cellphone, he thought about a problem: how large the friends group would be if everyone made friends once they find others who shake cellphone at same time and combine their friends group?

We assume all the people are lonely and have no friends at the beginning. In other word, their friends group only contains themselves.

# Standard Input

First line contains an integer $T$ ($0 < T \leq 10$), indicate there are $T$ cases.

For each case, the first line contains an integer $N$ ($0 < N \leq 1000$), indicate the number of people who would shake their cellphone.

Then follows $N$ lines. Every line comes with an integer $K\_i$ ($0 \leq K\_i \leq 1440$), indicate the $i\_{th}$ person shakes cellphone $K$ times a day. Then follows $K\_i$ strings shown as `HH:MM`, indicate the time the $i\_{th}$ person shakes cellphone.

# Standard Output

For each test case, the first line contains an integer $X$ indicate how many friends group amount the people; the second line comes $X$ integers in nondescending order, indicate the scale of each friends group.

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
4
3 00:00 00:01 00:02
2 00:01 00:03
1 00:03
1 00:04</td><td>2
1 3</td></tr></table>


# Constraints



# Note



# Source


