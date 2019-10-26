
# Content

众所周知，天行廖大师，情圣谭大爷，少女心澜少在喵哈哈村享有很大的名气，弱冠之年，恰逢年少轻狂时，众人称三人为$“哈哈村三公子”$

正所谓公子如玉，三位少爷风流倜傥，玉树临风，好写诗作画吹比

而咸鱼廖大师，廖少，无疑是三位公子中最具有特色的一位

据传闻，廖少来自于神秘的廖式集团，而廖少，则是廖式集团的下一任总裁

最近，廖少受到了情圣谭少，少女心澜少的邀请准备去吃喝一番

当然，廖少作为霸道总裁，赴约怎可没有佳人陪伴

而廖少的后宫有$2^{N}$位佳人，已知每个佳人的美丽值是$A\_{i}$

廖少准备带两位妹纸去赴约！，我们定义一个$ans\_{x}$表示人赢值，计算方式如下

$ans[x] = \sum\_{[i|j=x]} {A\_{i}*A\_{j}} $

*  Girl's index from $0$ to $ 2^N - 1 $

现在廖少非常迫切的想要知道$ans$数组，这个难题只能交给你了！

# Standard Input

第一行一个整数$N$，表示廖少有$2^N$位佳人

接下来一行$2^N$个数，分别表示$A\_{i}$，即第$i$个佳人的美丽值

数据保证:

*  $0 \leq N \leq 20 $

*  $0 \leq A\_{i} \leq 2^N-1 $

# Standard Output

输出$2^N$行，分别表示$ans[i]$，因为答案可能较大，你只需要输出$ans[i]$ % $772002$

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>2
0 0 0 0
</td><td>0
0
0
0
</td></tr></table>


# Constraints



# Note

喵哈哈村的编剧好苦命啊

什么？一个妹纸能同时是i , j ，不要在意这些细节

![title](/source/lutece/ba-dao-zong-cai-liao-shao-i/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTM4My8yMDE2MDUxMzAwMTk0OTIxNDUxLmdpZg==.gif)

# Source


