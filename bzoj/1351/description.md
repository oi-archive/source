
# Description

<div class="content"><div>This problem considers how mighty countries arise from humble beginnings. Consider a two-dimensional map of the area. On this map there are n cities. Each city i is in a distinct location with coordinates (xi, yi) on the map. The city has also a number si of soldiers in it under the command of a general.</div>
<div>The influence city i exerts to another location (x, y) is computed as si divided by the squared distance between it and (x, y). It is as if the mass of soldiers in city i exerted a gravitational pull to all map locations around it. City i is threatened by another city j if the influence exerted by city j on the location (xi, yi) of city i exceeds its number of soldiers si: then city j can dispatch enough soldiers to overpower all the soldiers defending city i. If city i is not threatened by any other city j, then its grateful citizens elect its invincible general as their king, and turn their city into the capital of his kingdom.</div>
<div>On the other hand, if some city j threatening city i exerts strictly more influence on its location (xi, yi) than any other city k, then the citizens of city i have no choice: city I must surrender to city j. Henceforth city i must obey the same capital as city j obeys; however, the si soldiers in city i do not join the army of city j or the capital. Otherwise city i is saved by mutual distrust of the equally threatening cities j and k: If one of them would attack and overpower city i, then the other would in turn attack and overpower the battle-weary first attackers. However, the citizens of city i can no longer elect its general as their king, because he has failed in his duty to keep the city safe from threats. Thus they must turn their city into the capital of a democracy instead.</div>
<div>Your task is to write a program, which takes the information about the cities on the map as inputs, and outputs for each city i one of the three outcomes:</div>
<div>• It is the capital of a kindgom.</div>
<div>• It is the capital of a democracy.</div>
<div>• It obeys city j as its capital.</div></div>

# Input

<div class="content"><div style="font-size: 11.8181819915771px;">The input is read from a text file named countries.in. The first line consists of one integer 1 ≤ n ≤ 1000, the number of cities. The following n lines give the information on the n cities, each city as its own line. Line i + 1 gives the information on city i as the three integers xi, yi, si which are separated by single space characters. All these numbers are in range 0 ≤ xi, yi, si ≤ 1000.</div></div>

# Output

<div class="content"><div style="font-size: 11.8181819915771px;">The output is written into a text file named countries.out. The output consists of n lines, where line i consists of the outcome for city i:</div>
<div style="font-size: 11.8181819915771px;">• The character K if city i is the capital of a kingdom.</div>
<div style="font-size: 11.8181819915771px;">• The character D if city i is the capital of a democracy.</div>
<div style="font-size: 11.8181819915771px;">• The number 1 ≤ j ≤ n of the city which city i obeys as its capital if city i had to surrender.</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 5 14<br/>
2 3 2<br/>
3 2 7<br/>
1 1 2<br/>
2 1 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">K<br/>
D<br/>
K<br/>
3<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

