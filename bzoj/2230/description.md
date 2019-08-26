
# Description

<div class="content">有一种纸牌游戏叫”Fool’s Game”，其规则是这样的：
	使用4种花色的6,7,8,9,10,J,Q,K,A共36张牌，牌的大小按照从左到右依次变大。有一种花色是主牌，主牌比所有副牌都大。
	打牌的过程双方都可以看到对方的牌，以及桌上的牌，以及已经被丢弃的牌。
	在一轮游戏中，由一方出牌，一方跟牌。一轮游戏进程如下：
	首先，出牌方甩出若干相同大小的牌。
	当出牌方甩出牌之后，跟牌方应该对每一张新出的牌都用一张自己的牌跟上去，这张跟上去的牌必须比被跟的牌大。
	如果桌上所有牌都成功被跟，出牌方必须在甩出至少一张牌，且甩出的牌的分值必须在桌上已经出现过。
	如果某一轮出牌方甩牌之后，跟牌方不能或不愿意跟掉这些牌，则出牌方还可以选择再甩出若干张牌（这些牌的分值必须在桌上已经出现过）。然后，出牌方赢得这一轮，桌上所有牌归该跟牌方所有。双方的角色不变，进入下一轮游戏。
	如果某一轮跟牌方完成跟牌之后，出牌方不能或不愿意再甩牌，则跟牌方赢得这一轮游戏。桌上所有牌被丢弃，双方交换出牌、跟牌角色后进入下一轮游戏。
	任何一个时刻，桌上未被跟的牌的数量不能超过跟牌方手中的牌的数量。
	游戏的胜负这样判定：
	如果某一轮结束之后，一方手中无牌而另一方手中有牌，则无牌的一方胜。
	如果某一轮结束之后双方手中都无牌，则在刚刚结束的那一轮中出牌的一方获胜。
给出一开始每给人手上的牌，判断哪一方获胜。（第一个人在第一轮中出牌）。
限制
	每个人手中的牌的数量不超过6张。
</div>

# Input

<div class="content">The first line of the input file contains n1 and n2 — the number of cards that each of the players has in the beginning of the round (1 ≤ n1, n2 ≤ 6), and the trump suit (suit is specified using one letter: ‘S’ for spades, ‘C’ for clubs, ‘D’ for diamonds, ‘H’ for hearts).

The second line contains n1 card descriptions — the cards of the first player. Each card is specified by its rank (‘6’…‘9’, ‘T’ for 10, ‘J’ for Jack, ‘Q’ for Queen, ‘K’ for King, ‘A’ for Ace) followed by its suit. The third line contains n2 card descriptions — the cards of the covering player. The first player is the starting player in the first round.

All cards in players’ hands are different.

</div>

# Output

<div class="content">Output “FIRST” if the first player wins the game, or “SECOND” if the second player does.

</div>

# Sample Input

<div class="content"><span class="sampledata">sample input #1<br/>
2 2 S<br/>
KC AD<br/>
6S 7S<br/>
<br/>
sample input #2<br/>
2 2 D<br/>
KC AD<br/>
6S 7S<br/>
<br/>
sample input #3<br/>
4 5 C<br/>
AS 6S 7S 8S<br/>
9S TS JS QS KS<br/>
<br/>
sample input #4<br/>
3 2 C<br/>
6H JS JD<br/>
AD 6C<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">sample output #1<br/>
SECOND<br/>
<br/>
sample output #2<br/>
FIRST<br/>
<br/>
sample output #3<br/>
SECOND<br/>
<br/>
sample output #4<br/>
FIRST<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Neerc2006">Neerc2006</a></p></div>

