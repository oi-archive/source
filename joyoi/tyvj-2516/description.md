# 

 
 # 题目描述 
<p>
Farmer John's N (1 <= N <= 50,000) cows are standing in a very<br>straight row and mooing. Each cow has a unique height h in the range<br>1..2,000,000,000 nanometers (FJ really is a stickler for precision).<br>Each cow moos at some volume v in the range 1..10,000. This "moo"<br>travels across the row of cows in both directions (except for the<br>end cows, obviously). Curiously, it is heard only by the closest<br>cow in each direction whose height is strictly larger than that of<br>the mooing cow (so each moo will be heard by 0, 1 or 2 other cows,<br>depending on not whether or taller cows exist to the mooing cow's<br>right or left).<br><br>The total moo volume heard by given cow is the sum of all the moo<br>volumes v for all cows whose mooing reaches the cow. Since some<br>(presumably taller) cows might be subjected to a very large moo<br>volume, FJ wants to buy earmuffs for the cow whose hearing is most<br>threatened. Please compute the loudest moo volume heard by any cow.<br><br><br>Farmer John的N(1<=N<=50,000)头奶牛整齐地站成一列“嚎叫”。每头奶牛有一个确定的高度h(1<=h<=2000000000)，叫的音量为v (1<=v<=10000)。每头奶牛的叫声向两端传播，但在每个方向都只会被身高严格大于它的最近的一头奶牛听到，所以每个叫声都只会 被0，1，2头奶牛听到（这取决于它的两边有没有比它高的奶牛）。<br><br>一头奶牛听到的总音量为它听到的所有音量之和。自从一些奶牛遭受巨大的音量之后，Farmer John打算买一个耳罩给被残害得最厉 害的奶牛，请你帮他计算最大的总音量。<br></p> 

 
 # 输入格式 
<p>
* Line 1: A single integer, N.<br><br>* Lines 2..N+1: Line i+1 contains two space-separated integers, h and<br>        v, for the cow standing at location i.<br><br></p> 

 
 # 输出格式 
<p>
* Line 1: The loudest moo volume heard by any single cow.<br></p> 
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>3
4 2
3 5
6 10

INPUT DETAILS:

Three cows: the first one has height 4 and moos with volume 2, etc.
</td><td>7

OUTPUT DETAILS:

The third cow hears both the first and second cows moo 2+5=7.  Though the
third cow moos with volume 10, no one hears her.</td></tr></table>
