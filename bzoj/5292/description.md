
# Description

<div class="content"><div>（没玩过《炉石传说》的人可以跳过这一段）今天我们来探讨下《炉石传说》中“治疗之雨”（恢复12点生命值，</div>
<div>随机分配到所有友方角色上）和“暗影打击装甲”（每当一个角色获得治疗，便对随机敌人造成1点伤害）这两张</div>
<div>卡牌之间的互动效果。假设你场上有m个剩余生命值无限大且生命值上限减去剩余生命值也无限大的随从，而对方</div>
<div>的场上有k个暗影打击装甲，你的英雄剩余生命值为p、生命值上限为n，现在你使用了一张可以恢复无限多（而不</div>
<div>是12点）生命值的治疗之雨，问治疗之雨期望总共恢复了几点生命值以后你的英雄会死亡（生命值降为0；治疗之</div>
<div>雨的判定机制使得在此后再也不会为英雄恢复生命值）。</div>
<div>注：题目背景与题目描述有冲突的地方请以题目描述为准</div>
<div>下面让我们再形式化地描述一遍问题。</div>
<div>题目描述</div>
<div>你现在有m+1个数：第一个为p，最小值为0，最大值为n；剩下m个都是无穷，没有最小值或最大值。</div>
<div>你可以进行任意多轮操作，每轮操作如下：</div>
<div>在不为最大值的数中等概率随机选择一个（如果没有则不操作），把它加一；</div>
<div>进行k次这个步骤：在不为最小值的数中等概率随机选择一个（如果没有则不操作），把它减一。</div>
<div>现在问期望进行多少轮操作以后第一个数会变为最小值0。</div>
<div></div></div>

# Input

<div class="content"><div>输入包含多组数据。</div>
<div>输入第一行包含一个正整数T，表示数据组数。</div>
<div>接下来T行，每行4个非负整数n、p、m、k（含义见题目描述），表示一次询问。</div>
<div>1≤T≤100 </div>
<div>1≤p≤n≤1500</div>
<div>0≤m,k≤1000000000 。</div>
<div>保证不存在n=p=k=1 ,m=0 的情况（因为出题人判错了）</div>
<div>保证不存在答案的分母是1000000007 的倍数的情况（因为出题人没想到）</div>
<div></div></div>

# Output

<div class="content"><div>输出T行，每行一个整数，表示一次询问的答案。</div>
<div>如果无论进行多少轮操作，第一个数都不会变为最小值0，那么输出-1；</div>
<div>否则，可以证明答案一定为有理数，那么请输出答案模1000000007的余数，</div>
<div>即设答案为b/a（a、b为互质的正整数），你输出的整数为x，</div>
<div>那么你需要保证0≤x&lt;1000000007且a≡bx mod 1000000007</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 1 1 1<br/>
2 2 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
8</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢佚名上传">鸣谢佚名上传</a></p></div>

