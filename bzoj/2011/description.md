
# Description

<div class="content">Georg有个MP3 Player，没有任何操作T秒钟就会锁定，这时按下任意一个键就会变回没锁定的状态，但不会改变频道。只有在没锁定的状态下按键才有可能改变频道。
	MP3的频道为0~Vmax(2&lt;=Vmax&lt;=5000)，如果现在是X频道，若X&lt;&gt;Vmax,在无锁状态下按+，X就会加1。若X&lt;&gt;0,在无锁状态下按-，X就会减一。
	想在Georg忘记了MP3的T是多少。他想通过一段操作试验一下。然后他就写下他的操作顺序和最后停留的频道V2(0&lt;=V2&lt;=Vmax),然后就给你了，你要求的是T的最大值和T在这个值的情况下，第一个操作前的频道V1的最大可能数。若T为无限大时经过这段操作最后能停在V2，则输出infinity。

</div>

# Input

<div class="content">
	第1行：N，Vmax，V2   N表示Georg操作了N次(2&lt;=N&lt;=100000);
	以下N行，每行第一个为字符C(C为&#39;+&#39;或&#39;-&#39;)，第二个为数字Ti(0&lt;=Ti&lt;=10^9)，  表示Georg在Ti秒按下了C键。


	</div>

# Output

<div class="content">如题所述。</div>

# Sample Input

<div class="content"><span class="sampledata">6 4 3<br/>
- 0<br/>
+ 8<br/>
+ 9<br/>
+ 13<br/>
- 19<br/>
- 24<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5 4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

