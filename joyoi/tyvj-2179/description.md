# 

 
 # 题目描述 
<p>约翰正在装饰他家的圣诞树。圣诞树上有个N&nbsp;个结点，第一个结点是根，其余结点都有唯一的父亲结点，第i&nbsp;个结点的父亲是Pi。由于根没有父亲，所以记P1&nbsp;=&nbsp;&minus;1。<br />
约翰可以在每个结点上挂载装饰物，但费用是变化的。在第i&nbsp;个结点上挂载一个装饰物需要花费Ci元钱。奶牛对这个圣诞树上每个结点都有特殊的装饰需求，对于第i个结点，奶牛要求以它为根的子树上必须至少有Di&nbsp;个装饰物。请问约翰在哪些结点上挂载装饰物，才能满足奶牛的要求，并且使得装饰费用最少？</p> 

 
 # 输入格式 
<p>第一行：单个整数N，1&nbsp;&le;&nbsp;N&nbsp;&le;&nbsp;10^5<br />
第二行到N&nbsp;行：第i+1&nbsp;行有三个整数：Pi，Di&nbsp;和Ci，1&nbsp;&le;&nbsp;Pi&nbsp;&le;&nbsp;N,&nbsp;0&nbsp;&le;&nbsp;Di&nbsp;&le;&nbsp;10^6,&nbsp;1&nbsp;&le;&nbsp;Ci&nbsp;&le;&nbsp;100</p> 

 
 # 输出格式 
<p>单个整数，表示完成所有装饰要求的最少费用</p>

<hr />
<p>样例输入<br />
5<br />
-1&nbsp;9&nbsp;3<br />
1&nbsp;2&nbsp;2<br />
5&nbsp;3&nbsp;2<br />
5&nbsp;1&nbsp;4<br />
2&nbsp;3&nbsp;3</p>

<p>样例输出<br />
20</p> 

 
 # 提示 
<p>解释<br />
在第四个结点上放一个，花4&nbsp;元；在第三个结点上放五个，花10&nbsp;元；在第二个结点上放三<br />
个，花6元；</p> 
