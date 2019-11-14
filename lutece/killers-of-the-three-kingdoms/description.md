
# Content

`Killers of the three kingdoms` is a very popular game. However wangkun is always impatient with games, so he decides to write a program to play it, which can not only satisfy his needs to the game, but also save lots of grief. In order to simplify the game, we set several rules.

There are total $4$ people involved in the game: `Master`(主公), `Rebel`(反贼), `Duplicity`(内奸) and `Loyalist`(忠臣). For simplicity, anybody’s role is known by everybody.

There are $3$ kinds of cards: `Miss`(闪), `Kill`(杀) and `All Out of None`(无中生有).

`Miss`: You can discard `Miss` to avoid the hurt which caused by the `Kill` cark played on you.

`Kill`: You can discard `Kill` to hurt the one you want to kill, and his blood will drop by one point.

`All Out of None`: You can draw two more cards by discarding this one. There is no limit on distance and everybody could be killed.

The rule is, starting from a specific place, everyone draws two cards in order. If anyone draws the `All Out of None` card, he draws another two cards immediately. After everybody finishes drawing, they start to play.

For everyone, `Kill` is always optimum to be played, but during every round, the `Kill` card can only be played once(Except for `Zhang Fei`). If `Kill` is played on somebody, he must use the `Miss` card if he has it; but if he does not has the `Miss` card, his blood will drop by one point.

If somebody could not discard any card anymore, the number of his cards can notbe more than the points of his blood.

The priority of abandoning card is that we choose to abandon `Kill` first, then `Miss`. The cards that have been abandoned could not be used again. Then let me tell you the logic of each character in the game.

`Master`: If the `Rebel` is alive, `Master` will kill `Rebel` first,or he will kill `Duplicity`.

`Loyalist`: If “Rebel” and `Duplicity` are all alive, then he will kill the one whose blood’s points is lower. If the points of the blood of `Rebel` and `Duplicity` are the same, `Loyalist` will kill `Rebel`. If just one of the `Rebel` and `Duplicity` is alive, `Loyalist` will kill the one who is still alive.

` Duplicity`: If `Rebel` and `Loyalist` are all alive, then he will kill the one whose blood’s point is higher. If the points of the blood of `Rebel` and `Loyalist` are the same, `Duplicity` will kill `Loyalist`. If just one of the `Rebel` and `Loyalist` is alive, `Duplicity` will kill the one who is still alive. If `Rebel` and `Loyalist` are all dead, `Duplicity` will kill `Master`.

`Rebel`: Only kill `Master`.

Please let me introduce the military commanders in the game: `Zhao Yun`, `Zhang Fei`, `Lv Bu` and `Liu Chan`.

`Zhao Yun`: `Miss` can be used as `Kill` and `Kill` can be used as `Miss`, but when it comes to abondaning cards ,he still has to abandon the `Kill` first, then he can abandon `Missed`. He has at most $4$ points of blood.

`Zhang Fei`: He can use as many `Kill` as he wants during a round. He has at most $4$ points of blood.

`Lv Bu`: If `Lv Bu` discard the `Kill` card on somebody, this person has to use two `Miss` cards to avoid the hurt. `Lv Bu` has at most $4$ points of blood.

`Liu Shan`: At the beginning of every round, he will be judged if he is `Drown in Happiness` (The meaning of the `Drown in Happiness` is that before `Liu Shan` draws any card, we need to check the first card on the card piles, which is called Judge Card and has to be abandoned after checked, is `Miss`, he will be able to draw and discard cards normally. Otherwise, he can only draw cards and can not discard any card on anyone but has to abandon when his cards in hands exceed his blood points, he abandons according to the abandoning rule.) When a `Kill` card is played on `Liu Shan`, he will be judged. `Liu Shan` will not get hurt if the Judge Card is `Miss`, and the one who discards the `Kill` will lose one point of blood, and hurt can not be avoided. `Liu Shan` has at most $5$ points of blood. There is a special situation: when `Lv Bu` discards `Kill` on `Liu Shan`, there has to be two Judge Cards and both have to be `Miss`, then `Liu Shan` could stay safe and `Lv Bu` drops one point of blood, or `Liu Shan` could only use two `Miss` cards to avoid the hurt or lose one of his blood.

If any one of following situation happens, the game will end. When `Master` dies, the game ends.

When only `Master` and `Loyalist` are alive, the game ends. When there is only one person alive, the game ends.

The data will make sure the game ends before there is no more card to draw. Please forget the original game, and if you kill the `Rebel`,you can not get more cards.

# Standard Input

The first line of the input is an integer $T$, which represents that there are $T$ test cases.

The first line of each case is an integer $N$, which represents the total number of cards.$(2 \leq N \leq 100)$

The second line of each case contains $N$ consecutive letters, $K$ represents `Kill`, $R$ represents `Missed` and $L$ represents `All Out of None`. The order to draw the cards is from the first letter to the last one.

The third line of each case contains $4$ strings, which means who are the persons from NO.$1$ to NO.$4$. The input could be any order of the $4$ strings: master, loyalist, rebel and duplicity.

The forth line of each case contains $4$ strings, which represents the military names from NO.$1$ to NO.$4$. The input could be any order of the $4$ strings: zhaoyun, zhangfei, lvbu and liushan. The points of everybody’s blood is maximum.

The fifth line of each case contains $4$ integers, which respectively represents the point of blood of each person at present.$(0 \leq x \leq 5)$

The sixth line of each case contains $4$ strings, which are the cards of each person from NO.$1$ to NO.$4$ at present.The string could be one of `Miss`, `Kill`, `All Out of None`.If the person does not have any card, then the input wold be `Empty`.

The seventh line of each case contains one integer $A$, which means that drawing will begin from the NO.$A$ person.

Drawing and discarding are all in increasing order, when NO.$4$ ends, it comes back to NO.$1$ again, that is the order :$1,2,3,4,1,2,3,4,1,2,3,4,1……$

# Standard Output

When the game ends, please output the point of the remain blood of each person from NO.$1$ to NO.$4$.

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
KKKK
master loyalist rebel duplicity
liushan zhangfei zhaoyun lvbu
4 4 1 1
RRKK KKKK EMPTY R
2</td><td>4
4
0
0</td></tr></table>


# Constraints



# Note



# Source


