

# 问题描述

<br/>
    小小在背单词，她发现当背诵了单词 beauty 以后 ，再接着背诵单词 beautiful 就会觉得容易许多。由于有很多单词要背，她希望找到一种好的背诵顺序。单词 A 和它的前驱 B 的最大公共前缀的长度称为背诵单词 A 的便利值 ( 例如： B= &#39; beauty &#39; ,A= &#39; beautiful &#39; , 则 A 的便利值是 len({A,B})=len( &#39; beaut &#39; )=5), 我们认为一个背诵单词 A 的花费是它的长度 ( 例如 : &#39; beautiful &#39;的长度 len( ‘ beautiful &#39; )=9) 与它的便利值之差（对于上述例子背诵 A 的花费为 9-5=4 ）。请你求一个背诵顺序，使得背诵这些单词的花费总和最小。假设一开始你什么单词都不记得。
</p>

# 输入格式



# 输出格式



# 输入输出样例

输入： <br/>
letter.in<br/>
5<br/>
beauty<br/>
beautiful<br/>
flower<br/>
man<br/>
dog
</p>
<p>
	输出：<br/>
letter.out<br/>
beautiful<br/>
beauty<br/>
dog<br/>
flower<br/>
man
</p>
