
# Description

<div class="content"><p><img border="0" src="/source/bzoj/1568/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1NjguanBn.jpg" alt=""/></p></div>

# Input

<div class="content"><div>第一行 ：一个整数N ，表示方案和询问的总数。 </div>
<div>接下来N行，每行开头一个单词“Query”或“Project”。 </div>
<div>若单词为Query，则后接一个整数T，表示Blue Mary询问第T天的最大收益。 </div>
<div>若单词为Project，则后接两个实数S，P，表示该种设计方案第一天的收益S，以及以后每天比上一天多出的收益P。</div>
<div>1 &lt;= N &lt;= 100000 1 &lt;= T &lt;=50000 0 &lt; P &lt; 100，| S | &lt;= 10^6 </div>
<div>提示：本题读写数据量可能相当巨大，请选手注意选择高效的文件读写方式。</div></div>

# Output

<div class="content"><div>对于每一个Query，输出一个整数，表示询问的答案，并精确到整百元（以百元为单位，</div>
<p></p>
<div>例如：该天最大收益为210或290时，均应该输出2）。没有方案时回答询问要输出0</div></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
Project 5.10200 0.65000<br/>
Project 2.76200 1.43000<br/>
Query 4<br/>
Query 2<br/>
Project 3.80200 1.17000<br/>
Query 2<br/>
Query 3<br/>
Query 1<br/>
Project 4.58200 0.91000<br/>
Project 5.36200 0.39000</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
0<br/>
0<br/>
0<br/>
0</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

