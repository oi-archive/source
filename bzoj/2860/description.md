
# Description

<div class="content"><p>现在有n个马车在铁路口等着，每个马车上有一种垃圾。我们有一些垃圾处理器，每种垃圾处理器能处理一些特定的垃圾。每天只能用一个垃圾处理器<br/>
铁路旁边还有一个栈<br/>
n个马车按顺序过去，如果当前的垃圾处理器能处理他，就处理了；否则要么过一天换一个垃圾处理器，要么你可以把它放入栈中<br/>
你每次既能处理铁路上的垃圾，也能处理栈中的垃圾……处理有顺序要求，铁路上的垃圾得按顺序处理，栈中的垃圾得按入栈顺序的逆序处理（所以才叫栈）。<br/>
每天一个垃圾处理器能处理无限垃圾<br/>
你要处理三天垃圾，你需要通过调整三天里分别用哪种垃圾处理器，从而处理最多数目的垃圾，同时还要求三天后栈是空的</p></div>

# Input

<div class="content"><p>第一行N,K,S，表示n个马车，有K种垃圾，有S种垃圾处理器，n&lt;=20000,K,S&lt;=1000<br/>
接下来S行，每行若干个数，表示垃圾处理器能处理的垃圾集合。每行以0结尾<br/>
最后一行N个数表示每辆马车上面的垃圾种类<br/>
保证每种垃圾至少一种最多十种垃圾处理器能处理</p></div>

# Output

<div class="content"><p>第一行输出最多能处理多少垃圾<br/>
第二行输出三个数，分别表示三天的的垃圾处理器<br/>
如果第一问答案是n，存在两天的方案，那么要求输出两天的；如果第一问答案是n，存在一天的方案，要求输出一天的<br/>
如果存在两天的方案，第三个数字应该是0；如果存在一天的方案，第二、三个数字应该是0</p></div>

# Sample Input

<div class="content"><span class="sampledata">13 5 4<br/>
1 0<br/>
4 5 0<br/>
5 3 0<br/>
2 5 0<br/>
4 5 2 5 5 4 1 1 5 4 5 3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">11<br/>
2 1 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Ydc提供SPJ">鸣谢Ydc提供SPJ</a></p></div>

