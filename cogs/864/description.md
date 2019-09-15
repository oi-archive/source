# 题目描述


<p>
USACO/ratios(译 by Felicia Crazy)
</p>
<p>
<span id=".E6.8F.8F.E8.BF.B0" class="mw-headline">描述</span> 
</p>
<p>
<br/>
</p>
<p>
农夫约翰从来只用调配得最好的饲料来喂他的奶牛。饲料用三种原料调配成：大麦，燕麦和小麦。他知道自己的饲料精确的配比，在市场上是买不到这样的饲料的。他只好购买其他三种混合饲料（同样都由三种麦子组成），然后将它们混合，来调配他的完美饲料。
</p>
<p>
给出三组整数，表示 大麦：燕麦：小麦 的比例，找出用这三种饲料调配 x：y：z 的饲料的方法。
</p>
<p>
例如，给出目标饲料 3：4：5 和三种饲料的比例：
</p>
<pre>    1:2:3   
    3:7:1  
    2:1:2
</pre>
<p>
你必须编程找出使这三种饲料用量最少的方案，要是不能用这三种饲料调配目标饲料，输出“NONE”。“用量最少”意味着三种饲料的用量（整数）的和必须最小。
</p>
<p>
<br/>
对于上面的例子，你可以用8份饲料1，1份饲料2，和5份饲料3，来得到7份目标饲料：
</p>
<pre>8*(1:2:3) + 1*(3:7:1) + 5*(2:1:2) = (21:28:35) = 7*(3:4:5)
</pre>
<p>
表示饲料比例的整数以及目标饲料的都是小于100的非负整数。表示各种饲料的份数的整数，都小于100。一种混合物的比例不会由其他混合物的比例直接相加得到。
</p>
<span class="mw-headline"></span> 
<p>
<br/>
</p>
<p>
<span id=".E6.A0.BC.E5.BC.8F" class="mw-headline">格式</span> 
</p>
<p>
<br/>
</p>
<p>
<b>PROGRAM NAME</b>: ratios
</p>
<p>
<b>INPUT FORMAT</b>:
</p>
<p>
(file ratios.in)
</p>
<p>
Line 1: 三个用空格分开的整数，表示目标饲料
</p>
<p>
Line 2..4: 每行包括三个用空格分开的整数，表示农夫约翰买进的饲料的比例
</p>
<p>
<b>OUTPUT FORMAT</b>:
</p>
<p>
(file ratios.out)
</p>
<p>
输出文件要包括一行，这一行要么有四个整数，要么是“NONE”。前三个整数表示三种饲料的份数，用这样的配比可以得到目标饲料。第四个整数表示混合三种饲料后得到的目标饲料的份数。
</p>
<span class="mw-headline"></span> 
<p>
<br/>
</p>
<p>
<span id="SAMPLE_INPUT" class="mw-headline">SAMPLE INPUT (ratios.in)</span> 
</p>
<pre>3 4 5
1 2 3
3 7 1
2 1 2 
</pre>
<p>
<span id="SAMPLE_OUTPUT" class="mw-headline">SAMPLE OUTPUT (ratios.out)</span> 
</p>
<p>
8 1 5 7
</p>
<p>
 
</p>
<p>
 
</p>
