# 题目描述


<h3>
【题目背景】
</h3>
<p>
缇欧（CV：水桥香织）：“哇..すごい（死高一）这这.是丽霞小姐的写真集呢”
</p>
<p>
琪雅（CV：钉宫理惠）：“呐呐，兰迪让我看看吗，给我。”
</p>
<p>
兰迪（CV：三木真一郎）：“小孩子不能看的哦，在沙发上别摔着，快下去，阿琪。”
</p>
<p>
艾莉（CV:远藤绫）：“罗伊德？！”
</p>
<p>
罗伊德（CV：柿原彻也）：“啊...艾莉，我什么都不知道...这不是我的”
</p>
<p>
<img src="/upload/image/20170630/20170630202718_53000.jpg" alt=""/> 
</p>
<p>
忙碌了一上午罗伊德本打算去兰迪的房间休息，不料看书过于投入没有注意艾莉在门外敲门，结果......平常被罗伊德冷落的艾莉非常生气，在Tio的帮助下找到了情敌写真集，现在艾莉想看看兰迪房间究竟有多少藏书。
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
<span style="font-size:24px;">    从兰迪屋最里面到兰迪屋子门口地上铺满了x摞书。</span><span style="font-size:24px;">我们近似把它看成一条直线排列。生气的艾莉站在门口不动，命令罗伊德从屋子最里面依次找书，直到找到门口为止。</span> 
</p>
<p>
<span style="font-size:24px;">    妻管严罗伊德只敢按直线从里面走到门口，书是按从内到外的顺序依次按摞标号，</span><span style="font-size:24px;"><strong><span style="font-size:32px;">1，2……x</span></strong>,每摞书有不同的本数<strong><span style="font-size:32px;">ai</span></strong>,</span><span style="font-size:24px;">每两摞书之间又有不同的距离</span><strong style="font-size:24px;"><span style="font-size:32px;">bi</span></strong><span style="font-size:24px;">。</span> 
</p>
<p>
<span style="font-size:24px;">   但是保证他们在一条直线上，防止罗伊德搬书太累，于是让琪雅和缇欧任意站在这条直线上的两个位置，罗伊德把书抱到任意一个女性角色手里的时候相当于清空一次手里的书。</span> 
</p>
<p>
<span style="font-size:24px;">   罗伊德每抱一本书走一个距离单位，艾莉的傲娇指数相应增加 <strong>1</strong>，捡书和将书放到女性角色手里时不增加。</span> 
</p>
<p>
<span style="font-size:24px;">   现在你必须决定在让缇欧和琪雅站在哪里，使得艾莉的傲娇指数最小。</span> 
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<p>
<br/>
</p>
<p>
<br/>
</p>
<p>
输入的第一行为一个正整数x——书的摞数（2≤x≤2*10^4）。
</p>
<p>
书从兰迪屋内最深处到屋的门口按照1，2……x标号。
</p>
<p>
接下来x行，每行有两个正整数（用空格分开）。
</p>
<p>
第i+1行含有：ai——第i摞书的本数和 bi——第i摞书和第i+1摞书之间的距离，（1≤ai ≤1*10^4，0≤bi≤1*10^4)。
</p>
<p>
保证所有书到女性角色手里，且艾莉的傲娇值最高不超过<strong><span style="font-size:18px;">2*10^9</span></strong>。
</p>
<p>
<br/>
</p>
<p>
<br/>
</p>
<h3>
【输出格式】
</h3>
<p>
<br/>
</p>
<p>
输出一个整数
</p>
<p>
艾莉的最终傲娇值
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<p>
2 
</p>
<p>
1 1 
</p>
<p>
1 1
</p>
<h3>
【样例输出】
</h3>
<pre>0</pre>
<h3>
【样例解释】
</h3>
<p>
只有两摞书，第一摞书离第二摞书有一个距离单位，第二摞书离艾莉有一个距离单位。
</p>
<p>
每摞只有一本，让琪雅或缇欧一个站在第一本到第二本中，第二个站在艾莉和第二本中。
</p>
<p>
罗伊德无需抱任何一本书走一个距离单位，所以艾莉的傲娇指数为0。
</p>
<h3>
【提示】
</h3>
<p>
1.书的本数和距离单位不重要，全按1为基本单位。
</p>
<p>
2.所有的女性角色的作用都是一样的，在这里只收书。
</p>
<p>
3.捡书和将书放到女性角色手里时不增加艾莉的傲娇值。
</p>
<p>
4.数据刚开始可能较弱，后续有时间会造加强数据。
</p>
<p>
5.要入坑游戏的私聊....
</p>
<h3>
【来源】
</h3>
<p>
零之轨迹 碧之轨迹
</p>
