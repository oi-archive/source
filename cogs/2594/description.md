# 题目描述


<h3>
【题目背景】
</h3>
<p>
<img src="/upload/image/20170119/20170119093943_25716.png" alt=""/> 
</p>
<p>
<img src="/upload/image/20170119/20170119094105_33792.png" alt=""/> 
</p>
<h3>
【题目描述】
</h3>
<p>
<img src="/upload/image/20170119/20170119094255_53967.png" alt=""/> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行两个数N,Q,表示Keller有N个串同时梨园春有Q次询问:
</p>
<p>
      接下来有N行:
</p>
<p>
             第i行行首有一个值T_i,表示第i号字符串的长度,接下来有T_i个数,第j个数表示这个字符的 UTF-滑 编码的值
</p>
<p>
      接下来又有Q行:
</p>
<p>
             第i行行首有两个值P_i和C_i分别表示梨园春的攻击的串的长度,和要询问最邻近的C_i个串的值,接下来有P_i个数表示了这个字符串.
</p>
<p>
我们已经把所有 UTF-滑 字符转成整数(不保证非负)
</p>
<h3>
【输出格式】
</h3>
<p>
对于第i个询问:
</p>
<p>
      首先输出the closest %d strings&#39; distance are: 其中”%d”为C_i
</p>
<p>
      换行后有C_i行,每一行上有一个数,这C_i行上的数从小到大表示了与询问串距离最近的C_i个字符串的距离
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5  5
2  9 10  
5  6  9 10  3  1  
4  3  7  6  9  
4  6  2  8  8  
4  2  4  1  3  
2  3  8  0  
4  3  5  9  5  7  
1  1  5  
3  3  4  0  3  
4  1  3  1  2  5  
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
the closest 3 strings&#39; distance are:
1634
8224
10001
the closest 3 strings&#39; distance are:
49
883
1218
the closest 1 strings&#39; distance are:
419
the closest 3 strings&#39; distance are:
369
4753
9044
the closest 1 strings&#39; distance are:
99
</p>
</pre>
<h3>
【提示】
</h3>
<p>
对第P个测试点有$80(i-1)^2\le N,Q\le 80i^2$
</p>
<p>
对于所有测试点有每个字符的值$\le 23333$
</p>
<p>
保证有解且解在Python Integer 范围内.
</p>
<p>
长度不同按零从最后位补全(详见样例)
</p>
<h3>
【来源】
</h3>
<p>
驴蛋蛋的脑冻
</p>
<p>
<img src="/upload/image/20170120/20170120170659_88898.png" alt=""/>
</p>
