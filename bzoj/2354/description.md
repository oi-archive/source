
# Description

<div class="content"><p>无向图中的汉密尔顿是指一条路径，它经过每个点有且仅有一次。每条汉密尔顿路径的<br/>
权值定义为这条路径中每条边的权值之和。这是最近 WZK 教小 Y 学的图论知识，现在 WZK<br/>
想检验一下小Y的举一反三的能力，提出了以下问题： <br/>
有一个n 个顶点的无向图（顶点从 0到 n-1 标号），它的每一个顶点都标有一个字符串<br/>
label[i] ，两两顶点间都存在一条边，一条从 i 到 j 的 边 的 权 值 定 义 为<br/>
length(label[i])^2+length(label[j])^2-length(LCP(label[i],label[j]))^2，LCP指的<br/>
是两个字符串的最长公共前缀。现在，要求一个从顶点 0出发，到顶点 1结束的权值最小的<br/>
汉密尔顿路径。</p>
<p></p></div>

# Input

<div class="content"><p> 第一行，一个整数 n (2&lt;=n&lt;=50)。 <br/>
接下来n行，每行一个不超过 50个字母的小写字符串 label[i],i从0到n-1。 <br/>
 </p>
<p></p></div>

# Output

<div class="content"><p>仅一行，为要求的汉密尔顿路径的权值。</p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 <br/>
abcd <br/>
aecgh <br/>
abef <br/>
aecd <br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">91<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

