# 

 
 # 题目背景 
<p><span style="line-height: 20.7999992370605px;">小</span><span style="line-height: 20.7999992370605px;">天很喜欢玩球球大作战这个游戏，大家也应该都玩过。游戏规则是：移动自己的球，移动到别人的球（一定要比自己的球小）的位置上，就可以吃掉别人的球，把别人的球的体积</span><span style="line-height: 20.7999992370605px;">值加到自己的球上</span><span style="line-height: 20.7999992370605px;">。还有分身、吐球等功能，但本题不考虑。</span></p> 

 
 # 题目描述 
<p><span style="line-height: 1.6em;">作为一个OIer，小天给自己做了一个超牛的外挂：让自己的球瞬间移动到场内的任何位置！！！这意味着小天可以瞬间移动到任何一个比自己小的球上，把它吃掉。现在，小天只用外挂来瞬移，每次瞬移只能吃掉一个球。</span></p>

<p>现在房间内有n个大小不一的球，小天至少瞬移吃球多少次，才能比剩下的所有球都大呢？</p>

<p>样例1：</p>

<p>输入</p>

<p>3&nbsp;5</p>

<p>10&nbsp;7&nbsp;4</p>

<p>输出</p>

<p>2</p>

<p>样例2：</p>

<p>输入3&nbsp;5</p>

<p>12&nbsp;2&nbsp;4</p>

<p>输出</p>

<p>-1</p>

<p>11</p> 

 
 # 输入格式 
<p>第一行两个正整数n,s，分别表示场内别人球的个数、小天的球的初始大小。</p>

<p>第二行n个正整数，表示这些球各自的大小。</p> 

 
 # 输出格式 
<p>一行一个整数，表示变成第一至少需要吃人的次数。如果怎么也无法变成第一，则输出两行，第一行为-1，第二行为最大能达到的体积值。</p> 

 
 # 提示 
<p><strong>数据限制：</strong></p>

<p>n&lt;=30000</p>

<p>其他数字保证32位能存下</p> 
