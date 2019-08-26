
# Description

<div class="content"><p style="text-align: left"><span id="1319334294901S" style="display: none"> </span><span style="font-size: medium"><font face="Times New Roman">This problem is based on the game of Black Vienna. In this version there are three players and 18 cards labeled A-R. Three of the cards are set aside (hidden) and form the &#34;Black Vienna&#34; gang. The remaining cards are shuffled and dealt to the players so that each player has 5 cards. Players never reveal their cards to each other. There is a separate deck of &#34;interrogation cards&#34; which contain three distinct letters in ascending order, like ACG or BHR. Turns rotate through players 1, 2, and 3. On each player&#39;s turn, that player selects an interrogation card, puts it face up in front of another player, and that other player must indicate the total number of these cards being held, without saying which ones. All players see the result of the &#34;interrogation&#34;. The play continues until a player deduces the three cards in the &#34;gang&#34;. <br/>
For example, suppose the cards are distributed as follows, and the game then proceeds: <br/>
<br/>
<br/>
Player 1: DGJLP; Player 2: EFOQR; Player 3: ACHMN; Gang: BIK <br/>
<br/>
Turn 1: Player 1 interrogates player 2 with BJK; answer 0 <br/>
Turn 2: Player 2 interrogates player 3 with ABK; answer 1 <br/>
Turn 3: Player 3 interrogates player 2 with DEF; answer 2 <br/>
Turn 4: Player 1 interrogates player 2 with EIL; answer 1 <br/>
Turn 5: Player 2 interrogates player 3 with FIP; answer 0 <br/>
Turn 6: Player 3 interrogates player 1 with GMO; answer 1 <br/>
Turn 7: Player 1 interrogates player 2 with OQR; answer 3 <br/>
Turn 8: Player 2 interrogates player 3 with ADQ; answer 1 <br/>
Turn 9: Player 3 interrogates player 1 with EGJ; answer 2 <br/>
<br/>
<br/>
<br/>
In fact, the game does not need to get to turn 9. With enough thought, player 1 can deduce after turn 8 that the gang is BIK. It is your job to analyse records of games and deduce the earliest time that the gang could be determined for sure. <br/>
<br/>
<br/>
Black Vienna游戏是当前很流行的桌面游戏，规则是这样的：有18张牌，分别标着A-R，游戏有三个人。游戏开始的时候每个人拿5张牌，剩下三张牌隐藏起来，大家都只能看见自己手中的牌。之后，从第一个人到第三个人轮流拿一张“疑问牌”去问另外的一个人，“疑问牌”上有三个字母，那个人必须诚实地回答自己手中有多少疑问牌中的字母。哪个人能够最先推断出隐藏起来的牌是什么，那个人就取得胜利。现在你的任务是，给出三个人手上的牌和询问情况，你需要计算出最早在哪一次询问之后，有人能够推断出隐藏的牌。 <br/>
<br/>
<br/>
</font></span></p>
<p style="text-align: left"></p></div>

# Input

<div class="content"><p style="text-align: left"> <span style="font-size: medium"><font face="Times New Roman">The input will consist of one to twelve data sets, followed by a line containing only 0. <br/>
The first line of a dataset contains the number, t, of turns reported, 2 ≤ t ≤ 15. <br/>
The next line contains four blank separated strings for the hands of players 1, 2, and 3, followed by the cards for the gang. <br/>
The remaining t lines of the data set contain the data for each turn in order. Each line contains three blank separated tokens: the number of the player interrogated, the string of interrogation letters, and the answer provided. <br/>
All letter strings will contain only capital letters from A to R, in strictly increasing alphabetical order. The same interrogation string may appear in more than one turn of a game. <br/>
</font></span></p>
<p style="text-align: left"></p></div>

# Output

<div class="content"><p style="text-align: left"><span style="font-size: medium"><font face="Times New Roman">There is one line of output for each data set. The line contains the single character &#34;?&#34; if no player can be sure of the gang after all the turns listed. If a player can determine the gang, the line contains the earliest turn after which one or more players can be sure of the answer. <br/>
</font></span></p>
<p style="text-align: left"></p></div>

# Sample Input

<div class="content"><span class="sampledata">9<br/>
DGJLP EFOQR ACHMN BIK<br/>
2 BJK 0<br/>
3 ABK 1<br/>
2 DEF 2<br/>
2 EIL 1<br/>
3 FIP 0<br/>
1 GMO 1<br/>
2 OQR 3<br/>
3 ADQ 1<br/>
1 EGJ 2<br/>
3<br/>
ABCDE FGHIJ KLMNO PQR<br/>
3 BKQ 1<br/>
1 ADE 3<br/>
2 CHJ 2<br/>
0<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">8<br/>
?<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于样例一的解释</p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><span lang="EN-US"><font face="Calibri"><span style="mso-spacerun: yes">                 </span><b style="mso-bidi-font-weight: normal"><span style="mso-spacerun: yes">  </span></b></font></span><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">从第一个人角度看：</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">1</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>2 BJK 0<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri"> </font></span></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJK<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><b style="mso-bidi-font-weight: normal"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP<o:p></o:p></font></span></font></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">2</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>3 ABK 1<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri"> </font></span></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJK<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP<span style="mso-spacerun: yes">                       </span>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">3</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>2 DEF 2<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri"> </font></span></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJK<span style="mso-spacerun: yes">       </span><span style="mso-spacerun: yes">  </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EF<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLPEF<span style="mso-spacerun: yes">                     </span>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">4</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>2 EIL 1<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri"> </font></span></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJKIL<span style="mso-spacerun: yes">       </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EF<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP EF<span style="mso-spacerun: yes">                     </span>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">5</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>3 FIP 0<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><span style="mso-spacerun: yes"><font face="Calibri"> </font></span></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJKIL<span style="mso-spacerun: yes">       </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EF<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP EFIP<span style="mso-spacerun: yes">                   </span>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">6</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组</span><span lang="EN-US"><font face="Calibri">:<span style="mso-spacerun: yes">  </span>1 GMO 1 </font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">（对自己没有利用价值）</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">7</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组：</span><span lang="EN-US"><font face="Calibri">2 OQR 3<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJKIL<span style="mso-spacerun: yes">       </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EFOQR<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP EFIPOQR<span style="mso-spacerun: yes">                </span>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt"><font size="3"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><font face="Calibri">8</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">组：</span><span lang="EN-US"><font face="Calibri">3 ADQ 1<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJKIL<span style="mso-spacerun: yes">       </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EFOQR<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP EFIPOQR<span style="mso-spacerun: yes">               </span>[<i style="mso-bidi-font-style: normal"> </i>ABK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><font face="Calibri"> ADK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">中有一个</span><span lang="EN-US"><font face="Calibri">]<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><b style="mso-bidi-font-weight: normal"><font size="3"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">由括号部分可知：</span><span lang="EN-US"><o:p></o:p></span></font></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第二人：无</span><span lang="EN-US"><font face="Calibri">DGJLPBJKIL<span style="mso-spacerun: yes">        </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">EFOQR<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">第三人：无</span><span lang="EN-US"><font face="Calibri">DGJLP EFIPOQRBK<span style="mso-spacerun: yes">  </span></font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">有</span><span lang="EN-US"><font face="Calibri">A<o:p></o:p></font></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">此时，第一人知道自己和</span><span lang="EN-US"><font face="Calibri">2,3</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">都无</span><span lang="EN-US"><font face="Calibri">BIK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">，所以隐藏牌为</span><span lang="EN-US"><font face="Calibri">BIK</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">。</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><b style="mso-bidi-font-weight: normal"><span lang="EN-US"><o:p><font face="Calibri" size="3"> </font></o:p></span></b></p><br/>
<p class="MsoNormal" style="margin: 0cm 0cm 0pt; text-indent: 5.15pt; mso-char-indent-count: .49"><font size="3"><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">（</span><span lang="EN-US"><font face="Calibri">2,3</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">人视角同上，前</span><span lang="EN-US"><font face="Calibri">8</font></span></b><b style="mso-bidi-font-weight: normal"><span style="font-family: 宋体; mso-ascii-font-family: Calibri; mso-hansi-font-family: Calibri">步无法得出结论）</span><span lang="EN-US"><o:p></o:p></span></b></font></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

