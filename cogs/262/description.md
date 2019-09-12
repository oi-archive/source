# 题目描述


<p>
某市组织了一次中学生科技全能竞赛，每个选手要参加数学、物理、化学、天文、地理、生物、计算机和英语共八项竞赛,最后综合八项竞赛的成绩排出总名次。选手编号依次为：1,2...N（N为参赛总人数）。
</p>
<p>
设<img alt="Image:Competitionsort 1.gif" src="../../../../mw/images/8/82/Competitionsort_1.gif" border="0" height="25" width="19"/>分别表示编号为i的选手第j项竞赛的成绩<img alt="Image:Competitionsort 2.gif" src="../../../../mw/images/f/fd/Competitionsort_2.gif" border="0" height="21" width="137"/>。其它指标如下：
</p>
<ul>
<li>
第j项竞赛的平均分 <img alt="Image:Competitionsort 3.gif" src="../../../../mw/images/d/df/Competitionsort_3.gif" border="0" height="45" width="177"/> 
</li>
<li>
选手i的总分 <img alt="Image:Competitionsort 4.gif" src="../../../../mw/images/c/c2/Competitionsort_4.gif" border="0" height="47" width="168"/> 
</li>
<li>
选手i第j项竞赛的位置分 <img alt="Image:Competitionsort 5.gif" src="../../../../mw/images/7/7c/Competitionsort_5.gif" border="0" height="117" width="439"/> 
</li>
<li>
选手i的总位置分 <img alt="Image:Competitionsort 6.gif" src="../../../../mw/images/e/eb/Competitionsort_6.gif" border="0" height="45" width="245"/> 
</li>
</ul>
<p>
排名规则如下:
</p>
<ol>
<li>
总位置分高的选手名次在前：
</li>
<li>
若两个或两个以上的选手总位置分相同，则总分高的选手名次在前：
</li>
<li>
若两个或两个以上的选手总位置分和总分均相同，则编号在前的选手名次在前。
</li>
</ol>
<p>
请你为竞赛组委会编一程序，计算本次全能竞赛的总排名情况。
</p>
<p>
输入输出
</p>
<p>
输入文件的第一行为参赛总人数N<img alt="Image:Competitionsort 7.gif" src="../../../../mw/images/c/c2/Competitionsort_7.gif" border="0" height="21" width="105"/>，从第二行到第N行依次为编号为1到编号为N的选手的成绩，每行有8个0～100之间的整数，代表该选手的8项竞赛成绩<img alt="Image:Competitionsort 8.gif" src="../../../../mw/images/0/00/Competitionsort_8.gif" border="0" height="24" width="81"/>。同一行相邻两个数之间用一个空格符隔开。
</p>
<p>
输出文件有N行，从第1行到第N行依次为排名第1的选手的编号，排名第2的选手的编号，…，排名第N的选手的编号。
</p>
<p>
样例
</p>
<p>
输入文件
</p>
<pre>3
72 82 73 68 95 86 82 90
72 90 50 60 80 70 65 80
72 82 73 68 95 86 82 90
</pre>
<p>
输出文件
</p>
<pre>1
3
2
</pre>
