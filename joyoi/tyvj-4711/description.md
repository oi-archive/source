# 

 
 # 题目描述 
<p>有若干命题，给出命题的证明关系m个，以及k个初始的真命题，求&nbsp;证明命题p至少需要多少步。</p>

<p>命题关系表示为&nbsp;T&nbsp;a&nbsp;b&nbsp;c。T是一个字符，可以为A&nbsp;或&nbsp;O，a&nbsp;b&nbsp;c是正整数。如:</p>

<p>A&nbsp;1&nbsp;2&nbsp;3&nbsp;表示若1&nbsp;2&nbsp;都成立，则能证明3；</p>

<p>O&nbsp;1&nbsp;2&nbsp;3表示若1&nbsp;2中任意一个成立则能证明3</p>

<p>&nbsp;</p>

<p>注意：本题中保证不出现证明环；证明同一个命题的关系仅有一个，即只出现一次；说白了，这就是个二叉树。</p> 

 
 # 输入格式 
<p>第一行m,k,p，表示共有m个命题之间证明关系，有k个初始成立的真命题，要证明的命题p</p>

<p>接下来m行，每行一个字符后，三个正整数（不超过200000），表示证明关系；</p>

<p>接下来一行，k个整数，表示初始已知成立的真命题。</p> 

 
 # 输出格式 
<p>一行，一个整数表示证明p最少需要多少步。如果不能证明则输出&nbsp;Unable&nbsp;to&nbsp;prove(行末行首无空格)。</p> 

 
 # 提示 
<p>输入样例</p>

<p>5&nbsp;3&nbsp;1<br />
A&nbsp;2&nbsp;3&nbsp;1<br />
O&nbsp;4&nbsp;5&nbsp;2<br />
A&nbsp;6&nbsp;7&nbsp;4<br />
O&nbsp;8&nbsp;9&nbsp;3<br />
A&nbsp;33&nbsp;44&nbsp;22<br />
6&nbsp;7&nbsp;8</p>

<p>输出样例</p>

<p>4</p>

<p>样例解释</p>

<p>6&nbsp;7&nbsp;-&gt;&nbsp;4</p>

<p>4-&gt;&nbsp;2</p>

<p>8-&gt;&nbsp;3</p>

<p>2&nbsp;3-&gt;&nbsp;1</p>

<p>共4步</p>

<p>&nbsp;</p>

<p>数据范围</p>

<p>1&lt;=<span style="line-height: 20.7999992370605px;">所有命题编号，</span>m&lt;=200000</p> 
