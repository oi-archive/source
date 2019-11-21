
# Content

#### $Sonochi$，明年再一起看烟花。——$Washio\,Sumi$    

![](http://yushadearu.jp/washiosumi/common/img/story_08_pic_01.png "")

为了实现和$Sonochi$的约定，$Washi$必须要打败眼前强大的怪物。     
怪物分布在二维平面上，    
某个怪物的$rank$被定义为$x$坐标不大于其$x$坐标，且$y$坐标不大于其$y$坐标的怪物的数量。（不含其自身）    
$Washi$要你输出$n$行，每行一个整数，分别代表$rank$为$0$~$n-1$的怪物数量。

# Standard Input

输入第一行为一个正整数$n$，    
接下来$n$行，第$i$行两个整数$x_i$、$y_i$，表示一个怪物的坐标。    
保证输入的坐标两两不同。

# Standard Output

包含$n$行，每行一个整数，第$i$行的数代表$rank$为$i-1$的怪物数量。

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
<tr><td>5
1 1
5 1
7 1
3 3
5 5</td><td>1
2
1
1
0</td></tr></table>


# Constraints



# Note

$1{\leq}n{\leq}100000$    
$1{\leq}x\_i{\leq}100000$    
$1{\leq}y\_i{\leq}100000$

# Source


