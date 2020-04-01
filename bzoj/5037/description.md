
# Description

<div class="content"><div>JYY创建的电信公司，垄断着整个JSOI王国的电信网络。JYY在JSOI王国里建造了很多的通信基站。目前所有的基站</div>
<div>都是使用2G网络系统的。而现在3G时代已经到来了，JYY在思考，要不要把一些基站升级成3G网络的呢？JSOI王国</div>
<div>可以被看作为一个无穷大的二维平面，JYY一共建造了N个通信基站，第i个基站的坐标是(Xi,Yi)。每个基站有一个</div>
<div>通信范围Ri。第i号基站会向所有到其距离不超过Ri的基站发送信息。每个基站升级到3G网络都会有一个收益Si，</div>
<div>这个收益可能是正数（比如基站附近有个大城市，用户很多，赚的流量费也就很多了），也可能是负数（比如基站</div>
<div>周围市场不佳，收益不能填补升级基站本身的投资）。此外，由于原有的使用2G网络系统的基站无法解析从升级成</div>
<div>3G网络系统的基站所发来的信息（但是升级之后的基站是可以解析未升级基站发来的信息的），所以，JYY必须使</div>
<div>得，在升级工作全部完成之后，所有使用3G网络的基站，其通信范围内的基站，也都是使用3G网络的。由于基站数</div>
<div>量很多，你可以帮助JYY计算一下，他通过升级基站，最多能获得的收益是多少吗？</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个整数N；</div>
<div>接下来N行，每行4个整数，Xi，Yi，Ri，Si，表示处在(Xi,Yi)的基站的通信</div>
<div>范围是Ri，升级可以获得的收益是Si。</div>
<div>数据满足任意两个基站的坐标不同。</div>
<div>1≤N≤500，1≤Ri≤20000，|Xi|,|Yi|,|Si|≤10^4。</div>
<div></div></div>

# Output

<div class="content"><p> 输出一行一个整数，表示可以获得的最大收益。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
0 1 7 10<br/>
0 -1 7 10<br/>
5 0 1 -15<br/>
10 0 6 10<br/>
15 1 2 -20</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
【样例说明】<br/>
我们可以将前三座基站升级成 3G 网络，以获得最佳收益。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Round1">Round1</a></p></div>

