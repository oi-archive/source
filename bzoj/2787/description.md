
# Description

<div class="content"><p><span style="font-size: medium">Maintain two sets of strings S and T.Initially,each set contains an empty string with id 1.<br/>
Your program are to perform the following four operations:</span></p>
<p><span style="font-size: medium">1.Add a char c to the end of an existed string Si in S,then insert the new string into S.Since there has been n strings in S already,the new string will hold the id n+1.<br/>
2.Add a char c to the beginning or to the end of an existed string Ti in T,then insert the new string into T.<br/>
3.Choose two existed strings Ti and Tj from T,next combine them into a new one TiTj,then insert the new string into T.<br/>
4.Print the time that an existed string Ti in T appears in an string Si in S.Your program should print 0 if Ti is an empty string. </span></p>
<p><span style="font-size: medium">维护两个字符串集合S,T，一开始S和T都只有一个空串,编号都为1,要求支持操作:<br/>
1.在S的某一个串Si后添加一个字符c，加入S<br/>
2.在T的某一个串Ti的前面或后面添加一个字符c，加入T<br/>
3.将T的两个串Ti,Tj首尾相接形成一个新串TiTj，加入T<br/>
4.询问T中的某个串Ti在S中某个串Si中的出现次数.（如果Ti是空串，输出0）<br/>
</span></p>
<p><span style="font-size: medium"> </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">In the first line,there is an integer Q,which means the number of operations to perform.<br/>
In the next Q lines,the i-th line describes the i-th operation containing some integers.Such a line may look like this:<br/>
1 Si c<br/>
2 0 Ti c =&gt;add c to the beginning of Ti<br/>
2 1 Ti c =&gt;add c to the end of Ti<br/>
3 Ti Tj<br/>
4 Ti Si</span></p>
<p><span style="font-size: medium">Q&lt;=300000,&#39;a&#39;&lt;=c&lt;=&#39;z&#39;<br/>
The number of the first operation will not exceed 100000. <br/>
The number of the third operation will not exceed 30000.<br/>
The number of fourth operation will not exceed 100000.   </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">For each &#34;4 Ti Si&#34; operation,print its result;</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">18<br/>
1 1 a<br/>
1 2 a<br/>
1 3 b<br/>
1 2 b<br/>
1 5 a<br/>
1 5 b<br/>
2 1 1 a<br/>
3 2 2<br/>
2 0 3 b<br/>
2 1 2 b<br/>
3 2 5<br/>
3 5 2<br/>
4 7 6<br/>
4 5 6<br/>
4 3 4<br/>
4 2 4<br/>
4 2 7<br/>
4 2 6<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1<br/>
2<br/>
1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

