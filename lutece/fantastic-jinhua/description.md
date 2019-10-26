
# Content

![title](/source/lutece/fantastic-jinhua/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMzY1LzIwMTQwNDExMTM1NDA1OTQ4MzMucG5n.png)

The standard $52$-card deck consists of $52$ cards divided into $4$ suits: `clubs`, `diamonds`, `hearts` and `spades`. For each suit there are $13$ ranks: `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`, `10`, `jack`, `queen`, `king` and `ace`, listed from the lowest to the highest.

A card is denoted by its rank (`2`$\cdots$ `9` for `2`$\cdots$`9`, `T` for `10`, `J` for `jack`, `Q` for `queen`, `K` for `king`, and `A` for `ace`) followed by its suit (`C` for `clubs`, `D` for `diamonds`, `H` for `hearts`, and `S` for `spades`). Cards are partially ordered by their ranks. The suit does not play a role in the cards ordering.

A Poker hand is a set of three distinct cards. Each hand is said to have a certain ranking. A hand with a higher ranking beats a hand with a lower one. Two hands of the same ranking are compared using a tie-breaking rule specific for their ranking -- either one of them beats the other or they are tied.

The list of poker rankings is given below, from the worst ranking to the best ranking. If a hand satisfies several rankings, only the best one is considered.
1. `High Card`: Does not fit into any ranking below. When comparing with another High Card hand, the ranks of the highest cards in the two hands are first compared. If there is a tie, the second highest cards in each hand are compared, then the third highest cards. (Example: `KD`, `TS`, `3C`)
2. `Pair`: Two cards of the same rank. Pair with higher rank beats the lower pair. In case of a tie, the remaining card is used as a tie-breaker, the one with higher rank beats another one. (Example: `9H`, `9D`, `6S`)
3. Straight: Three cards in consecutive rank. An ace can either be accounted above a king or below a two, but not both, so wrapping is not allowed. Two straights are compared using the rank of the highest card (in the case of `A`, `2`, `3`, the highest card is considered to be `3`). (Example: `6D`, `7D`, `8S`)
4. Flush: Three cards of the same suit. When comparing two Flushes, the rank of the highest card is first considered, then the second highest, and so on (as in `High Card`). (Example: `KS`, `TS`, `5S`)
5. Straight Flush: A hand that is both a Straight and a Flush. Same tie-breaker as for a Straight. (Example: `6D`, `7D`, `8D`)
6. Three of a Kind: Three cards of the same rank. Three-of-a-kind with the higher rank beats the lower one. (Example: `5S`, `5H`, `5C`)

Now I will introduce a poker game called `Fantastic Jinhua` to you. 

At first we need a standard poker with $52$ cards specified before. After the cards are random shuffled (all cards are faced down so that players doesn’t know which card they will get), the card on the top is taken out and faced up on the center of the table as the public card, meaning that every player shares this card. Then, every player (from player $1$ to player $N$) gets a private card (from top to bottom), and a player needn’t show his private card to others. Now every player has two cards, and he needs to imagine the third one (all cards are legal but the one shared by every player on the center of the table, the one himself already has, and the ones have been discarded) to make his hand best. 

After that, every player has to make decisions. This begins from player $1$, who got his private card first. Player $1$ needs to decide if he should exchange his private card or the public card or not (he must choose one but only one of the three decisions). If he exchanges his private card, he will discard his original private card and get a new private card from the top of the remaining cards. If he exchanges the public card, the original pubic card is discarded, and the card from the top of the remaining cards becomes the new public card. If he wouldn’t like to do any exchange, he can pass directly. After player $1$, it’s player $2$’s turn, then play $3$’s, and so on. After player $N$’s turn, it’s player $1$’s turn again.

When would a player like to make an exchange? To simplify this question, we give some conditions. If a player’s hand has a winning probability no less than $p\_{win}$ (while he is calculating his winning probability, he will consider others’ private cards are randomly chosen from the legal cards, meaning that these cards have nothing to do with their decisions. And if his poker hand has a tie with others’, calculate as he wins), he won’t make an exchange. Otherwise, from last time the public card exchanged (the first exchange is considered as at the beginning of the game), if there are no less than $n\_{pass}$ players who haven’t made exchanges and the private card of this player has a rank no less than $R$, he will exchange the public card, or he will exchange his private card.

The game is ending either there are no cards remain or there are no players make exchanges, meaning that when it comes player $x$’s turn, if player $x$ doesn’t make exchange, and from his last turn, there haven’t players made exchanges (At the beginning, after every player got his initial private card, and before player $1$’s first decision, we think that all players have already made an exchange, player $1$ made first, then player $2$, finally player $N$). Then every player shows his private card to other players, who has the best hand beats others and wins the game. If several players have a tie, the one who made his last exchange earliest wins the game.

In this problem, we will give you the information of $N$, $p\_{win}$, $n\_{pass}$, $R$, and the sequence of a standard poker with $52$ cards from top to bottom. You should tell me who wins the game at the end.

# Standard Input

The first line of the input is an integer $T$ ($T\leq 30$), which stands for the number of test cases you need to solve.

Every test case begins with $N$, $p\_{win}$, $n\_{pass}$, $R$, which are specified before. Then on the next line, there are $52$ cards of a standard poker.

$1\leq N\leq 51$

$0.0\leq p\_{win}\leq 1.0$

$0\leq n\_{pass} < N$

$R = $`2`, `3`$\cdots$ `9`, `T`, `J`, `Q`, `K`, `A`

# Standard Output

For every test case, you should output `Case #k:` on a single line first, where k indicates the case number and starts at $1$.Then output the public card, the private cards from player $1$ to player $N$, and the winner when the game is ending, each on a line . Output a blank line after every test case. See sample for more details.

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

3 0.0050 1 T
4D QC 2D 8D JC AH JH TD TS 8C KH 7S QS 6D 6C AC 3H 2C JD 3C 4S 7D 5H 5D 2S KC QH TC KD 9C 3S AD 9H 9D QD 6S AS 3D 4C 7H 6H 5C 9S 2H 4H 5S TH KS 7C 8H JS 8S

5 0.0080 2 J
AD 3C JD 6D 9D 6S 5S 6C 5H TC 3D 2D 9C 8H 9H 2S 7D 3S 9S KC 5C 7C 2C 4S 8C KD QC 4H KH KS TD AC 6H 2H TH QS TS 5D JH 4D 7S AS QH QD 8S AH 3H 4C 8D JC 7H JS</td><td>Case #1:
Public Card: 4D
Player 1's Private Card: QC
Player 2's Private Card: 2D
Player 3's Private Card: 8D
Winner: Player 2

Case #2:
Public Card: AD
Player 1's Private Card: 3C
Player 2's Private Card: JD
Player 3's Private Card: 6D
Player 4's Private Card: 9D
Player 5's Private Card: TC
Winner: Player 2</td></tr></table>


# Constraints



# Note



# Source


