# 

 
 # 题目背景 
<p>原创题</p>

<p>Peppy最近兴致很高，翻出多年前的游戏Megaman，挑战传说中的Boss&mdash;&mdash;Airman</p> 

 
 # 题目描述 
<p>Peppy当然知道这个Boss的难度很大，所以他机智地利用了游戏bug，把自己的HP改成了-1，于是就永远减不到0了。而Airman的初始HP依然为<strong>N</strong>。</p>

<p>Airman也很机智，发现砍Peppy并没有什么卵用，所以就把全部的精力放到了防御上。</p>

<p>每一回合Peppy都会对Airman展开一次很厉害的攻击，可以对Airman造成1点伤害，当Airman的HP减少到0的时候Peppy就获胜了。</p>

<p>然而Airman的防御技能也很厉害，每一回合有<strong>p/q</strong>的概率使Peppy造成的伤害变成-1点。</p>

<p>Peppy等下还要去更新osu!，不希望游戏永远进行下去。于是他找到了你，希望你告诉他游戏结果大概会怎样。</p> 

 
 # 输入格式 
<p>输入共1行&nbsp;三个整数N,&nbsp;p,&nbsp;q</p> 

 
 # 输出格式 
<p>如果游戏期望不会永远进行下去，输出一行为游戏期望进行的回合数。</p>

<p>否则输出一行，为Peppy最终获胜的概率。</p>

<p>由于没有Special&nbsp;Judge，输出请保留6位小数</p> 

 
 # 提示 
<p>输入范围：</p>

<p>对于10%的数据&nbsp;p&nbsp;=&nbsp;0&nbsp;或&nbsp;1,&nbsp;q&nbsp;=&nbsp;1</p>

<p>对于30%的数据&nbsp;N&nbsp;&lt;=&nbsp;10</p>

<p>对于70%的数据&nbsp;N&nbsp;&lt;=&nbsp;1000</p>

<p>对于100%的数据&nbsp;0&nbsp;&lt;=&nbsp;N&nbsp;&lt;=&nbsp;10^9&nbsp;,&nbsp;gcd(p,&nbsp;q)&nbsp;=&nbsp;1,0&nbsp;&lt;=&nbsp;p&nbsp;&lt;=&nbsp;q&nbsp;&lt;=&nbsp;10^9</p> 
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
<tr><td>1 1 1

</td><td>0.000000

</td></tr><tr><td>3 51 100

</td><td>0.886906

</td></tr><tr><td>1 0 1

</td><td>1.000000

</td></tr><tr><td>3 49 100

</td><td>76.500000

</td></tr><tr><td>1000000000 1 2

</td><td>1.000000

</td></tr></table>
