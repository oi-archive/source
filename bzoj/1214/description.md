
# Description

<div class="content"><div>人类最终登陆了人马座行星，却惊讶地发现这颗行星是怪物的聚居地。这些怪物的防御系统是一个N行M列的矩阵格。</div>
<div>人类的星际舰队已经击破了一些单元格，但是现在轮到你来决定摧毁哪一个单元格了。</div>
<div>怪物的防御系统的防御力由只包含完整单元格的子矩阵的数量决定。</div>
<div>一个非空子矩阵由原矩阵通过以下方法获得：</div>
<div>一、移除一些以第一行开始的连续的行</div>
<div>二、移除一些以最后一行结束连续的行</div>
<div>三、移除一些以第一列开始的连续的列</div>
<div>四、移除一些以最后一列结束连续的列</div>
<div>选择一个单元格来摧毁，使得最小化防御系统的防御力</div>
<div>任务</div>
<div>计算摧毁一个单元格后，防御系统的防御力的最小值</div>
<div></div></div>

# Input

<div class="content"><div>第一行包括两个用空格隔开的两个数字N和M，表示矩阵的行数和列数。</div>
<div>接下来有N行，每行一串长度为M的01串。1表示该单元格是完整的，0表示该单元格已经被摧毁了。</div>
<div>1 &lt;= N , M &lt;= 750</div>
<div>对于所有的数据，矩阵里至少有1个完整的单元格</div>
<div></div></div>

# Output

<div class="content"><div>输出一个数字，即摧毁一个单元格以后，防御系统的防御力的最小值。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
011<br/>
110<br/>
100</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
样例解释<br/>
最初时，防御系统的防御力是9。摧毁第二行第二列的单元格以后，防御力降为6。<br/>
此时的矩阵为<br/>
011<br/>
100<br/>
100</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

