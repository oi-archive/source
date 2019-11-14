
# Content

![title](/source/lutece/dang-ran-shi-xuan-ze-yuan-liang-ta/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU5MC8yMDE3MDQxNzIyMjgxMDg3NjIuanBn.jpg)

在社交网络中，经常有小伙伴因为种种原因不得不选择原谅她。这时他就会获得心灵的成长并通过社交网络使更多人受到影响，我们称之为传播“快乐力量”。

我们假设一个社交网络是树的结构，我们定义群主是树的根。

传播“快乐力量”有两种方式：

1、树状传播：

![title](/source/lutece/dang-ran-shi-xuan-ze-yuan-liang-ta/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU5MC8yMDE3MDQxNzIyNDg1MDA0MDMuanBn.jpg)

由某个节点向其所有子孙节点传播，该节点及以该节点为根的子树上的所有节点都获得一定的“快乐力量”。

2、链式传播：

![title](/source/lutece/dang-ran-shi-xuan-ze-yuan-liang-ta/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTU5MC8yMDE3MDQxNzIyNDkwNDE2MzQuanBn.jpg)

在某两个节点之间传播， 两点及其路径上的所有节点都获得一定的“快乐力量”。

假设初始所有人的快乐力量为0，现在我们需要获得一些时刻社交网络中某人的“快乐力量”值。

# Standard Input

第一行三个正整数N、M、T（1<=N<=100000；1<=M<=1000000；1<=T<=N）表示社交网络中有几个人，传播快乐力量或询问的次数，群主的标号。 社交网络中所有人按1到N顺序标号

接下来N-1行，每行两个正整数Ui、Vi表示Ui、Vi间有边相连。

接下来M行，表示按顺序进行的M次操作，每行若干个整数

首先一个K：表示这次操作的类型

如果K=1，表示一次树状传播：接下来两个整数Ai(1<=Ai<=N)、Ci(1<=Ci<=20) 表示以Ai为子树的根进行操作，所有节点获得Ci的快乐力量。

如果K=2，表示一次链式传播：接下来三个正整数Ai、Bi(1<=Ai、Bi<=N)、Ci(1<=Ci<=20) 表示以Ai、Bi为端点进行链式操作，所有节点获得Ci的快乐力量。

如果K=3，表示一次询问：接下来一个正整数Ai(1<=Ai<=N)，表示询问节点Ai的快乐力量。

# Standard Output

对于每个询问，输出一行一个非负整数表示该节点当前的“快乐力量”值。

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
<tr><td>2 3 1
1 2
1 1 1
2 2 1 1
3 2

</td><td>2</td></tr></table>


# Constraints



# Note



# Source


