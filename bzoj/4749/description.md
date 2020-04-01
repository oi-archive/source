
# Description

<div class="content"><div>Farmer John&#39;s N cows (1≤N≤200) want to organize an emergency &#34;moo-cast&#34; system for broadcasting im</div>
<div>portant messages among themselves.Instead of mooing at each-other over long distances, the cows deci</div>
<div>de to equip themselves with walkie-talkies, one for each cow. These walkie-talkies each have a limit</div>
<div>ed transmission radius -- a walkie-talkie of power PP can only transmit to other cows up to a distan</div>
<div>ce of PP away (note that cow A might be able to transmit to cow B even if cow B cannot transmit back</div>
<div>, due to cow A&#39;s power being larger than that of cow B). Fortunately, cows can relay messages to one</div>
<div>-another along a path consisting of several hops, so it is not necessary for every cow to be able to</div>
<div> transmit directly to every other cow.Due to the asymmetrical nature of the walkie-talkie transmissi</div>
<div>on, broadcasts from some cows may be more effective than from other cows in their ability to reach l</div>
<div>arge numbers of recipients (taking relaying into account). Please help the cows determine the maximu</div>
<div>m number of cows that can be reached by a broadcast originating from a single cow.</div>
<div>
<div>每头牛手上有一台对讲机，给出N（1≤N≤200）头牛的坐标（X,Y）及其对讲机的极限传输半径P，也就是说该对讲</div>
<div>机能将信息传送到与之距离不超过P的对讲机。幸运的是,牛可以传递消息通过其他牛，所以没有必要每头牛能直接</div>
<div>传送到其他牛。请帮助奶牛确定：如果源于一头牛，最多能将信息传递到多少头牛？</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>The first line of input contains N.The next N lines each contain the xx and yy coordinates of a sing</div>
<div>le cow ( integers in the range 0…25,000) followed by p, the power of the walkie-talkie held by this</div>
<div> cow.</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>Write a single line of output containing the maximum number of cows a broadcast from a single cow ca</div>
<div>
<div>n reach. The originating cow is included in this number.</div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 3 5<br/>
5 4 3<br/>
7 2 1<br/>
6 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
In the example above, a broadcast from cow 1 can reach 3 total cows, including cow 1.</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver 鸣谢winmt提供译文">Silver 鸣谢winmt提供译文</a></p></div>

