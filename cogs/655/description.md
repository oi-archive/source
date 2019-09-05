# 题目描述


<p>
<b>【问题描述</b>】
</p>
<div>
去年夏天 Max 去加利福尼亚旅行，他玩的很开心：拍了很多照片、参观了著名的大学、享受了美丽的海滩并且品尝了很多美食，那次旅行如此美妙以至于 Max 计划今年再去一次。 Max 对去年订的那家旅店非常满意，但是他把那个旅店的名片弄丢了，也记不起它的确切名字。于是 Max 在网上搜了一下有关加利福尼亚旅店的信息，搜出一堆结果，你能帮 Max 挑出那些可能是正确的旅店吗？ <br/>
</div>
<div>
【输入格式】
</div>
<div>
<span>输入文件包含若干测试数据序列，每一个序列的格式如下： <br/>
第一行有一个字符串，字符串由‘ * &#39;，‘？&#39;以及字母‘ a &#39; -‘z&#39; 组成，该字符串表示 Max 所能记起来的旅店的名称，符号‘ * &#39;与‘？&#39;是 通配符 ，‘ * &#39;可以匹配 0 个或多个小写字母，‘？&#39;只能匹配一个小写字母。 <br/>
第二行有一个整数 n （ 1 ≤ n ≤ 10000 ），表示 Max 搜到的旅店个数，接下来有 n 行，每一行有一个由小写字母组成的字符串，即旅店名称，每个字符串的长度均不超过 50 。 </span> 
</div>
<div>
【输出格式】
</div>
<p>
对于每个测试数据序列，只需输出一行，包含一个整数，表示与 Max 所记的名称相匹配的名字的个数。
</p>
<div>
【输入样例】
</div>
<div>
输入文件：
</div>
<div>
herbert<br/>
2<br/>
amazon<br/>
herbert<br/>
?er*<br/>
2<br/>
amaZon<br/>
herbert<br/>
*<br/>
2<br/>
amazon<br/>
anything<br/>
hertber?<br/>
2<br/>
amazon<br/>
herber<br/>
</div>
<div>
输出文件：<span> </span> 
</div>
<div>
<span>1<br/>
1<br/>
2<br/>
0</span> 
</div>
<p>
<br/>
</p>