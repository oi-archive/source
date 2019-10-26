
# Content

An adventurer is trapped in a chamber, and the only way he can escape is a door with a special lock. The lock is a seiries of combined rotatable disks with some characters on them. The picture below is an example of a lock with $4$ disks. The door will open if the character sequence on the lock forms the correct password. Fortunately, the adventurer finds the password, but he is not always so lucky. The chamber seems to collapse in a while, so he must get out as quick as possible. Every second he can rotate one disk and swap the two characters on it. The adventurer wants to know what's the minimum time before he leaves this place.

![.*](/source/lutece/escape-from-the-chamber/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vOTgvMjAxNDAxMjgxNjQwMDU4MDgxLnBuZw==.png)

# Standard Input

One integer $T$ on the first line indicates the number of cases.
Then followed by $T$ cases.
Every case contains two strings of lowercase characters with the same $length$($length\leq 10000$).The first string 

is the initial character sequence on the lock,and the second string is the password.

It's guaranteed that there is always a solution to form the password.

# Standard Output

For each case, print an integer on a line indicating the minimum time to escape from the chamber.

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
abcde
acbde
aaaaaab
baaaaaa</td><td>1
6</td></tr></table>


# Constraints



# Note



# Source


