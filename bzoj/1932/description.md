
# Description

<div class="content"><p>中学数学里集合的元素往往是具体的数字，比如A = {1,2,3}，B = {}（空集）等等。但是要特别注意，集合的元素也可以是另一个集合，比如说C = {{}}，即说明C有且仅有一个元素——空集B，所以称B是C的子集或者称B是C的元素都是正确的。所谓一个集合的势，就是这个集合的元素个数，一般记为|S|，空集的势为0。在上例中，|A| = 3，|B| = 0，|C| = 1。 鉴于集合论是现代数学的基础理论这一事实，一群异想天开的科学家开始着手建造一台新式的超级计算机——集合堆栈机Alpha，这台机器操作的将是集合而不是数字。不过由于Alpha的竣工之日遥遥无期，科学家们希望你为他们编写一台虚拟机，好让他们检查自己的原型设计是否合理。 Alpha的存储设备只有一个栈，栈的每个单元都只能放置一个集合。一开始，栈是空的，在每个操作结束后，计算机就会输出位于栈顶单元的那个集合的势。Alpha拥有五种不同的指令，分别为：PUSH、DUP、UNION、INTERSECT和ADD，他们的功能如下：</p>
<p><img border="0" src="/source/bzoj/1932/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE5MzIuanBn.jpg" alt=""/></p></div>

# Input

<div class="content"><p>第一行只有一个整数n（0≤n≤2000），代表将要执行的指令条数。接下来有n行，每行有包含一条大写的指令，我们保证每条指令都是上述五条指令中的一条，并且虚拟机总是能正确执行完所有的指令。</p></div>

# Output

<div class="content"><p>输出虚拟机的输出结果即可。每行输出一个大于或等于0的整数，代表虚拟机执行该条指令后的输出。选手们务必仔细考量程序的执行效率。</p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
PUSH<br/>
DUP<br/>
ADD<br/>
PUSH<br/>
ADD<br/>
DUP<br/>
ADD<br/>
DUP<br/>
UNION<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
1<br/>
0<br/>
1<br/>
1<br/>
2<br/>
2<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于20%的数据，n ≤ 10。 对于100%的数据，n ≤ 2000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

