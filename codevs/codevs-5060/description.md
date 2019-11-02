<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">情人节到了，情侣们也活跃起来了。这不，GoldenSun和Yoyo_Yao分到了同一个班上（真有缘）。这天，GoldenSun专门跑到了花店，为Yoyo_Yao选了999支玫瑰花（-_-|||），可当GoldenSun说了一大堆肉麻的话，正准备把花送给Yoyo_Yao时，班主任DuBowen进来了，无奈的GoldenSun只得从自己的位子上把花传给Yoyo_Yao。如果一整束传，不但比较抢眼，说不定还会被中途的一些八卦的人抢走，所以GoldenSun只能一支一支的传。</span></p><p style=""><span style="">已知GoldenSun他们班的座位是一个矩形，GoldenSun的位子在(x,m)，Yoyo_Yao的位子在(y,n)，传玫瑰时，只能纵横传而不能斜传（更不能扔）。又知GoldenSun班上的同学很八卦，每经过一个同学传时，玫瑰花就会扣去一定的成长值（玫瑰先开始有个成长值），即那个同学的八卦度，当玫瑰的成长值不大于0时，玫瑰就会凋零。GoldenSun希望自己的心血不要白费，即所有的玫瑰花都能传到Yoyo_Yao手中，所以如果有这种情况，GoldenSun就会自己冒着风险送这朵玫瑰。</span></p><p style=""><span style="">请你帮GoldenSun找到一条令玫瑰成长值为最高的路线，让GoldenSun能向Yoyo_Yao在情人节之际表达自己的爱意。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入第一行有2个用空格隔开的整数a和b，表示班里有a行b列（1&lt;=a,b&lt;=90）。</span></p><p style=""><span style="">第二行有四个用空格隔开的整数x,m,y,n，(x,m)为GoldenSun的座位，(y,n)为Yoyo_Yao的座位。（1&lt;=x,y&lt;=a;1&lt;=m,n&lt;=b） </span></p><p style=""><span style="">第三行有一个整数love为单支玫瑰的最初成长值。(0&lt;love&lt;=maxlongint)</span></p><p><span style="">来的a行是一个a*b的矩阵，矩阵中第i行j列的正整数表示坐在第i行j列的学生的八卦程度，每行的b个整数之间用空格隔开。（当然他们两个人的八卦程度为0）</span></p><p style=""><span style="">八卦程度(0&lt;=bg&lt;=love)</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">输出共一行，包含一个整数，表示单支玫瑰最后成长值的最大值。</span></p><p style="text-indent:28px"><span style="font-family:宋体">如果是GoldenSun自己送，则输出love，即单支玫瑰的最初成长值。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2 2</span></p><p style=""><span style="">1 1 2 2</span></p><p style=""><span style="">3</span></p><p style=""><span style="">0 1</span></p><p style=""><span style="">1 0</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">2</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见输入输出</p>
</div>
</div>