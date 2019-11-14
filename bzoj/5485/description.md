
# Description

<div class="content"><div>奶牛们从世界各地聚集起来参加一场大型聚会。总共有N头奶牛，N?1对奶牛互为朋友。每头奶牛都可以通过一些朋</div>
<div>友关系认识其他每头奶牛。她们玩得很开心，但是现在到了她们应当离开的时间了，她们会一个接一个地离开。她</div>
<div>们想要以某种顺序离开，使得只要至少还有两头奶牛尚未离开，所有尚未离开的奶牛都还有没有离开的朋友。此外</div>
<div>，由于行李寄存的因素，有M对奶牛(ai,bi)必须满足奶牛ai要比奶牛bi先离开。注意奶牛ai和奶牛bi可能是朋友，</div>
<div>也可能不是朋友。帮助奶牛们求出，对于每一头奶牛，她是否可以成为最后一头离开的奶牛。可能会发生不存在满</div>
<div>足上述要求的奶牛离开顺序的情况。</div>
<p></p></div>

# Input

<div class="content"><div>输入的第1行包含两个空格分隔的整数N和M。</div>
<div>输入的第2≤i≤N行，每行包含两个整数xi和yi，满足1≤xi,yi≤N，xi≠yi，表示奶牛xi和奶牛yi是朋友关系。</div>
<div>输入的第N+1≤i≤N+M行，每行包含两个整数ai和bi，满足1≤ai,bi≤N，ai≠bi，表示奶牛ai必须比奶牛bi先离开聚会。</div>
<div>输入保证1≤N,M≤10^5</div>
<p></p></div>

# Output

<div class="content"><div>输出N行，每行包含一个整数di，如果奶牛i可以成为最后一头离开的奶牛，则di=1，否则di=0</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 1<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
2 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
1<br/>
1<br/>
1<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Platinum">Platinum</a></p></div>

