
# Description

<div class="content"><p>　　2008北京奥运会即将开幕，举国上下都在为这一盛事做好准备。为了高效率、成功地举办奥运会，对物流系统<br/>
进行规划是必不可少的。物流系统由若干物流基站组成，以 1 … N 进行编号。每个物流基站 i 都有且仅有一个<br/>
后继基站 Si，而可以有多个前驱基站。基站 i 中需要继续运输的物资都将被运往后继基站 Si，显然一个物流基<br/>
站的后继基站不能是其本身。编号为 1 的物流基站称为控制基站，从任何物流基站都可将物资运往控制基站。注<br/>
意控制基站也有后继基站，以便在需要时进行物资的流通。在物流系统中，高可靠性与低成本是主要设计目。对于<br/>
基站 i ，我们定义其“可靠性” R(i) 如下：设物流基站 i 有 w 个前驱基站 P1,P2, … Pw ，即这些基站以 i<br/>
为后继基站，则基站 i 的可靠性 R(i) 满足下式：<br/>
<img width="195" height="62" alt="" src="/source/bzoj/1065/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC8yKDQpLnBuZw==.png"/><br/>
其中 Ci 和 k 都是常实数且恒为正，且有 k 小于 1 。整个系统的可靠性与控制基站的可靠性正相关，我们<br/>
的目标是通过修改物流系统，即更改某些基站的后继基站，使得控制基站的可靠性 R(1) 尽量大。但由于经费限制<br/>
，最多只能修改 m 个基站的后继基站，并且，控制基站的后继基站不可被修改。因而我们所面临的问题就是，如<br/>
何修改不超过 m 个基站的后继，使得控制基站的可靠性 R(1) 最大化。</p></div>

# Input

<div class="content"><p>　　输入第一行包含两个整数与一个实数，N，m，k。其中 N 表示基站数目，m 表示最多可修改的后继基站数目，<br/>
k 分别为可靠性定义中的常数。第二行包含 N 个整数，分别是 S1,S2…SN ，即每一个基站的后继基站编号。第三<br/>
行包含 N 个正实数，分别是 C1,C2…CN ，为可靠性定义中的常数</p></div>

# Output

<div class="content"><p>　　输出仅包含一个实数，为可得到的最大 R(1)。精确到小数点两位</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 1 0.5<br/>
2 3 1 3<br/>
10.0 10.0 10.0 10.0</span></div>

# Sample Output

<div class="content"><span class="sampledata">30.00</span></div>

# Hint

<div class="content"><p></p><p>　　对于所有的数据，满足 m≤N≤60，Ci≤106，0.3≤k&lt;1 ，请使用双精度实数，无需考虑由此带来的误差。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

