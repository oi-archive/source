# 

 
 # 题目描述 
<p>
My country's bigger than most		我们的国家比大部分国家广袤<br>And if asked I boast			如果被问到我会大肆炫耀<br>'Cause I'm really proud			因为我真的很骄傲<br>So I shout it loud			我要放声大叫<br>Though our numbers are few		虽然这裡人烟稀少<br>We will welcome you			我们仍然会欢迎远方的朋友<br><br>Although we don't have history		虽然我们历史不是很悠久<br>Gold medal winning teams		金牌队伍也没有<br>Heroes or prisoners			没有英雄没有罪犯<br>World famous volcanoes			也没有世界着名的火山口<br>Still what we've got's glorious		但是我们仍然十分骄傲<br><br>'Cause we've got			因为我们有<br>Rocks and trees				石头木头<br>And trees and rocks			木头石头<br>And rocks and trees			石头木头<br>And trees and rocks			木头石头<br>And rocks and trees			石头木头<br>And trees and rocks			木头石头<br>And rocks and trees			石头木头<br>And trees and rocks			木头石头<br>And water 				和水&#8943;&#8943;<br>    -The Arrogant Worms, on Canada<br><br>http://www.youtube.com/watch?v=P2Ca-vTapfU<br><br>农夫约翰在穿过北纬49度纬线进入祇有石头木头的土地，加拿大之后，他们的牛发明了一种新游戏来在草地上消磨閒暇时间；因为这个游戏把石头和木头（树）天衣无缝地结合在一起！小牛Ted灰常喜欢这个游戏，可是他的运气是多麽糟糕他总是在这个游戏输给其它的牛。这次，他过来找你帮忙。这个游戏的规则很简单。这个游戏在一个有着1到N (2 <= N <= 10,000)一共N个节点，N-1条边的树上面进行。节点1是树根。除了节点1，节点i有一个父节点P_i (1 <= P_i < i)。一开始，每个节点都有一些石头（除了根节点，根节点没有石头）。具体来说，在游戏刚开始的时候非根节点i恰好有R_i (1 <= R_i <= 1,000)个石头。<br>游戏在两个玩家之间轮流进行，Ted先手。在每一轮，这轮的玩家可以选择一个非根节点，并且把最多L (1 <= L <= 1,000)个石头从这个节点向树根靠近一个单位（也就是说，把这些石头移动到它的父节点处）。并且这个玩家至少需要移动一个石子。当某个玩家没有办法移动石子的时候（也就是所有的石子都移动到节点1），游戏结束，这个玩家失败。Ted需要你的帮助。他得到了一开始一开始游戏的佈局，而且他将会对这个佈局一一进行T (1<= T <= 10,000)次修改。请帮助他确定，在每步修改之后，以这个佈局开局，在双方都用最优策略的前提下他是否能赢得这个游戏。Ted的每次修改由两个数字A_j (1 < A_j <= N)和B_j (1 <= B_j <= 1,000)描述，表示Ted将会把节点A_j的石头数修改为B_j（注意这是一个“设定”操作，既不是“减少”也不是“增加”）。并且询问修改后谁会获胜。注意这些修改会累积，也就是节点A_j的石头数会一直保<br>持在B_j个，知道新的A_j出现。考虑图灵这个例子，数字表示节点的标号，线段表示边。一开始，节点2有5个石头，节点3有3个石头。见图一。<br>第一次改变，Ted从节点2移走2个石头（也就是剩下3），见图二。第二次移动，Ted从节点3移走2个石头（也就是剩下1），注意节点2仍然是2个石头，见图三。<br>   <img border="0" src="/source/joyoi/tyvj-2608/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYwOC9wcm9ibGVtc19pbWFnZXMvMzA1MC8xNzc3LmpwZw==.jpg"><br>你的程序应该确定在以每个状况作为开局时谁将获胜。<br>大约30%的测试数据有N <= 10且T <= 100。并且在Ted每次修改过后树上没有节点会超过5个石头。<br></p> 

 
 # 输入格式 
<p>
* 第1行: 三个整数: N, T 和 L<br><br>* 第2到第N行: 第i行包含两个整数: P_i 和 R_i<br><br>* 第N+1到第N+T行: 第j-N行表示Ted的下一步操作，包含两个整数: A_j 和 B_j<br><br></p> 

 
 # 输出格式 
<p>
* 第1到第T行: 如果在第i次修改后，Ted可以获胜，那麽第i行输出"Yes"，否则输出"No"。<br></p> 
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
<tr><td>3 2 10
1 5
1 3
2 3
3 1
</td><td>No
Yes</td></tr></table>
