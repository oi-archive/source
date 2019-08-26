
# Description

<div class="content">  小C 有一个能量魔方，这个魔方可神奇了，只要按照特定方式，放入不同的
能量水晶，就可以产生巨大的能量。 
  能量魔方是一个 N*N*N 的立方体，一共用 N3
个空格可以填充能量水晶。 
能量水晶有两种： 
·一种是正能量水晶(Positive) 
·一种是负能量水晶(Negative) 
  当这个魔方被填满后，就会依据填充的能量水晶间的关系产生巨大能量。对
于相邻两(相邻就是拥有同一个面)的两个格子，如果这两个格子填充的是一正一
负两种水晶，就会产生一单位的能量。而整个魔方的总能量，就是这些产生的能
量的总和。 
  现在，小 C 已经在魔方中填充了一些水晶，还有一些位置空着。他想知道，
如果剩下的空格可以随意填充，那么在最优情况下，这个魔方可以产生多少能量。  
 </div>

# Input

<div class="content">第一行包含一个数N，表示魔方的大小。 
接下来 N2
行，每行N个字符，每个字符有三种可能： 
P：表示此方格已经填充了正能量水晶； 
N：表示此方格已经填充了负能量水晶； 
?：表示此方格待填充。 
上述 N*N
行，第(i-1)*N+1~i*N 行描述了立方体第 i 层从前到后，从左到右的
状态。且每 N 行间，都有一空行分隔。 </div>

# Output

<div class="content">仅包含一行一个数，表示魔方最多能产生的能量</div>

# Sample Input

<div class="content"><span class="sampledata">2 <br/>
P? <br/>
?? <br/>
 <br/>
?? <br/>
N? </span></div>

# Sample Output

<div class="content"><span class="sampledata">9</span></div>

# Hint

<div class="content"><p>如下状态时，可产生最多的能量。 <br/>
PN <br/>
NP <br/>
 <br/>
NP <br/>
NN <br/>
 <br/>
【数据规模】 <br/>
  10% 的数据N≤3； <br/>
  30% 的数据N≤4； <br/>
  80% 的数据N≤10； <br/>
  100% 的数据N≤40。 <br/>
   </p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

