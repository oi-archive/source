# 题目描述


<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
   <span style="color:#999999;font-size:12px;">“巡音ルカ（巡音露卡、巡音流歌、巡音流香）是CRYPTON FUTURE MEDIA（下略作“CRYPTON”）以Yamaha的VOCALOID 2语音合成引擎为基础开发贩售的虚拟女性歌手软件角色主唱系列的第三作”</span> 
</p>
<p>
<img src="/upload/image/20141224/20141224090809_48554.jpeg" alt=""/> 
</p>
<p>
    在新专辑售发后，巡音收到了vocaloid公司不少的奖金，所以她打算去小吃店买一些喜欢的章鱼丸子来犒劳自己。
</p>
<p>
    小吃店里有n种口味的章鱼丸子，每一种口味的章鱼丸子有自己的价格si和体积vi，并且数量无限，Luka对每一种口味的章鱼丸子都有对应的好感度wi。小吃店的店主是个很会赚钱的人，店主为客人提供一种装章鱼丸子的盒子，这些盒子可以装体积为V的章鱼丸子，但对每个盒子店主会收取盒子单位价格S的费用。
</p>
<p>
    现在Luka手里有数量为m的钱，她想用这些钱买到的章鱼丸子好感度之和最大，并且她为了方便带走，希望所有的章鱼丸子都装到盒子里，Luka想知道达到她愿望时，最大的好感度之和为多少，并需买多少个盒子。
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
第一行四个整数n,m,V,S;
</p>
<p>
接下来n行每行三个整数si,vi,wi；
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
第一行一个整数，表示最大的好感度之和；
</p>
<p>
第二行一个整数，表示好感度之和达到最大时需买多少个盒子；
</p>
<p>
<br/>
</p>
<h3>
【样例输入】
</h3>
<p>
<br/>
</p>
<p>
3 10 5 2
</p>
<p>
3 6 10
</p>
<p>
2 5 4
</p>
<p>
3 2 5
</p>
<p>
<br/>
</p>
<h3>
【样例输出】
</h3>
<p>
 10
</p>
<p>
 1
</p>
<h3>
【样例说明】
</h3>
<p>
此时买一个盒子，买两个第三种口味的章鱼丸子，获得的价钱为10，忽略球体等几何问题对体积的影响，当最高好感度之和相同时，买尽量少的盒子,因为体积超过盒子体积，所以对第一种章鱼丸子不予考虑，可能不让带走吧…
</p>
<h3>
【数据范围】
</h3>
<p>
<br/>
</p>
<p>
1&lt;=n,m&lt;=300;
</p>
<p>
1&lt;=V,vi&lt;=300;
</p>
<p>
1&lt;=S,si&lt;=m;
</p>
<p>
wi在int范围内；
</p>
<p>
<br/>
</p>