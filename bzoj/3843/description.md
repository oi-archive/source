
# Description

<div class="content"><div>ZCC owns an army with n soldiers. Soldiers are numbered from 1 to n. Soldier 1 is the commander in chief. Each soldier has a direct superior (which is called father in ACM) except soldier 1. x is a direct inferior (which is called son in ACM) of y if and only if y is the direct superior of x. Soldier use an ordered list called direct inferiors list to manage his direct inferiors (The indexes begin with 1). If soldier A and soldier B are in the same direct inferiors list, and A is in front of B, then we say A’s level is higher than B. We assume that soldier 1 belongs to a direct inferior list that only contains soldier 1 for convenience.</div>
<div>Messages can be transmitted among the soldiers. A soldier can directly send messages to his direct superior, his direct inferior, and those who are in the same direct inferior list with him. Messages can also be sent indirectly. That means if x wants to send a message to y, he first send it directly to a third soldier z, then z send this message directly to y. In this case, we say z is involved in this transmission as a middleman. Message transmission that involves more than one middleman is also allowed.</div>
<div>Orders can be transmitted among the soldiers too. A soldier can directly give orders to his direct inferior and those who are in the same direct inferior list with him but have lower level. Orders can also be given indirectly. That means if x wants to give an order to y, he first give it to a third soldier z, then z give this order to y. In this case, we say z is involved in this transmission as a middleman. Order transmission that involves more than one middleman is also allowed.</div>
<div>Unfortunately, sometimes some soldiers will change their direct superior. More specifically, event like “the p-th soldier to (p+c-1)-th soldier in soldier x’s direct inferior list change their direct superior to y and be inserted after the q-th soldier in y’s direct inferior list (if q=0, that means these soldiers are inserted in front of the first soldier in y’s direct inferior list)” will sometimes happen.</div>
<div>To examine the efficiency of the transmission of the messages and orders, ZCC will ask two types of question: </div>
<div>1) If soldier x want to send messages to soldier y, at least how many soldiers will be involved in this transmission as a middleman.</div>
<div>2) How many soldiers can give orders to soldier x.</div>
<div>Now, m events, including direct superior change events and ZCC’s questions, happen one by one. Can you answer all ZCC’s questions?</div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>The first line contains two integers n and m, indicating the number of soldiers and the number of events.</div>
<div>Then n lines follow, describing the initial direct inferior list of each soldier. The i-th line contains several integers. The first integer is k, indicating the number of soldier i’s direct inferior. Then k integers follow, indicating the direct inferior list of soldier i.</div>
<div>After that m lines follow, describing the m events. Each line begins with an integer t, indicating the type of this event.</div>
<div>If t = 1, then 5 integers x, p, c, y and q follow, indicating a direct superior change event;</div>
<div>If t = 2, then 2 integers x and y follow, indicating ZCC’s question 1;</div>
<div>If t = 3, then an integer x follows, indicating ZCC’s question 2.</div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>For each question, output one line with one integer indicating your answer.</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 7<br/>
2 2 3<br/>
3 4 5 6<br/>
3 7 8 9<br/>
0<br/>
0<br/>
0<br/>
0<br/>
0<br/>
0<br/>
3 1<br/>
3 9<br/>
1 2 2 2 3 2<br/>
3 9<br/>
2 5 9<br/>
2 4 8<br/>
3 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
5<br/>
7<br/>
0<br/>
2<br/>
2</span></div>

# Hint

<div class="content"><p></p><div> n&lt;=100000, m&lt;=100000</div><br/>
<div> You can assume that the events are all legal, and the relationship among the soldiers forms a tree all the time.</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 镇海中学">By 镇海中学</a></p></div>

