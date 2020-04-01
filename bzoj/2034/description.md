
# Description

<div class="content"><p>给出N件单位时间任务，对于第i件任务，如果要完成该任务，需要占用[Si, Ti]间的某个时刻，且完成后会有Vi的收益。求最大收益。 N≤5000，1 ≤ Si ≤ Ti ≤ 108，1 ≤ Vi ≤ 108。 澄清：一个时刻只能做一件任务，做一个任务也只需要一个时刻。</p></div>

# Input

<div class="content"><p>第一行一个整数N,表示可供选择的任务个数. 接下来的第二到第N+1行，每行三个数，其中第i+1行依次为Si,Ti,Vi</p></div>

# Output

<div class="content"><p>输出最大收益</p></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 1 2<br/>
2 2 2<br/>
1 2 3<br/>
1 3 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6</span></div>

# Hint

<div class="content"><p></p><p>共有四个任务，其中第一个任务只能在时刻1完成，第二个任务只能在时刻2做，第三个任务只能在时刻1或时刻2做，第四个任务可以在[1,3]内任一时刻完成，四个任务的价值分别为2、2、3和1。一种完成方案是：时刻1完成第一个任务，时刻2完成第三个任务，时刻3完成第四个任务，这样得到的总收益为2+3+1=6，为最大值。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=版权所有者： 冯齐纬">版权所有者： 冯齐纬</a></p></div>

