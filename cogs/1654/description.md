# 题目描述


<h3>
【题目描述】
</h3>
<p>
密码学是一种给信息编码的科技，使得只有特定的接收者才能解读它们。另一方面，密码分析学，是破译密码的科学。在这个问题中，假设你是一位密码分析学家，被雇用来破译一些在警察对当地黑手党总部的突袭中截获的加密信息。你的同行已经通过逆向工程得到了加密程序，剩下唯一要做的就是逆向分析加密算法并且猜测这些文件的密钥。与这些密文一起，警察还截获了一些明文，他们确信这些明文和密文来自相同的文章，因此在措辞，语法等方面有着相似的结构。
</p>
<h4>
加密程序如下：
</h4>
<p>
C语言版本：
</p>
<p>
<br/>
</p>
<pre class="prettyprint lang-cpp">/* crypto.c */

#include &lt;stdio.h&gt;
#include &lt;ctype.h&gt;
#include &lt;string.h&gt;

const int len = 10;
const char *let = &#34;ABCDEFGHIJKLMNOPQRSTUVWXYZ&#34;;

int main()
{
	char s1[250], s2[250];
	FILE *f1, *f2;
	unsigned char key[len];
	int i, k, c;
	char *p;

	printf(&#34;Input file: &#34;); gets(s1);
	f1 = fopen(s1, &#34;rt&#34;);
	printf(&#34;Output file: &#34;); gets(s2);
	f2 = fopen(s2, &#34;wt&#34;);
	printf(&#34;Key (%d bytes): &#34;, len);
	for (i = 0; i &lt; len; ++i) scanf(&#34;%d&#34;, &amp;key[i]);
	k = 0;
	while ((c = fgetc(f1)) != EOF) {
		p = strchr(let, toupper(c));
		if (p != NULL) {
			i = ((p - let) + key[k]) % strlen(let);
			c = let[i];
			k = (k + 1) % len;
		}
		fputc(c, f2);
	}
	fclose(f1);
	fclose(f2);
	return 0;
}
</pre>
Pascal语言版本：
<p>
<br/>
</p>
<p>
<br/>
</p>
<pre class="prettyprint">{ crypto.pas }

const
	len = 10;
	let = &#39;ABCDEFGHIJKLMNOPQRSTUVWXYZ&#39;;
var
	s1, s2 : string;
	f1, f2 : text;
	key : array [1..len] of byte;
	i, k : integer;
	c : char;
begin
	write (&#39;Input file: &#39;); readln (s1);
	assign (f1, s1); reset (f1);
	write (&#39;Output file: &#39;); readln (s2);
	assign (f2, s2); rewrite (f2);
	write (&#39;Key (&#39;, len, &#39; bytes): &#39;);
	for i := 1 to len do read (key[i]);
	k := 0;
	while not eof (f1) do begin
		while not eoln (f1) do begin
			read (f1, c);
			i := pos (upcase (c), let);
			if i &gt; 0 then begin
				k := k mod len + 1;
				i := (i - 1 + key[k]) mod length (let) + 1;
				c := let[i];
			end;
			write (f2, c);
		end;
		if not eof (f1) then begin
			readln (f1);
			writeln (f2);
		end;
	end;
	close (f1);
	close (f2);
end.</pre>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
由于COGS的环境限定，本题的数据格式较为特殊。
</p>
<p>
有5组测试数据。第i组数据包含两个.in文件：crai.in和cra(i+5).in。其中，前者是密文，后者是来源于相同文章的一段明文（即题目描述中所说的.txt文件）。
</p>
<p>
例如，第1组数据是cra1.in和cra6.in，其中cra1.in是密文，cra6.in是相同来源的明文，第3组数据是cra3.in和cra8.in，其中cra3.in是密文，等等。
</p>
<h3>
【输出格式】
</h3>
<p>
你需要提交10个.out文件：cra1.out~cra10.out。其中,cra1.out~cra5.out是五组数据破译后的结果，cra6.out~cra10.out的内容分别与cra6.in~cra10.in完全相同。
</p>
<h3>
【来源】
</h3>
<p>
<a target="_blank" href="http://www.ii.uni.wroc.pl/boi/task/crazad.phtml">BOI2001 Crack the Code</a> 
</p>
