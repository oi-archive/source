# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">题目叙述</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">要开运动会了，Freda 承担起了制作全校旗帜的工作。旗帜的制作方法是这样的：Freda</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一共有C 种颜色的布条，每种布条都有无数个，你可以认为这些布条的长、宽、厚都相等，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">只有颜色可能不同。每个旗帜都是由一些布条横向拼接起来的，如图所示，图上所示的是一</span><br/>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">面红、黄、蓝三种颜色布条拼接的旗帜：</span> 
</p>
<p>
	<img src="/upload/image/20120823/20120823172253_43808.png" alt=""/> 
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">布条数目不同的旗帜显然是不同的。对于布条数目都为T 的两面旗帜，如果存在从左到</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">右第i(0<i<=n)个布条颜色不同，那么就认为这两面旗帜是不同的。旋转或翻转后才相同的< span=""><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">旗帜被认为是不同的旗帜，比方说，“红黄蓝”和“蓝黄红”被认为是不同的旗帜。有的时候，</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一些颜色放在相邻的位置上会显得很不好看，比方说红色和绿色放在一起就很不好看。作为</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一个完美主义者，Freda 可不想这样。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">全校共有N 个班级，不同的班级必须使用不同的旗帜，Freda 也就需要制作N 面不同的</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">旗帜了。和谐起见，Freda 想让使用布条数目最多的那面旗帜使用的布条数目最少，请你帮</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">助Freda 计算一下，在避免了不好看的情况之后，使用布条数目最多的那面旗帜最少要用多</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">少布条。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入格式</span> </i<=n)个布条颜色不同，那么就认为这两面旗帜是不同的。旋转或翻转后才相同的<></span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">第一行两个整数N，C，表示班级的数目和Freda 拥有C 种颜色的布条。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">接下来C 行，每行一个长度为C 的字符串，每个字符都为’0’或’1’，第i 行第j 个</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">字符表示第i 种颜色和第j 种颜色是否能够相邻。如果能，第i 行第j 个字符为’1’，否则</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">为’0’.保证第i 行第j 个字符与第j 行第i 个字符相同。</span>
</p>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出格式</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">一行一个整数，表示制作了N 面不同的旗帜的情况下，使用布条数目最多的那面旗帜最</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">少需要多少布条。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输入样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">10 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">11</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">11</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">输出样例</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;">3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"></span><span style="font-family:&#39;Microsoft YaHei&#39;;font-size:14px;"></span> 
</p>
