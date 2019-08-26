
# Description

<div class="content"><div>银河队选手名单出来了！小林，作为特聘的营养师，将负责银河队选手参加宇宙比赛的饮食。众所周知，前往宇宙</div>
<div>的某个星球，通常要花费好长好长的时间，人体情况在这之间会发生变化，因此，需要根据每天的情况搭配伙食，</div>
<div>来保证营养。小林把人体需要的营养分成了n种，这些营养包括但不限于铁，钙。他准备了2套厨师机器人，一套厨</div>
<div>师机器人有n个，每个厨师机器人只会做一道菜，这道菜一斤能提供第i种营养xi微克。想要吃这道菜的时候，只要</div>
<div>输入一个数，就能吃到对应数量的这道菜了。为防止摄入过量对身体造成的伤害，每个机器人还有防过量摄入药，</div>
<div>只要输入一个数，就能生成一定剂量的药，吃了这些药，就能减少相当于食用对应数目的这道菜提供的营养。小林</div>
<div>之所以准备2套厨师机器人，正是因为旅途漫漫，难以预计，也许某一个厨师机器人在途中坏掉，要是影响了银河</div>
<div>队选手的身体，就不好了。因此，第2套厨师机器人被用来做第1套的备用。小林需要为每一个第1套厨师机器人选</div>
<div>一个第2套厨师机器人作备份，使得当这个机器人坏掉时，用备份顶替，整套厨师机器人仍然能搭配出任何营养需</div>
<div>求，而且，每个第2套厨师机器人只能当一个第1套厨师机器人的备份。</div></div>

# Input

<div class="content"><div>第一行包含一个正整数n。</div>
<div>接下来n行，每行n个整数，表示第1套厨师机器人做的菜每一斤提供的每种营养。</div>
<div>再接下来n行，每行n个整数，表示第2套厨师机器人做的菜每一斤提供的每种营养。</div>
<div>1≤n≤300，所有出现的整数均非负，且不超过10,000。</div></div>

# Output

<div class="content"><div>第一行是一个字符串，如果无法完成任务，输出“NIE”，否则输出“TAK”</div>
<div>并跟着n行，第i行表示第i个第1套机器人的备份是哪一个第2套机器人。</div>
<div>为了避免麻烦，如果有多种可能的答案，请给出字典序最小的那一组。</div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
1 0 0<br/>
0 1 0<br/>
0 0 1<br/>
2 3 0<br/>
0 7 8<br/>
0 0 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">TAK<br/>
1<br/>
2<br/>
3</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

