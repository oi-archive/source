# 题目描述


<p>
	<b>Magic Squares</b> 魔板
</p>
<p>
	译 by Felicia Crazy
</p>
<p>
	</p><hr/>
	<p>
		<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
	</p>
	<p>
		在成功地发明了魔方之后，鲁比克先生发明了它的二维版本，称作魔板。这是一张有8个大小相同的格子的魔板：
	</p>
<pre>1  2  3  4  
8  7  6  5  
</pre>
	<p>
		我们知道魔板的每一个方格都有一种颜色。这8种颜色用前8个正整数来表示。可以用颜色的序列来表示一种魔板状态，规定从魔板的左上角开始，沿顺时针方向依次取出整数，构成一个颜色序列。对于上图的魔板状态，我们用序列（1，2，3，4，5，6，7，8）来表示。这是基本状态。
	</p>
	<p>
		这里提供三种基本操作，分别用大写字母“A”，“B”，“C”来表示（可以通过这些操作改变魔板的状态）：
	</p>
<pre>“A”：交换上下两行；  
“B”：将最右边的一列插入最左边； 
“C”：魔板中央四格作顺时针旋转。 
</pre>
	<p>
		下面是对基本状态进行操作的示范：
	</p>
<pre>A:  8  7  6  5  
    1  2  3  4  
B:  4  1  2  3  
    5  8  7  6  
C:  1  7  2  4  
    8  6  3  5  
</pre>
	<p>
		对于每种可能的状态，这三种基本操作都可以使用。
	</p>
	<p>
		你要编程计算用最少的基本操作完成基本状态到目标状态的转换，输出基本操作序列。
	</p>
	<p>
		<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline"></span> 
	</p>
	<p>
		<span class="mw-headline">格式</span> 
	</p>
	<p>
		</p><p>
			<b>PROGRAM NAME</b>: msquare
		</p>
		<p>
			<b>INPUT FORMAT</b>:
		</p>
		<p>
			(file msquare.in)
		</p>
		<p>
			只有一行，包括8个整数，用空格分开（这些整数在范围 1——8 之间）不换行，表示目标状态。
		</p>
		<p>
			<b>OUTPUT FORMAT</b>:
		</p>
		<p>
			(file msquare.out)
		</p>
		<p>
			Line 1: 包括一个整数，表示最短操作序列的长度。
		</p>
		<p>
			Line 2: 在字典序中最早出现的操作序列，用字符串表示，除最后一行外，每行输出60个字符。
		</p>
<span class="mw-headline"></span> 
		<p>
			<br/>
		</p>
		<p>
			<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT (msquare.in)</span> 
		</p>
<pre>2 6 8 4 5 7 3 1 
</pre>
		<p>
			<span id="SAMPLE_OUTPUT" class="mw-headline"></span> 
		</p>
		<p>
			<span class="mw-headline">SAMPLE OUTPUT (msquare.out)</span><span class="mw-headline"></span> 
		</p>
		<p>
</p><pre>7 
BCABCCB
</pre>
<!-- 
NewPP limit report
Preprocessor node count: 15/1000000
Post-expand include size: 0/2097152 bytes
Template argument size: 0/2097152 bytes
Expensive parser function count: 0/100
--><!-- Saved in parser cache with key newnocow:pcache:idhash:850-0!*!*!!zh-cn!*!* and timestamp 20120709094038 --><span class="mw-headline"></span> 
			<p>
				<br/>
			</p>
			<p>
				<span class="mw-headline"></span> 
			</p>
			<p>
				 
			</p>
<span class="mw-headline"></span>
