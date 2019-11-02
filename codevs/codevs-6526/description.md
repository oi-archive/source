<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>Dr. Evil kidnapped Mahmoud and Ehab in the evil land because of their performance in the Evil Olympiad in Informatics (EOI). He decided to give them some problems to let them go.</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>Dr. Evil is interested in sets, He has a set of n integers. Dr. Evil calls a set of integers evil if the MEX of it is exactly x. the MEX of a set of integers is the minimum non-negative integer that doesn't exist in it. For example, the MEX of the set {0, 2, 4} is 1 and the MEX of the set {1, 2, 3} is 0 .</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>Dr. Evil is going to make his set evil. To do this he can perform some operations. During each operation he can add some non-negative integer to his set or erase some element from it. What is the minimal number of operations Dr. Evil has to perform to make his set evil?</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>Evil博士因为Mahmoud和Ehab在Evil Olympiad in Informatics（EOI）上的表现而在恶魔之地绑架了他们。 他决定给他们一些问题再让他们走。</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>Evil博士对集合感兴趣，他有一个包括n个整数的集合。 如果这个集合的MEX正好是x，Evil博士会认为这个整数集合邪恶。</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>一组整数的MEX是集合中不存在的最小的自然数。 例如，集合{0,2,4}的MEX为1，集合{1,2,3}的MEX为0。</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>邪恶的恶魔为了让他的集合变得邪恶，他可以执行一些操作。 在每个操作期间，他可以向集合添加一些自然数或从中删除一些自然数。 Evil博士最少能操作多少次使得集合邪恶？</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line contains two integers n and x (1 ≤ n ≤ 100, 0 ≤ x ≤ 100) — the size of the set Dr. Evil owns, and the desired MEX.</p><p><br></p><p>The second line contains n distinct non-negative integers not exceeding 100 that represent the set.</p><p><br></p><p>输入的第一行包括两个整数 n 和 x (1≤n≤100,0≤x≤100) — Evil博士的集合的元素个数，和这个集合的MEX.</p><p><br></p><p>输入的第二行包括 n 个自然数，代表Evil博士拥有的集合。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box; text-indent: 2em; color: rgb(51, 51, 51); font-family: &quot;Times New Roman&quot;, Times, &quot;Microsoft YaHei&quot;, &quot;WenQuanYi Micro Hei&quot;, &quot;Microsoft YaHei UI&quot;, serif; font-size: 14px; background-color: rgb(255, 255, 255);">The only line should contain one integer — the minimal number of operations Dr. Evil should perform.</p><p style="margin-top: 0px; margin-bottom: 10px; white-space: normal; box-sizing: border-box; text-indent: 2em; color: rgb(51, 51, 51); font-family: &quot;Times New Roman&quot;, Times, &quot;Microsoft YaHei&quot;, &quot;WenQuanYi Micro Hei&quot;, &quot;Microsoft YaHei UI&quot;, serif; font-size: 14px; background-color: rgb(255, 255, 255);">一行一个整数，为Evil博士操作次数的最小值。</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>Test #1:</p><p><br></p><p>5 3</p><p>0 4 5 6 7</p><p><br></p><p>Test #2:</p><p><br></p><p>1 0</p><p>0</p><p><br></p><p>Test #3:</p><p><br></p><p>5 0</p><p>1 2 3 4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Test #1:</p><p><br></p><p>2</p><p><br></p><p>Test #2:</p><p><br></p><p>1</p><p><br></p><p>Test #3:</p><p><br></p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>For the first test case Dr. Evil should add 1 and 2 to the set performing 2 operations.</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>For the second test case Dr. Evil should erase 0 from the set. After that, the set becomes empty, so the MEX of it is 0.</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>In the third test case the set is already evil.</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>第一组样例，Evil博士应该将1,2加进集合，共两个操作</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>第二组样例，Evil博士应该删除数字0，这时集合空，MEX为0</p><p style='font-family: "Times New Roman", Times, "Microsoft YaHei", "WenQuanYi Micro Hei", "Microsoft YaHei UI", serif;'>第三组样例已经是邪恶的了，无需操作</p><p><br></p>
</div>
</div>