
# Content

Fish是一条生活在海里的鱼，有一天他很无聊，于是他去捡了人类扔进海里的垃圾，打算用这些来玩些什么。
	
他从捡回来的垃圾堆里找到了不少火柴棍，便把这些火柴棍拼成了一个长度为$n$的十进制数，每个数字的拼法如下图所示。

![.*](/source/lutece/huo-chai-gun-shu-zi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3LzIwMTQwMjAxMTQ0NzA1Mzk3Ni5wbmc=.png)

拼完之后他好累，感觉再也不会拼了。

他对拼出来的数大小不满意，希望通过移动一些火柴棍的位置来把这个数变得尽量大。
由于太累，他只能最多移动$k$根火柴棍。而且由于数字的最低位放在墙边，他不能在该数的低位后面添加数字，但他可以在该数的前面添加数字。
	
你能帮他算出他移动火柴棍之后的数最大能是多大吗？

**注意：火柴棍对于Fish来说是很贵重的物品，所以不允许折断或丢弃火柴棍。**

**注意：火柴头的方向不影响数字的辨识，例如下面几种情况都是数字$1$。**

![.*](/source/lutece/huo-chai-gun-shu-zi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3LzIwMTQwMjAxMTQ0NzQzMTAwNy5wbmc=.png)

**注意：每个数字占据的宽度和摆放方式是固定的，故以下情况均不合法。**

![.*](/source/lutece/huo-chai-gun-shu-zi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3LzIwMTQwMjAxMTQ0ODEyMzU3OC5wbmc=.png)

# Standard Input

输入仅含一行，分别是长度为$n$的十进制数$x$和最多移动火柴棍的数量$k$。$x$没有前导零。

对于$30\%$的数据，$1\leq n\leq 10$，$0\leq k\leq 10$。

对于$100\%$的数据，$1\leq n\leq 500$，$0\leq k\leq 3500$。

# Standard Output

输出仅一行，表示移动火柴棍之后的最大数。

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
<tr><td>3 2</td><td>17</td></tr><tr><td>3 3</td><td>71</td></tr></table>


# Constraints



# Note

![.*](/source/lutece/huo-chai-gun-shu-zi/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTI3LzIwMTQwMjAxMTQ0OTE5NTI2OS5wbmc=.png)

# Source


