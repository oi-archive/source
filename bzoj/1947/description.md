
# Description

<div class="content"><p>If you are an average football fan, you probably know that obtaining tickets for this year’s World Cup in Germany was an impossible task. Greedy organizers and football federations grabbed the majority or available tickets and divided them among sponsors, friends and family members. As a result, jet setters have flooded the venues, while die-hard fans sit at home enjoying the games between advertisements featuring crappy beer and sugar-free chewing gum. A couple of tickets are left for the final game and a huge queue has formed in front of the ticker office. As fans were arriving, they were labeled with successive integers. The first person in queue was labeled with number one, the second with number two, etc. Since the fans arrived the night before, they had to wait for a long time before the ticket counter was open and, naturally, some of them had to use the restroom. Each time a person needs to use the restroom, he/she steps out of the queue and, and, after completing the task, steps back into the queue, though not necessarily at the same position as before. Since there is only one restroom available no person leaves the queue before the previous person has returned (hence, at any moment there is at most one person missing from the queue). During the course of the night, a total of N restroom visits have occurred. Each visit is described by two positive integers A and B, denoting that the person labeled A stepped out of the queue and the stepped back into the queue immediately in front of the person labeled B. Now that all the visits have completed, the officials have to answer a series of questions. Each question is either of the form ‘P X’, asking for the position lf the person labeled X, or of the form ‘L X’, asking for the label of the person at position X. The first person in queue is considered to be at position one, the second at position two, etc. Write a program that, given the description of the visits and a number of questions, answers all of the questions. 一开始将一列人按编号从1开始顺序排列，然后进行N次操作，每次将编号为A的人拿出，放在编号为B的人前面，所有操作进行完后有Q个问题，询问编号为X的人的位置，或者询问在X号位置上的人的编号。</p></div>

# Input

<div class="content"><p>The first line of input contains an integer N(2 ≤ N ≤ 50 000)- the total number of restroom visits. Each of the following N lines contains two different integers A and B (1 ≤ A, B ≤ 109), describing one restroom visit. The nest line contains an integer Q (1 ≤ Q ≤ 50 000) – the total number of questions. Each of the following Q lines contains a single character (either the uppercase letter ‘P’ or the uppercase letter ‘L’) and an integer X (1≤ X ≤109) , describing one question.</p></div>

# Output

<div class="content"><p>The output should consist of a total of Q lines. The ith line or output should contain a single integer R – the answer to the ith question. If the corresponding question is of the form ‘P Xi’ then R should be the final position of the person labeled Xi. If the corresponding question is of the form ‘L Xi’ then R should be the label of the person at position Xi. Grading Partial credit is awarded for incorrect solutions that correctly answer all questions of one type. If all questions of the form ‘P X’ are answered correctly or if all questions of the form ‘L X’ are answered correctly, you will receive 50% of the corresponding test case. In order to receive partial credit, the output should be formatted according to the specifications. Therefore, even if you choose to answer only one type of questions, you should still produce output for all questions of the other type.</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
6 3<br/>
9 6<br/>
8<br/>
L 1<br/>
L 2<br/>
L 3<br/>
L 4<br/>
P 1<br/>
P 2<br/>
P 3<br/>
P 4<br/>
Output<br/>
1<br/>
2<br/>
9<br/>
6<br/>
1<br/>
2<br/>
5<br/>
6<br/>
<br/>
Input<br/>
5<br/>
7 2<br/>
2 7<br/>
9 7<br/>
10 1<br/>
10005 9995<br/>
9<br/>
L 1<br/>
P 2<br/>
L 2<br/>
P 7<br/>
L 7<br/>
P 9<br/>
P 10<br/>
P 99999<br/>
P 100000<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
3<br/>
1<br/>
5<br/>
4<br/>
4<br/>
1<br/>
99999 <br/>
100000</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

