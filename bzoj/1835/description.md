
# Description

<div class="content"><p>有N个村庄坐落在一条直线上，第i(i&gt;1)个村庄距离第1个村庄的距离为Di。需要在这些村庄中建立不超过K个通讯基站，在第i个村庄建立基站的费用为Ci。如果在距离第i个村庄不超过Si的范围内建立了一个通讯基站，那么就成它被覆盖了。如果第i个村庄没有被覆盖，则需要向他们补偿，费用为Wi。现在的问题是，选择基站的位置，使得总费用最小。 输入数据 (base.in) 	输入文件的第一行包含两个整数N,K，含义如上所述。 	第二行包含N-1个整数，分别表示D2,D3,…,DN ，这N-1个数是递增的。 	第三行包含N个整数，表示C1,C2,…CN。 	第四行包含N个整数，表示S1,S2,…,SN。 	第五行包含N个整数，表示W1,W2,…,WN。</p></div>

# Input

<div class="content"><p>输出文件中仅包含一个整数，表示最小的总费用。</p></div>

# Output

<div class="content"><p>3 2 1 2 2 3 2 1 1 0 10 20 30</p></div>

# Sample Input

<div class="content"><span class="sampledata">	4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">	40%的数据中，N&lt;=500；<br/>
	100%的数据中，K&lt;=N，K&lt;=100，N&lt;=20,000，Di&lt;=1000000000，Ci&lt;=10000，Si&lt;=1000000000，Wi&lt;=10000。<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 2018.7.7重设时限为20s,未重测!</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

