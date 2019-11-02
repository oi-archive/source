# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;但是，命运之神是不会偏向任何一方的。<BR>&nbsp;&nbsp;&nbsp;&nbsp;正在烦恼的人不止是HF一个，Winter联盟的PL也同样在烦恼。<BR>&nbsp;&nbsp;&nbsp;&nbsp;是的，刚刚打完一场激烈的战斗，现在又要和Summer进行一次激战，这实在是令人头疼。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是，战争已是弦上之箭，不得不发了。<BR>&nbsp;&nbsp;&nbsp;&nbsp;既然上次战争是时空炸弹开头的，这次PL也决定用时空炸弹作开场白。<BR>&nbsp;&nbsp;&nbsp;&nbsp;“让他们看看，大量的时空炸弹有多么豪华的攻击力吧！”<BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;由于技术问题，时空炸弹现在只可以安放在直线y=0上的任意一点，同样，它的爆炸范围为r。<BR>&nbsp;&nbsp;&nbsp;&nbsp;（有不明白者，参看P1300时空炸弹或本题注释）<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是，经过试验，PL了解了时空炸弹的稳定性，而且也彻底明白了时空炸弹的巨大威力，所以Winter联盟投入重金，购买了k颗时空炸弹，那么，要怎样才能给敌人以最大的杀伤呢？<BR>&nbsp;&nbsp;&nbsp;&nbsp;敌人的阵地可以视作一个平面，由于激战，这里只剩敌人的战舰。这k颗时空炸弹可以被设置在直线y=0上的任意一点，那么所有能被炸到的战舰c，都会被摧毁，现在要求能够最多摧毁多少价值的战舰。<BR>&nbsp;&nbsp;&nbsp;&nbsp;但是，为了产生豪华的效果，PL希望两颗相邻布置的炸弹之间（设两炸弹的横坐标为x1,x2，则在直线x=x1和直线x=x2称为之间，不包括x=x1和x=x2）没有被摧毁的敌舰数量不要超过t。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行四个整数n,k,r,t分别表示敌人的战舰数量，时空炸弹的数量，PL所希望的两炸弹爆炸中间存活的敌舰的最小数，炸弹的爆炸半径。<BR>&nbsp;&nbsp;&nbsp;&nbsp;接下来n行，每行三个整数x,y,v，分别表示敌舰的横纵坐标和敌舰的价值。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;一个数，为最多能摧毁多少价值的战舰。<BR> 

 
 # 提示 
&nbsp;&nbsp;&nbsp;&nbsp;一个设定在(x,y)的爆炸半径为r的时空炸弹可以攻击到所有战舰i&nbsp;{&nbsp;(&nbsp;x&nbsp;-&nbsp;xi&nbsp;)&nbsp;^&nbsp;2&nbsp;+&nbsp;(&nbsp;y&nbsp;-&nbsp;yi&nbsp;)&nbsp;^&nbsp;2&nbsp;&lt;=&nbsp;r&nbsp;^&nbsp;2&nbsp;}&nbsp;。<BR>&nbsp;&nbsp;&nbsp;&nbsp;因为Winter的低级程序员已经处理了数据，所以不会出现无论如何都不能攻击到的战舰，即abs(&nbsp;yi&nbsp;)&nbsp;&lt;=&nbsp;r。<BR>&nbsp;&nbsp;&nbsp;&nbsp;20%的数据：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;20&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;1000<BR>&nbsp;&nbsp;&nbsp;&nbsp;100%的数据：1&nbsp;&lt;=&nbsp;k&nbsp;&lt;=&nbsp;1000&nbsp;,&nbsp;1&nbsp;&lt;=&nbsp;n&nbsp;&lt;=&nbsp;1000&nbsp;,&nbsp;0&nbsp;&lt;=&nbsp;r&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;-10^9&nbsp;&lt;=&nbsp;xi,t&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;abs(&nbsp;yi&nbsp;)&nbsp;&lt;=&nbsp;r。<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;由于均是敌方战舰，所以&nbsp;1&nbsp;&lt;=&nbsp;vi&nbsp;&lt;=&nbsp;10^6<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR>&nbsp;&nbsp;&nbsp;&nbsp;“敌人来了吗？”Winter联盟将军们窃窃私语。<BR>&nbsp;&nbsp;&nbsp;&nbsp;“不，但快了。”Winter来联盟被誉奇才的副指挥官December看着手上那张古老的蓝色星云的图片，既像是在回答将军们的问题，又像在自言自语。<BR>&nbsp;&nbsp;&nbsp;星际战争系列，Winter联盟。<BR>&nbsp;&nbsp;&nbsp;&nbsp;EZ_gx原创。（P1300时空炸弹是本题序幕）<BR> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3 2 1 0
0 0 10
3 0 1
6 0 10
</td><td>11
</td></tr></table>
