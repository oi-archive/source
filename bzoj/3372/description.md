
# Description

<div class="content"><div><span style="font-size: medium">    贝茜统计到人类拥有很多大学可以去就读，而奶牛们却一个大学也没有．为了解决这个问</span></div>
<div><span style="font-size: medium">题，她和她的同伴们建立了一所奶牛大学Moo大学．为了防止笨牛入学，学校的创立者搞了一个奶牛智力测试(CSAT)，它的分数在区间[1，2×10^9]内．Moo大学的学费很昂贵：不是所有奶牛都能负担．事实上，大多数奶牛需要一些财政帮助a(0≤o≤100000)．政府不会给奶牛任何资金，所以所有的资金都来自于学校有限的资金，资金总数为F(0≤F≤2×10^9).更糟的是，虽然有C(N≤C≤100000)头奶牛报考，Moo大学却只能接受N(1≤N≤19999)头奶牛，N为奇数．贝茜既要让这N头奶牛享受最大限度的教育资源，又要它们CSAT分数的中位数尽可能高．    这里说一下对于一个奇数个数组成的集合中中位数的概念．例如，集合3，8，9，7，5的中位数是7，因为有两个数小于7，有两个数大于7．    给出每头奶牛的分数和所需的财政补贴数，可以接纳的奶牛数，补助的资金总数，求出中位数最大的可能值．</span></div>
<div></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：三个用空格分开的整数N，C，F.</span></div>
<div><span style="font-size: medium">    第2到C+1行：每行有两介用空格隔开的整数．第一个数表示这头奶牛的CSAT分数；第二个</span></div>
<div><span style="font-size: medium">整数表示这头奶牛所需的补助数额．</span></div>
<div></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    仅一行，一个整数即最大的中位数可能值．如不存在输出-1.</span></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">    3  5  70<br/>
    30  25<br/>
    50  21<br/>
    20  20<br/>
    5  18<br/>
    35  30<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    35<br/>
样例说明<br/>
    如果贝茜接收CSAT分数为5，35，50的奶牛，中位数为35.总的资金要求为18+30+21=69<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Green">Green</a></p></div>

