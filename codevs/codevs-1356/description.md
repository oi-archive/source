<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>yz 是 Z 国的领导人，他规定每个地区的名字只能为 26 个小写拉丁字母的一个。由于地<br>区数有可能超过 26 个，便产生了一个问题，如何辨别名字相同的地区？于是 yz 规定，一个<br>地区的描述必须包含它的所有上级，且上级按次序排列。于是，一个地区的描述是一个字符<br>串。比如说，一个地区的名字为 c，它的上级为 b，b 的上级为 a，a 没有上级，那么这个地<br>区就描述为 abc。显然，这个描述同时包含了 c 的上级 b 和 b 的上级 a 的描述，分别为 ab<br>和a。</p>
<p>值得注意的是，每个地区最多有一个上级，同一上级的地区之间名字不同，没有上级的<br>地区之间名字不同。 <br>现在，yz 对外公布了 n 个地区的描述，这些描述中包含了 Z 国所有地区的描述，并让<br>你处理来访者的旅行问题。 <br>现有 m 对人访问这个国家，对于每对人，第一个人喜欢第 i 个描述中的第 j 个地区，设<br>这个地区描述为 s1，第二个人喜欢第 k 个描述中的第 l 个地区，设这个地区描述为 s2。他<br>们为了统一行程，决定访问描述为 s 的地区（显然他们只关心地区的名字，并非是地区本身），<br>设 s 的长度为 t，s 需要满足以下条件： <br>1：t&lt;=j, t&lt;=l; <br>2：s[1..t] = s1[j-t+1 … j], s[1..t] = s2[l-t+1 … l]；（即s为s1中1到k位与 s2 中 1 到 l 位的公共后缀） <br>3：t 最大化。 <br>为了不使输出过大，你只需把这个字符串按照如下生成的 26 进制数转成 10 进制后 mod 1000000007 后输出: <br>a-&gt;0 <br>b-&gt;1 <br>. <br>. <br>. <br>z-&gt;25 <br>比如地区 cab 被编码成 2 * 26^2+ 0 * 26^1+ 1 * 26^0= 1353。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行给定一个整数 n <br> 第 2…n+1 行:每 i+1 行给定一个字符串 a[i],表示第 i 个描述。 <br> 接下来一行一个整数 m <br> 接下来 m 行:每行给定四个整数 i,j,k,l，字母含义与题目描述一致。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共 m 行，每行一个整数，表示答案字符串的编码。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <br>aabb <br>babb <br>2 <br>1 3 2 3 <br>1 4 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 <br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>询问 1 中的公共后缀有 ab 和 b，但是没有 ab 这个地区，只有 b 地区，所以只能选择 b 这个<br>地区； <br>询问 2 中的公共后缀有 abb、bb 和 b，但是没有 abb 和 bb 这两个地区，只有 b 地区，所以<br>只能选择 b 这个地区。</p>
<p>设这个国家地区总数数为 tot（注意：输入的字符串总长度可能超过 tot！） <br>对于 30%的数据，满足 tot，m，n&lt;=100； <br>对于 50%的数据，满足 tot，m，n&lt;=1000； <br>对于 80%的数据，满足 tot，m，n&lt;=100000； <br>对于 100%的数据，满足 tot，m，n&lt;=1000000； <br>保证输入文件不超过 20MB。</p>
</div>
</div>