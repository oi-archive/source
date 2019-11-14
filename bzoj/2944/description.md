
# Description

<div class="content"><div align="center"></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">一棵二叉树要么为空，要么由一个结点和两棵与其相连的树组成。这两棵树分别称为左子树和右子树。每个结点处有一个英文字母。不包括在任何子树内的结点称为根结点。我们定义二叉搜索树(BST)为：若按字母表中的先后顺序排列，则二叉树的任一个结点均满足，其左子树上的所有字母均在该结点字母之前，而其右子树上所有字母均在该结点字母之后。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">于是，一棵BST的代码为：</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">●如果是一棵空树，则代码中不包括任何字母，即为空串；</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">●如果不是空树，则代码为：根结点上的字母，紧跟着左子树的代码和右子树的代码。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">一棵含k个结点的BST，其代码会有k个小写英文字母，按照字母顺序排列它所有可能的代码，并用(n,k)表示其中的第n条代码。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">例如，一棵有4个结点的BST共有14个不同的代码，按字母顺序列出：abcd 、abdc、 acbd、 adbc、 adcb、 bacd、 badc、 cabd、 cbad、 dabc、 dacb、 dbac、 dcab、 dcba。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">代码(7,4)：badc，对应的BST如下图所示。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"><img height="143" width="166" alt="" src="/source/bzoj/2944/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTIxMi8xMSg0KS5qcGc=.jpg"/></span></div>
<div><span style="font-size: medium"><b>任务：</b></span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">编写一个程序，完成下列工作：</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">●读入n，k；</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">●找出代码(n,k)；</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">●把它写入</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">仅一行，包括以空格分开的两个整数n和k(1≤K≤19)。n不超过BST代码的总数。</span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 21pt"><span style="font-size: medium">仅一行，是以小写字母给出的代码(n,k)。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">11 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">dacb</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

