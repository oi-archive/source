
# Description

<div class="content">在一次军事行动中有一批空降兵要降落在沙漠中拆除炸弹. 空降兵按照预定的顺序跳伞并降落到指定的位置.一旦降落他们便呆在原地不动了. 
每个空降兵都有一个生存半径. 如果炸弹与他的距离小于或等于这个生存半径的话,空降兵便会引爆炸弹导致死亡. 指挥官想尽量少的派出升降兵.但是在这个目标的前提是至少要能有1名伞兵活着回来.(无论炸弹在何处的情况下都如此). 
我们可以假定沙漠抽象成一个二维平面,每个伞兵降落的地点都是这个平面上的一个整点.我们会给定伞兵降落的顺序,每个伞兵都不会不跳,即如果第i个伞兵在沙漠中着陆,那么他前面的所有伞兵肯定都已着陆.求指挥官至少要派出多少空降兵. 
</div>

# Input

<div class="content">第一行一个数n ( 2 &lt;= n &lt;= 2 000) – 空降兵的个数. 接下来n 行每行描述一个空降兵. 每个空降兵用三个整数: x, y 和 r ( -1000 &lt;= x, y &lt;= 1000, 1 &lt;= r &lt;= 5000). 表示空降兵在点(x, y) 着陆, 他的生存半径为 r. 
</div>

# Output

<div class="content">输出一行表示最少需要派出多少空降兵.如果所有的空降兵都有可能牺牲的话输出NIE (NO in Polish). 

</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 2 4<br/>
7 2 3<br/>
4 3 1<br/>
5 7 1<br/>
8 7 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

