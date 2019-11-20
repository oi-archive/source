# 

 
 # 题目背景 
水题No.4 

 
 # 题目描述 
lyd学会了使用扑克DIY占卜。方法如下：一副去掉大小王的扑克共52张，打乱后均分为13堆，编号1~13，每堆4张，其中第13堆称作“生命牌”，也就是说你有4条命。这里边，4张K被称作死神。<BR>初始状态下，所有的牌背面朝上扣下。<BR>流程如下：<BR>1.抽取生命牌中的最上面一张(第一张)。<BR>2.把这张牌翻开，正面朝上，放到牌上的数字所对应编号的堆的最上边。(例如抽到2，正面朝上放到第2堆牌最上面，又比如抽到J，放到第11堆牌最上边，注意是正面朝上放)<BR>3.从刚放了牌的那一堆最底下(最后一张)抽取一张牌，重复第2步。（例如你上次抽了2，放到了第二堆顶部，现在抽第二堆最后一张发现是8，又放到第8堆顶部.........）<BR><BR>4.在抽牌过程中如果抽到K，则称死了一条命，就扔掉K再从第1步开始。<BR>5.当发现四条命都死了以后，统计现在每堆牌上边正面朝上的牌的数目，只要同一数字的牌出现4张正面朝上的牌(比如4个A)，则称“开了一对”，当然4个K是不算的。<BR>6.统计一共开了多少对，开了0对称作"极凶"，1~2对为“大凶”，3对为“凶”，4~5对为“小凶”，6对为“中庸”，7~8对“小吉”，9对为“吉”，10~11为“大吉”，12为“满堂开花，极吉”。<BR><BR>如果还不明白，就去看样例把。。。 

 
 # 输入格式 
一共13行，为每堆牌的具体牌是什么(不区分花色只区分数字)，每堆输入的顺序为从上到下。<BR>为了便于读入，用0代表10，那么A，J，Q，K(大写)就不用说了吧。。。 

 
 # 输出格式 
一共开了几对。 

 
 # 提示 
注解：第一条命死后前12堆牌变成了这个样子：<BR>A&nbsp;A&nbsp;A&nbsp;8<BR>K&nbsp;5&nbsp;3&nbsp;2<BR>3&nbsp;9&nbsp;6&nbsp;0<BR>4&nbsp;4&nbsp;3&nbsp;4<BR>5&nbsp;5&nbsp;3&nbsp;4<BR>6&nbsp;6&nbsp;5&nbsp;6<BR>7&nbsp;7&nbsp;7&nbsp;7&nbsp;<BR>8&nbsp;8&nbsp;8&nbsp;9<BR>9&nbsp;9&nbsp;0&nbsp;0<BR>0&nbsp;K&nbsp;J&nbsp;J<BR>J&nbsp;Q&nbsp;A&nbsp;Q//抽到这里的K死掉了<BR>J&nbsp;Q&nbsp;2&nbsp;2<BR>第二条命由于K在生命牌中，所以直接死掉，不变。<BR>第三条命死后前12堆牌变成了这个样子：<BR>A&nbsp;A&nbsp;A&nbsp;A<BR>2&nbsp;2&nbsp;2&nbsp;K<BR>3&nbsp;3&nbsp;3&nbsp;3<BR>4&nbsp;4&nbsp;4&nbsp;4<BR>5&nbsp;5&nbsp;5&nbsp;5<BR>6&nbsp;6&nbsp;6&nbsp;6<BR>7&nbsp;7&nbsp;7&nbsp;7&nbsp;<BR>8&nbsp;8&nbsp;8&nbsp;8<BR>9&nbsp;9&nbsp;9&nbsp;9<BR>0&nbsp;0&nbsp;0&nbsp;0//抽到这里的K死掉了<BR>J&nbsp;J&nbsp;J&nbsp;Q<BR>Q&nbsp;Q&nbsp;J&nbsp;Q<BR>第四条命死后前12堆牌变成了这个样子：<BR>A&nbsp;A&nbsp;A&nbsp;A<BR>2&nbsp;2&nbsp;2&nbsp;2//抽到这里的K死掉了<BR>3&nbsp;3&nbsp;3&nbsp;3<BR>4&nbsp;4&nbsp;4&nbsp;4<BR>5&nbsp;5&nbsp;5&nbsp;5<BR>6&nbsp;6&nbsp;6&nbsp;6<BR>7&nbsp;7&nbsp;7&nbsp;7&nbsp;<BR>8&nbsp;8&nbsp;8&nbsp;8<BR>9&nbsp;9&nbsp;9&nbsp;9<BR>0&nbsp;0&nbsp;0&nbsp;0<BR>J&nbsp;J&nbsp;J&nbsp;Q<BR>Q&nbsp;Q&nbsp;J&nbsp;Q<BR>最后发现在所有已经正面朝上的牌中，A&nbsp;2&nbsp;3&nbsp;4&nbsp;5&nbsp;6&nbsp;7&nbsp;8&nbsp;10这9对牌“开”了，（注意，第9堆牌中的最后一张虽然也是9，但是并没有被翻开！所以不能算）因此输出9，喔，出题人Lyd的运势为“吉”哦·T_T。<BR> 
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
<tr><td>//这是出题人随手写下的数据，看看他的运势如何吧...
8 5 A A
K 5 3 2
9 6 0 6
3 4 3 4
3 4 4 5
5 6 7 6
8 7 7 7
9 9 8 8
9 0 0 0
K J J J
Q A Q K
J Q 2 2
A K Q 2




</td><td>9</td></tr></table>
