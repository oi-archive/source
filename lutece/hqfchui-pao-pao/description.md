
# Content

Tql! 经历了一天的训练之后，`hqf`准备放松一下。与`FarmerKb`这个蒟蒻的放松方式不一样，`hqf`在草坪上吹起了泡泡。经历了`hqf`的一顿操作之后，天空中出现了n个泡泡，每个泡泡都有个编号。`hqf`给出了m个关系，每个关系以u v w的形式给出，表示编号为u的泡泡可以和编号为v的泡泡连在一起，且花费的代价为w。看到`FarmerKb`坐在草坪上傻傻的望着天空，`hqf`问了`FarmerKb`一个问题：如何以最小的代价把这n个泡泡中的一些泡泡连在一起，使得天空中出现k个泡泡联通块？可是`FarmerKb`沉浸在了泡泡的海洋无法自拔，不想回答这个问题，他希望你来替他回答`hqf`的提问。

# Standard Input

第一行三个整数n，m和k。表示泡泡的个数，`hqf`给出的关系数以及最终要形成的泡泡联通块数，1<=k<n<=1000，1<=m<=5e5  
接下来的m行，每行三个数u, v, w，表示你可以把泡泡u和泡泡v连在一起，需要花费的代价为w，1<=u,v<=n，0<w<=1e6

# Standard Output

输出一个整数，表示把这n个泡泡中的一些泡泡连在一起使得天空中出现k个泡泡联通块的最小代价

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
<tr><td>4 4 2  
1 2 1  
2 3 4  
3 4 2  
1 4 5  </td><td>3</td></tr></table>


# Constraints



# Note

1：对于样例，可以选择把泡泡1和泡泡2连在一起，花费代价为1，泡泡3和泡泡4连在一起，花费代价为2，从而形成2个泡泡联通块，且花费最小代价1+2=3    
2：数据保证有解

# Source


