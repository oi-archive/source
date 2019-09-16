# 题目描述


<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【题目背景】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第二届『Citric杯』NOIP提高组模拟赛第一题</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;"><span></span>【题目描述】<span></span></span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Lemon认为在第一届『Citric』杯模拟赛中出的题目太简单了，于是他决定，这次要给参赛选手们一个下马威！ ^_^</span><br/>
<br/>
<br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Lemon手上有一个长度为n的数列，第i个数为xi。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">他现在想知道，对于给定的a,b,c，他要找到一个i，使得a*(i+1)*xi^2+(b+1)*i*xi+(c+i)=0成立。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">如果有多个i满足，Lemon想要最小的那个i。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">Lemon有很多很多组询问需要你回答，多到他自己也不确定有多少组。<span style="color:#337FE5;">所以在输入数据中a=b=c=0标志着Lemon的提问的结束</span>。</span><br/>
<br/>
<br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">更加糟糕的是，Lemon为了加大难度，决定对数据进行加密以防止离线算法的出现。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">假设你在输入文件中读到的三个数为a0,b0,c0，那么Lemon真正要询问的a=a0+lastans,b=b0+lastans,c=c0+lastans.</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">lastans的值是你对Lemon的前一个询问的回答。如果这是第一个询问，那么lastans=0</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">所有的询问都将会按上述方式进行加密，<span style="color:#337FE5;">包括标志着询问的结束的那个询问也是这样</span>。</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入格式】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件第一行包含一个正整数n，表示数列的长度。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">输入文件第二行包含n个整数，第i个数表示xi的值。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">接下来若干行，每行三个数，表示加密后的a,b,c值（也就是上文所述的a0,b0,c0）</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出格式】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">包含若干行，第i行的值是输入文件中第i个询问的答案。注意，你不需要对标志着询问结束的那个询问作答。</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">同时，标志着询问结束的询问一定是输入文件的最后一行。也就是，输入文件不会有多余的内容。</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输入样例】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-2 3 1 -5 2 </span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-5 -4 145</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-1 -6 -509</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-9 -14 40</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-3 -13 21</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">-3 -3 -3</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【输出样例】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">5</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">4</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">3</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【样例解释】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第一个询问中，真实的a=-5+0=-5，b=-4+0=-4，c=145+0=145（第一个询问中lastans=0）</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">带入发现，i=5时，-5*(5+1)*2^2+(-4+1)*5*2+145+5=0，而其他的i均不符合条件。所以答案是5.</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第二个询问中，真实的a=-1+5=4,b=-6+5=-1,c=-509+5=-504（lastans是上一个询问的答案的值，也就是5）</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">经带入发现，i=4时，4*(4+1)*(-5)^2+(-1+1)*4*(-5)+(-504)+4=0，满足条件，而其他的i均不满足条件，所以答案是4.</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">同理，第三个询问中真实的a=-5,b=-10,c=44.答案i=3</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第四个询问中真实的a=0,b=-10,c=24，答案i=3</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">第五个询问中真实的a=0,b=0,c=0，此时我们发现这是一个标志着结束的询问，这个询问我们无需作出回答。</span><br/>
<br/>
<br/>
<h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">【数据规模】</span> 
</h3>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">时间限制3s</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于40%的数据，满足N&lt;=1000，需要作出回答的询问个数不超过1000.</span><br/>
<span style="font-size:16px;font-family:&#39;Microsoft YaHei&#39;;">对于100%的数据，满足N&lt;=50000，需要作出回答的询问个数不超过500000，xi的绝对值不超过30000，解密后的a的绝对值不超过50000，解密后的b的绝对值不超过10^8，解密后的c的绝对值不超过10^18.</span><br/>
<br/>
<br/>
