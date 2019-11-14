# 

 
 # 题目描述 
<p>
　　我们都很熟悉二叉树的前序、中序、后序遍历，在数据结构中常提出这样的问题：已知一棵二叉树的前序和中序遍历，求它的后序遍历，相应的，已知一棵二叉树的后序遍历和中序遍历序列你也能求出它的前序遍历。然而给定一棵二叉树的前序和后序遍历，你却不能确定其中序遍历序列，考虑如下图中的几棵二叉树：<br> <br><center><img src="/source/joyoi/tyvj-2927/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkyNy9wcm9ibGVtc19pbWFnZXMvMTIwOS8xLmJtcA==.bmp"></img></center><br>　　所有这些二叉树都有着相同的前序遍历和后序遍历，但中序遍历却不相同。<br></p> 

 
 # 输入格式 
<p>
　　输A数据共两行，第一行表示该二叉树的前序遍历结果s1，第二行表示该二叉树的后序遍历结果s2。</p> 

 
 # 输出格式 
<p>
　　输出可能的中序遍历序列的总数，结果不超过长整型数。</p> 

 
 # 提示 
<p>
【算法分析】<br>　　根据二叉树先序遍历和后序遍历的特点，可以知道，先序遍历的第一个结点是后序遍历的最后一个结点，对于中序遍历来说却是中间的一个结点，这里所说的中间也只是相对而言的中间。如果一棵二叉树的根结点没有左子树，那么先序遍历的第一个结点也是中序遍历的第一个结点，如果一棵二叉树的根结点没有右子树，那么先序遍历的第一个结点是中序遍历的最后一个结点。我们这里还认为就是中序遍历的中间结点，上面两种情况只是特殊的情况。<br>　　设二叉树的结点总数为n(对于输入的字符串来说是它的长度)，对于先序遍历的结果，第一个结点为根结点，从第二个结点到最后一个结点分为n种情况：<br>　　根结点的左子树结点个数为n-1，右子树结点的个数为0；<br>　　根结点的左子树结点个数为n-2，右子树结点的个数为1；<br>　　……<br>　　根结点的左子树结点个数为n-i，右子树结点的个数为i-1；{0 <＝ i <= n-1)；<br>　　……<br>　　根结点的左子树结点个数为0，右子树结点的个数为n-1。<br>　　根据这n种情况，分别将二叉树拆分为左子树和右子树，左子树结点个数为n-i，右子树结点的个数为i-l( 0 <＝ i <＝ n-1)，先序遍历的结果是从第二个结点(字符)开始取，而后序遍历的结果里是从第1个结点字符开始取。也就是说对于每一种情况，分两步处理：第一步在先序遍历和后序遍历的结果里取左子树，看是否符合规则，统计这部分可能有的中序遍历的结果数目；第二步在先序遍历和后序遍历的结果里取右子树，看是否符合规则，统计这部分可能有的中序遍历的结果数目。这两步都递归调用了统计过程，不再递归调用的条件就是当统计的是空树或只有一个结点的树，这时返回的值是可能有的中序遍历结果数目。<br>　　结合“分类相加原理”和“分步相乘原理”，可以得到下面的递归函数：<br>Function count (先序结果first，后序结果last : string) : longint;<br>　　begin<br>　　Len:=遍历结果的长度；<br>　　如果len为0或1，则返回结果即count:=l<br>　　否则  begin<br>　　　　　t为当前统计后符合条件的数目，初值为0；<br>　　　　　分类统计for i:=len-1 downto 0 do<br>　　　　　　　begin<br>　　　　　　　　　在first中取出长度为i的左子树结果LF；<br>　　　　　　　　　在last中取出长度为i的左子树结果LL；<br>　　　　　　　　　在first中取出长度为len-1-i的左子树结果RF；<br>　　　　　　　　　在last中取出长度为len-1-i的右子树结果RL；<br>　　　　　　　　　如果LF、LL符合基本规则(LF的首字符跟LL的尾字符相同、LF中，所有的字符在LL中也都有)<br>　　　　　　　　　并且RF、RL也符合基本规则，那么<br>　　　　　　　　　t:=t+count(LF，LL)*count(RF，RL);<br>　　　　　　　　　{分步相乘、分步相加}<br>　　　　　　　　　{这里count函数中递归调用了count}<br>　　　　　　　end;<br>　　　　　　返回值为t即count:=t;<br>　　　　　end;<br>　end;<br>　其中，检查先序结果和后序结果两个字符串是否符合基本规则，可以再通过一个函数来实现：<br>　function check(先序字符串F，后序字符串L)：boolean；<br>　　　begin<br>　　　　　Check:=true;<br>　　　　　如果F的首字符不等于L的尾字符则check:=false;<br>　　　　　从F的第二个字符取到最后一个字符，如果该字符不在L中，则check:=false;<br>　　　end;<br>【思考与提高】<br>　　上面的算法通过递归，结合统计的基本原理“分步相乘，分类相加”，从而统计出所有可能解的个数，如果输入的两个字符串没有解，上述算法同样能得到结果。<br>在肯定有解的情况下，上述算法最终可以递归调用到0、1个结点，如果有多组解，那么调用到两个结点时，如先序为ab、后序为ba，此时有可能有如下两种结构：<br> <br><center><img src="/source/joyoi/tyvj-2927/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkyNy9wcm9ibGVtc19pbWFnZXMvMTIwOS8yLmJtcA==.bmp"></img></center><br>　　这两种结构的中序遍历结果分别为：ba、ab，有两种。<br>　　根据分步相乘的原理，对比两个字符串，每出现一次如上的情况，可能有的结构数目(结构不同，中序遍历结果也不同，因此可能有的二叉树结构的数目就是可能有的中序遍历结果数目)就乘以2一次，最终得到总的数目。这也可以理解为一种递推的方法。<br>　　从这里可以看到，在肯定有解的情况下，给定先序遍历的结果和后序遍历的结果，可能有2n种可能的结构，也就是中序遍历可能得到2n种不同的结果，其中n>＝0。那么这里的n最大可能是多少呢？可以证明n的最大值为字符串的长度加1整除2。<br>递推的程序如下：<br>Program travel(intput,output);<br>  Var<br>Total,I,m:longint;<br>S1,s2:string;<br>  Begin<br>　　Assign(input,’travel.in’);<br>　　Assign(output,’travel.out’);<br>　　Reset(input);  rewrite(output);<br>　　Readln(s1);    readln(s2);    total:=1;<br>　　For i:=1 to length(s1)-1 do<br>　　　Begin<br>　　　　　M:=pos(s1[i],s2);<br>　　　　　If m>1 then if s[i+1]=s[m-1] then total:=total*2;<br>　　　End;<br>　　Writeln(total);   close(iinput);   close(output);<br>　End.<br><br> <br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>abc						
bca
</td><td>4</td></tr></table>
