
# Description

<div class="content"><p><span style="font-size: medium">yz是Z国的领导人，他规定每个地区的名字只能为26个小写拉丁字母的一个。由于地 区数有可能超过26个，便产生了一个问题，如何辨别名字相同的地区？于是yz规定，一个 地区的描述必须包含它的所有上级，且上级按次序排列。于是，一个地区的描述是一个字符 串。比如说，一个地区的名字为c，它的上级为b，b的上级为a，a没有上级，那么这个地 区就描述为abc。显然，这个描述同时包含了c的上级b和b的上级a的描述，分别为ab和a。 值得注意的是，每个地区最多有一个上级，同一上级的地区之间名字不同，没有上级的 地区之间名字不同。现在，yz对外公布了n个地区的描述，这些描述中包含了Z国所有地区的描述，并让 你处理来访者的旅行问题。现有m对人访问这个国家，对于每对人，第一个人喜欢第i个描述中的第j个地区，设 这个地区描述为s1，第二个人喜欢第k个描述中的第l个地区，设这个地区描述为s2。他们为了统一行程，决定访问描述为s的地区（显然他们只关心地区的名字，并非是地区本身）， 设s的长度为t，s需要满足以下条件： <br/>
1：t&lt;=j, t&lt;=l; <br/>
1：s[1..t] = s1[j-t+1 … j], s[1..t] = s2[l-t+1 … l]；（即s为s1中1到k位 与s2中1到l位的公共后缀） <br/>
2：t最大化。 <br/>
为了不使输出过大，你只需把这个字符串按照如下生成的26进制数转成10进制后mod 1000000007后输出: <br/>
a-&gt;0 <br/>
b-&gt;1 <br/>
. <br/>
. <br/>
. <br/>
z-&gt;25 <br/>
比如地区cab被编码成2 *    26? + 0 * 26? + 1 * 26? = 1353。 <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行给定一个整数n <br/>
第2…n+1行:每i+1行给定一个字符串a[i],表示第i个描述。 <br/>
接下来一行一个整数m <br/>
接下来m行:每行给定四个整数i,j,k,l，字母含义与题目描述一致。 <br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">共m行，每行一个整数，表示答案字符串的编码。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
aabb babb <br/>
2 <br/>
1  3 2 3<br/>
1  4 2 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
1 <br/>
【样例说明】<br/>
询问1中的公共后缀有ab和b，但是没有ab这个地区，只有b地区，所以只能选择b这个 地区； <br/>
询问2中的公共后缀有abb、bb和b，但是没有abb和bb这两个地区，只有b地区，所以 只能选择b这个地区。 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】</p><br/>
<p> 设这个国家地区总数数为tot（注意：输入的字符串总长度可能超过tot！） 对于30%的数据，满足tot，m，n&lt;=100； <br/><br/>
对于50%的数据，满足tot，m，n&lt;=1000； <br/><br/>
对于80%的数据，满足tot，m，n&lt;=100000； <br/><br/>
对于100%的数据，满足tot，m，n&lt;=1000000； <br/><br/>
保证输入文件不超过20MB。 <br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

