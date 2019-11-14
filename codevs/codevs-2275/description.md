<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>王大哥是一个很闷骚的男人，总是不停地忧虑。现在他又开始忧虑了。</p>
<p>王大哥手上有一个长度为n的数列，第i个数为xi。</p>
<p>他现在想知道，对于给定的a,b,c，他要找到一个i，使得a*(i+1)*xi^2+(b+1)*i*xi+(c+i)=0成立。如果有多个i满足，他想要最小的那个i。</p>
<p>王大哥有很多很多组询问需要你回答，多到他自己也不确定有多少组。所以在输入数据中a=b=c=0标志着王大哥的提问的结束。</p>
<p>更加糟糕的是，他十分闷骚，决定对数据进行加密以防止离线算法的出现。</p>
<p>假设你在输入文件中读到的三个数为a0,b0,c0，那么王大哥真正要询问的a=a0+lastans,b=b0+lastans,c=c0+lastans.</p>
<p>lastans的值是你对他的前一个询问的回答。如果这是第一个询问，那么lastans=0</p>
<p>所有的询问都将会按上述方式进行加密，包括标志着询问的结束的那个询问也是这样。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行包含一个正整数n，表示数列的长度。</p>
<p>输入文件第二行包含n个整数，第i个数表示xi的值。</p>
<p>接下来若干行，每行三个数，表示加密后的a,b,c值（也就是上文所述的a0,b0,c0）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含若干行，第i行的值是输入文件中第i个询问的答案。注意，你不需要对标志着询问结束的那个询问作答。</p>
<p>同时，标志着询问结束的询问一定是输入文件的最后一行。也就是，输入文件不会有多余的内容。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>-2 3 1 -5 2</p>
<p>-5 -4 145</p>
<p>-1 -6 -509</p>
<p>-9 -14 40</p>
<p>-3 -13 21</p>
<p>-3 -3 -3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>4</p>
<p>3</p>
<p>3</p>
<p> </p>
<p><strong>样例解释</strong></p>
<p>第一个询问中，真实的a=-5+0=-5，b=-4+0=-4，c=145+0=145（第一个询问中lastans=0）</p>
<p>带入发现，i=5时，-5*(5+1)*2^2+(-4+1)*5*2+145+5=0，而其他的i均不符合条件。所以答案是5.</p>
<p>第二个询问中，真实的a=-1+5=4,b=-6+5=-1,c=-509+5=-504（lastans是上一个询问的答案的值，也就是5）</p>
<p>经带入发现，i=4时，4*(4+1)*(-5)^2+(-1+1)*4*(-5)+(-504)+4=0，满足条件，而其他的i均不满足条件，所以答案是4.</p>
<p>同理，第三个询问中真实的a=-5,b=-10,c=44.答案i=3</p>
<p>第四个询问中真实的a=0,b=-10,c=24，答案i=3</p>
<p>第五个询问中真实的a=0,b=0,c=0，此时我们发现这是一个标志着结束的询问，这个询问我们无需作出回答。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于前4组数据，每组10分，满足N&lt;=1000，需要作出回答的询问个数不超过1000.</p>
<p>对于后2组数据，每组30分满足N&lt;=50000，需要作出回答的询问个数不超过500000，xi的绝对值不超过30000，解密后的a的绝对值不超过50000，解密后的b的绝对值不超过10^8，解密后的c的绝对值不超过10^18.</p>
<p> </p>
</div>
</div>