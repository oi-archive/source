
# Description

<div class="content"><div>很多年前你创立了这家公司，幸运地是它经营地非常成功。出于企业发展的考虑，你注意到你需要通过更有组织性的方式来管理你的雇员们，并且决定成立一些小组，为这些小组分配雇员。</div>
<div>现在你准备成立 n 个小组，每个小组对应公司的一个项目。有时候你会在分配成员时受到一些限制。例如，某一个小组由另一个小组的高级成员组成时前者是后者的子集、某两个项目相关程度十分高时二者对应的小组成员相同、为了避免腐败使得某两个小组的成员不能完全相同、出于安全考虑使得某两个小组没有公共成员、出于合作考虑使得某两个小组必须有公共成员等等。</div>
<div>总而言之，令 X_i (i=1,2,⋯,n)  表示第 i 个小组的成员集合，你可能会在分配成员时受到以下五种类型的限制：</div>
<div>X_i⊆X_j</div>
<div>X_i=X_j</div>
<div>X_i≠X_j</div>
<div>X_i∩X_j=∅</div>
<div>X_i∩X_j≠∅</div>
<div>由于你已经列出了所有的限制，所以你可以知道你是否能够分配雇员满足所有的限制，很可能的是你无法满足所有的限制。因此限制被你按照优先级排了序，你希望知道最多能满足多少个优先级较高的限制。</div>
<div>你不需要考虑员工的能力，换句话说，你可以指定任何人去任何小组，而且你可以成立一个没有人的小组，甚至只要你愿意，你可以解雇和聘请无限多的雇员。</div>
<div>例如第一组样例，通过分配相同的雇员到前三个集合，你可以满足前三个限制，但无论如何都无法满足第四个限制，因此第一组样例的答案是三。</div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">输入包含多组测试数据。每组数据的第一行包含两个正整数 n(2≤n≤100)  和 m(1≤m≤10000)  ，表示有 n 个小组和 m 个限制。</div>
<div style="font-size: 11.8181819915771px;">接下来 m 行，每行包含三个正整数 s(1≤s≤5),i(1≤i≤n)  和 j(1≤j≤n,i≠j)  ，表示第 i 个集合和第 j 个集合有上述的第 s 种限制。限制按照优先级从高到低给出。</div>
<div style="font-size: 11.8181819915771px;">输入以两个零作为结尾。</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">对于每组数据，输出一行一个整数表示最多同时能满足的优先级较高的限制数量。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 2 1<br/>
1 3 2<br/>
1 1 3<br/>
3 1 3<br/>
1 3 1<br/>
4 4<br/>
1 2 1<br/>
1 3 2<br/>
1 1 3<br/>
4 1 3<br/>
4 5<br/>
1 2 1<br/>
1 3 2<br/>
1 1 3<br/>
4 1 3<br/>
5 1 3<br/>
2 3<br/>
1 1 2<br/>
2 1 2<br/>
3 1 2<br/>
0 0 </span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
4<br/>
4<br/>
2 </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tangjz提供试题">鸣谢Tangjz提供试题</a></p></div>

