<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>最近，阿<span style="font-family: 'Times New Roman';">Q</span><span style="">开了一间宠物收养所。收养所提供两种服务：收养被主人遗弃的宠物和让新的主人领养这些宠物。 </span><br>每个领养者都希望领养到自己满意的宠物，阿<span style="font-family: 'Times New Roman';">Q</span><span style="">根据领养者的要求通过他自己发明的一个特殊的公式，得出该领养者希望领养的宠物的特点值</span><span style="font-family: 'Times New Roman';">a</span><span style="">（</span><span style="font-family: 'Times New Roman';">a</span><span style="">是一个正整数，</span><span style="font-family: 'Times New Roman';">a&lt;2^31</span><span style="">），而他也给每个处在收养所的宠物一个特点值。这样他就能够很方便的处理整个领养宠物的过程了，宠物收养所总是会有两种情况发生：被遗弃的宠物过多或者是想要收养宠物的人太多，而宠物太少。 </span><br>1<span style="">． 被遗弃的宠物过多时，假若到来一个领养者，这个领养者希望领养的宠物的特点值为</span><span style="font-family: 'Times New Roman';">a</span><span style="">，那么它将会领养一只目前未被领养的宠物中特点值最接近</span><span style="font-family: 'Times New Roman';">a</span><span style="">的一只宠物。（任何两只宠物的特点值都不可能是相同的，任何两个领养者的希望领养宠物的特点值也不可能是一样的）如果有两只满足要求的宠物，即存在两只宠物他们的特点值分别为</span><span style="font-family: 'Times New Roman';">a-b</span><span style="">和</span><span style="font-family: 'Times New Roman';">a+b</span><span style="">那么领养者将会领养特点值为</span><span style="font-family: 'Times New Roman';">a-b</span><span style="">的那只宠物。 </span><br>2<span style="">． 收养宠物的人过多，假若到来一只被收养的宠物，那么哪个领养者能够领养它呢？能够领养它的领养者，，是那个希望被领养宠物的特点值最接近该宠物特点值的领养者，如果该宠物的特点值为</span><span style="font-family: 'Times New Roman';">a</span><span style="">，存在两个领养者他们希望领养宠物的特点值分别为</span><span style="font-family: 'Times New Roman';">a-b</span><span style="">和</span><span style="font-family: 'Times New Roman';">a+b</span><span style="">，那么特点值为</span><span style="font-family: 'Times New Roman';">a-b</span><span style="">的那个领养者将成功领养该宠物。 </span><br><br>一个领养者领养了一个特点值为<span style="font-family: 'Times New Roman';">a</span><span style="">的宠物，而它本身希望领养的宠物的特点值为</span><span style="font-family: 'Times New Roman';">b</span><span style="">，那么这个领养者的不满意程度为</span><span style="font-family: 'Times New Roman';">abs(a-b)</span><span style="">。 </span><br><br><br>【任务描述】 <br>你得到了一年当中，领养者和被收养宠物到来收养所的情况，希望你计算所有收养了宠物的领养者的不满意程度的总和。这一年初始时，收养所里面既没有宠物，也没有领养者。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个正整数<span style="font-family: 'Times New Roman';">n</span><span style="">，</span><span style="font-family: 'Times New Roman';">n&lt;=80000</span><span style="">，表示一年当中来到收养所的宠物和领养者的总数。接下来的</span><span style="font-family: 'Times New Roman';">n</span><span style="">行，按到来时间的先后顺序描述了一年当中来到收养所的宠物和领养者的情况。每行有两个正整数</span><span style="font-family: 'Times New Roman';">a, b</span><span style="">，其中</span><span style="font-family: 'Times New Roman';">a=0</span><span style="">表示宠物，</span><span style="font-family: 'Times New Roman';">a=1</span><span style="">表示领养者，</span><span style="font-family: 'Times New Roman';">b</span><span style="">表示宠物的特点值或是领养者希望领养宠物的特点值。（同一时间呆在收养所中的，要么全是宠</span><span style="">物，要么全是领养者，这些宠物和领养者的个数不会超过</span><span style="font-family: 'Times New Roman';">10000</span><span style="">个）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p15">仅有一个正整数，表示一年当中所有收养了宠物的领养者的不满意程度的总和<span style="font-family: 'Times New Roman';">mod&nbsp;1000000</span><span style="font-family: 宋体;">以后的结果。</span></p>

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
<p>0 2</p>
<p>0 4</p>
<p>1 3</p>
<p>1 2</p>
<p>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>(abs(3-2) + abs(2-4)=3<span style="">，最后一个领养者没有宠物可以领养</span><span style="font-family: 'Times New Roman';">)</span></p>
</div>
</div>