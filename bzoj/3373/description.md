
# Description

<div class="content"><div>
<div>兽群中总是有一些麻烦制造者．约翰知道他的N(1≤N≤100)头奶牛中有一头总是说谎，其他的总是说真话．他想快速的找出这个麻烦制造者．为了实现这个目标，他一个一个的问这些奶牛Q(1≤Q≤1000)个关于它们吃草的简单问题（虽然大多数奶牛是诚实的但它们依旧很笨只能懂得一些关于食物的话题）．</div>
<div>他将这些问题用以下的格式写了下来：</div>
<div>牛4说：牛5比牛10吃得多</div>
<div>牛6说：牛10比牛7吃得多</div>
<div>牛3说：牛2比牛6吃得多</div>
<div>牛1说：牛7比牛5吃得多</div>
<div>从这个例子中不难看出说谎的奶牛只有可能是4，6，1．你的任务是确定可能说谎的奶牛的个</div>
<div>数．可能说谎的奶牛是指如果这头奶牛说谎则输入数据中不存在矛盾．</div>
</div></div>

# Input

<div class="content"><div>第1行：两个用空格分开的整数N和Q.第2到Q+1:每一行描述一个问题，由3个用空格隔开的整数A，B，C表示，意思是A说B牛吃的比C牛多．一头奶牛可能回答多次．</div></div>

# Output

<div class="content"><div>仅一行一个整数即可能说谎的奶牛的头数．</div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
3 1 2<br/>
1 3 1<br/>
1 3 2<br/>
2 2 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
样例说明<br/>
    3头奶牛给出了4个回答．奶牛1说3&gt;1，3&gt;2，奶牛2说2&gt;1，奶牛3说1&gt;2．当然“&gt;”的意思是“吃得多”．    显然，2号和3号的话是矛盾的．它们都有可能说谎．如果1号说谎则2，3都没说谎，那是不可能的．所以，1号说的一定是实话．</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Orange">Orange</a></p></div>

