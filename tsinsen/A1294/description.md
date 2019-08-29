<div id="pcont1" style="margin-top:20px; display:block;">
<div class="pdcont">　　Time Limit: 60 seconds</div>
# 问题描述

<div class="pdcont">　　Nowadays, Japanese cartoons are popular among teenagers and a BBS called “Sumisora” has been built for anime discussion. Now, the Moe War, a famous activity in Sumisora, is coming.<br/>
　　You will join the Moe War with your team consisting of four cartoons girls, numbered from 1 to 4. Your goal is to get as many KIDs (the currency of Sumisora) as possible in the War. The rule of the Moe War is shown below.<br/>
　　Yours excluded, there are <i>N</i> teams in the Moe War, numbered from 1 to <i>N</i>. Each team consists of four girls. Your team will compete with every other team, each for once. So there are <i>N</i> matches in total.<br/>
　　A match consists of three rounds. Each round, a girl in your team will compete with a girl in your opponent’s team. No one can compete in more than one round in a match. Before the match, you can decide which three girls will be involved and their order in the three rounds. Your enemy will randomly pick three girls from the four and decide their orders to compete with uniform probability distribution among all possible candidates.<br/>
　　For the girl number <i>i</i> in your team, there is a variable <i>c<sub>i</sub></i> representing the maximum number of rounds she had ever won consecutively. Note that the matches that the girl numbered <i>i</i> did not participate in should not be taken into consideration when calculating the value of <i>c<sub>i</sub></i>. For example, the girl numbered 1 competed in the first, the second and the fourth matches, but she did not participate in the third match, then the value of <i>c</i><sub>1</sub> should be three if she won all three matches. But if she took part in the third match and lost, then the value of <i>c</i><sub>1</sub> should be two.<br/>
　　The War ends after all <i>N</i> matches are finished. The number of KIDs you will get can be divided into two categories:<br/>
　　The number of rounds you win. Obviously, the number of KIDs you get this way will by no means exceed the number of rounds you have competed in, which is 3<i>N</i>.<br/>
　　The maximum value of <i>c<sub>k</sub></i> among all the girls in your team. Note that an integer <i>M</i> is given as a threshold value, which means that If the maximum value of <i>c<sub>k</sub></i> is larger than <i>M</i>, it will be counted as <i>M</i>.<br/>
　　Every cartoon girl has a “Moe Value”. The girl with a higher “Moe Value” can always defeat her opponent in a round. If the two girls with the same “Moe Value” compete, each will have a 50% probability to win. The “Moe Values’ of all girls in all teams have been found out.<br/>
　　There is something extra you can do — bribery. To influence the leader of the <i>i</i>-th team, you have to offer a bribe of <i>A<sub>i</sub></i> KIDs. If so, you can then decide which three girls in the <i>i</i>-th team will be involved and their order to compete in the match between your team and the <i>i</i>-th team.<br/>
　　Please find out the expected number of KIDs you will get in the Moe War, with the optimal strategy.</div>
# 输入格式

<div class="pdcont">　　The input contains multiple test cases.<br/>
　　The first line of the input is an integer <i>T</i>, the number of test cases.<br/>
　　For each case, the first line of the input is an integer <i>N</i>, which is the number of teams, yours excluded.<br/>
　　Each of the following <i>N</i> lines contains five integers characterizing a team. The first four integers are the “Moe Values” of the girls in the team and the last integer is the KIDs you have to pay to offer a bribe.<br/>
　　The next line contains four integers, which are the “Moe Values” of the girls in your team.<br/>
　　The following line contains 3<i>N</i> integers. The <i>i</i>-th integers <i>P<sub>i</sub></i> is the number of KIDs you will get if you win <i>i</i> rounds at last.<br/>
　　The next-to-last line contains an integer <i>M</i>, the threshold value.<br/>
　　The last line contains <i>M</i> integers. The <i>i</i>-th integer <i>Q<sub>i</sub></i> is the number of KIDs you will get if the maximum value of <i>c<sub>k</sub></i>, among all the girls in your team, is <i>i</i>.<br/>
　　There are no empty lines between two consecutive cases.</div>
# 输出格式

<div class="pdcont">　　For each test case, the output should contain exactly one line with one real number rounded to three decimal places, the expected number of KIDs you can get, with the best strategy.</div>
# 样例输入

<div class="pddata">1<br/>
2<br/>
10 20 30 40 10<br/>
10 20 30 40 20<br/>
15 25 35 45<br/>
20 40 60 80 100 120<br/>
2<br/>
100 200</div>
# 样例输出

<div class="pddata">295.000</div>
# Constraints

<div class="pdcont">　　The number of test cases will not exceed 50, or 1 ≤ <i>T</i> ≤ 50.<br/>
　　For all test cases, 1 ≤ <i>N</i> ≤ 30, 0 ≤ <i>M</i> ≤ 5, and it is guaranteed that both <i>P<sub>i</sub></i> and <i>Q<sub>i</sub></i> are increasing sequences.</div>

</div>