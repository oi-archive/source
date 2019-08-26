
# Description

<div class="content">打孔机是一种在票上打孔的装置， 假设票是一个M*N的矩阵，矩阵行列间距相等，你可以选择在M*N个位置上打穿或不打穿，这样就有 
2^(M*N)-1（至少要打一个孔）不同的方案数。 

但是我们的问题并不是这么简单的，如果两种方案经过如下的若干操作后，打穿的孔刚好重合，那么认为这两个方案是相同的： 
•翻转 
•旋转0，90，180，270 
•平行移动 
显然如果两种方案上孔的数目不同，那么必然是不同的方案。现在你的问题就是给定M，N，算出所有不同的方案数。 

</div>

# Input

<div class="content">文件包含两个数M(≤6), N (≤10) ,用空格分开。 
</div>

# Output

<div class="content">只有一行，为所求的方案数。 
</div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">85<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

