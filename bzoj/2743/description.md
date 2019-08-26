
# Description

<div class="content"><div>萧芸斓是Z国的公主，平时的一大爱好是采花。今天天气晴朗，阳光明媚，公主清晨便去了皇宫中新建的花园采花</div>
<div>。花园足够大，容纳了n朵花，花有c种颜色（用整数1-c表示），且花是排成一排的，以便于公主采花。公主每次</div>
<div>采花后会统计采到的花的颜色数，颜色数越多她会越高兴！同时，她有一癖好，她不允许最后自己采到的花中，某</div>
<div>一颜色的花只有一朵。为此，公主每采一朵花，要么此前已采到此颜色的花，要么有相当正确的直觉告诉她，她必</div>
<div>能再次采到此颜色的花。由于时间关系，公主只能走过花园连续的一段进行采花，便让女仆福涵洁安排行程。福涵</div>
<div>洁综合各种因素拟定了m个行程，然后一一向你询问公主能采到多少朵花（她知道你是编程高手，定能快速给出答</div>
<div>案！），最后会选择令公主最高兴的行程（为了拿到更多奖金！）。</div></div>

# Input

<div class="content"><div>第一行四个空格隔开的整数n、c以及m。</div>
<div>接下来一行n个空格隔开的整数，每个数在[1, c]间，第i个数表示第i朵花的颜色。</div>
<div>接下来m行每行两个空格隔开的整数l和r（l ≤ r），表示女仆安排的行程为公主经过第l到第r朵花进行采花。</div></div>

# Output

<div class="content"><div>共m行，每行一个整数，第i个数表示公主在女仆的第i个行程中能采到的花的颜色数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">5  3 5<br/>
1  2 2 3 1<br/>
1  5<br/>
1  2<br/>
2  2<br/>
2  3<br/>
3  5</span></div>

# Sample Output

<div class="content"><span class="sampledata">2 <br/>
0 <br/>
0 <br/>
1 <br/>
0 <br/>
【样例说明】<br/>
询问[1, 5]：公主采颜色为1和2的花，由于颜色3的花只有一朵，公主不采；询问[1, 2]：颜色1和颜色2的花均只有一朵，公主不采；<br/>
询问[2, 2]：颜色2的花只有一朵，公主不采；<br/>
询问[2, 3]：由于颜色2的花有两朵，公主采颜色2的花；<br/>
询问[3, 5]：颜色1、2、3的花各一朵，公主不采。<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【数据范围】<br/><br/>
对于100%的数据，1 ≤ n ≤    10^6，c ≤ n，m ≤10^6。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

