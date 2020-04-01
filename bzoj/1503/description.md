
# Description

<div class="content"><div>OIER公司是一家大型专业化软件公司，有着数以万计的员工。作为一名出纳员，我的任务之一便是统计每位员工的</div>
<div>工资。这本来是一份不错的工作，但是令人郁闷的是，我们的老板反复无常，经常调整员工的工资。如果他心情好</div>
<div>，就可能把每位员工的工资加上一个相同的量。反之，如果心情不好，就可能把他们的工资扣除一个相同的量。我</div>
<div>真不知道除了调工资他还做什么其它事情。工资的频繁调整很让员工反感，尤其是集体扣除工资的时候，一旦某位</div>
<div>员工发现自己的工资已经低于了合同规定的工资下界，他就会立刻气愤地离开公司，并且再也不会回来了。每位员</div>
<div>工的工资下界都是统一规定的。每当一个人离开公司，我就要从电脑中把他的工资档案删去，同样，每当公司招聘</div>
<div>了一位新员工，我就得为他新建一个工资档案。老板经常到我这边来询问工资情况，他并不问具体某位员工的工资</div>
<div>情况，而是问现在工资第k多的员工拿多少工资。每当这时，我就不得不对数万个员工进行一次漫长的排序，然后</div>
<div>告诉他答案。好了，现在你已经对我的工作了解不少了。正如你猜的那样，我想请你编一个工资统计程序。怎么样</div>
<div>，不是很困难吧？</div></div>

# Input

<div class="content"><div>第一行有两个非负整数n和min。n表示下面有多少条命令，min表示工资下界。</div>
<div>接下来的n行，每行表示一条命令。命令可以是以下四种之一：</div>
<div>名称<span class="Apple-tab-span" style="white-space:pre">	</span>格式<span class="Apple-tab-span" style="white-space:pre">	</span>作用</div>
<div>I命令<span class="Apple-tab-span" style="white-space:pre">	</span>I_k<span class="Apple-tab-span" style="white-space:pre">	</span>新建一个工资档案，初始工资为k。</div>
<div>                如果某员工的初始工资低于工资下界，他将立刻离开公司。</div>
<div>A命令<span class="Apple-tab-span" style="white-space:pre">	</span>A_k<span class="Apple-tab-span" style="white-space:pre">	</span>把每位员工的工资加上k</div>
<div>S命令<span class="Apple-tab-span" style="white-space:pre">	</span>S_k<span class="Apple-tab-span" style="white-space:pre">	</span>把每位员工的工资扣除k</div>
<div>F命令<span class="Apple-tab-span" style="white-space:pre">	</span>F_k<span class="Apple-tab-span" style="white-space:pre">	</span>查询第k多的工资</div>
<div>_（下划线）表示一个空格，I命令、A命令、S命令中的k是一个非负整数，F命令中的k是一个正整数。</div>
<div>在初始时，可以认为公司里一个员工也没有。</div>
<div>I命令的条数不超过100000 </div>
<div>A命令和S命令的总条数不超过100 </div>
<div>F命令的条数不超过100000 </div>
<div>每次工资调整的调整量不超过1000 </div>
<div>新员工的工资不超过100000</div></div>

# Output

<div class="content"><div>输出行数为F命令的条数加一。</div>
<div>对于每条F命令，你的程序要输出一行，仅包含一个整数，为当前工资第k多的员工所拿的工资数，</div>
<div>如果k大于目前员工的数目，则输出-1。</div>
<div>输出文件的最后一行包含一个整数，为离开公司的员工的总数。</div></div>

# Sample Input

<div class="content"><span class="sampledata">9 10<br/>
I 60<br/>
I 70<br/>
S 50<br/>
F 2<br/>
I 30<br/>
S 15<br/>
A 5<br/>
F 1<br/>
F 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
20<br/>
-1<br/>
2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

