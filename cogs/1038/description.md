# 题目描述


<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">树链剖分</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【问题描述】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">其实，本题和树链剖分没有关系。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">作为一名OIer，ZYN和LHC自然要好好利用暑假学习算法、数据结构。某一</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">天，他们在一起研究树链剖分，被FK看到了。FK决定不懂装懂，问了他们一个</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">很奇怪的问题：给你们一棵树，能够拆成的最小的链数是多少？</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">链的定义：一个由X个点和X-1条边组成的连通块，注意X≥1，每个点的</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">度数≤2。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">拆的要求：将原图中的一些边删去，使得每个点属于一条链。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">ZYN笑了笑：“这很简单么。。。只要。。。只要。。。”LHC随声附和“对！</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对！”，可不久两人都陷入了沉思。FK因为难倒了他们而窃喜，实际上他自己</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">也不会做。那么你能帮帮这三个悲催的人么。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">从文件tree.in中读入数据。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第1行有1个数N，表示树的节点的个数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">第2行到第N行，每行两个数X、Y，表示在树上点X与Y之间有边相连。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出到文件tree.out中。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">输出1行，包含1个数，表示最少能拆成的链数。</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 3</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">1 4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">2</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例解释】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">两条链分别是：2-1-3，4</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【数据范围】</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于30%数据，N≤10</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于60%数据，N≤300</span><br/>
<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">对于100%数据，N≤100000</span><br/>
