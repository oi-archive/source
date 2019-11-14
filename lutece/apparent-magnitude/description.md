
# Content

*The scale now used to indicate magnitude originates in the Hellenistic practice of dividing stars visible to the naked eye into six magnitudes. The brightest stars were said to be of first magnitude ($m = 1$), while the faintest were of sixth magnitude ($m = 6$), the limit of human visual perception (without the aid of a telescope). Each grade of magnitude was considered twice the brightness of the following grade (a logarithmic scale). This somewhat crude method of indicating the brightness of stars was popularized by Ptolemy in his Almagest, and is generally believed to originate with Hipparchus. This original system did not measure the magnitude of the Sun. *

*In 1856, Norman Robert Pogson formalized the system by defining a typical first magnitude star as a star that is $100$ times as bright as a typical sixth magnitude star; thus, a first magnitude star is about $2.512$ times as bright as a second magnitude star. The fifth root of $100$ is known as Pogson's Ratio. *

<p class="text-right">-- from Wikipedia</p>

The apparent visual magnitude and its corresponding relative brightness are listed below (the accurate ratio is $\sqrt[5]{100}$ , and we use a rounded value here for simplicity ). Your task is to decide the apparent visual magnitude according to a given relative brightness.

<table class="table">
<thead>
<tr><th>Apperant magnitude</th><th>Brightness relative to Vega</th></tr>
</thead>
<tbody>
<tr><td>$1$</td><td>$[0.400, 1.000)$</td></tr>
<tr><td>$2$</td><td>$[0.160, 0.400)$</td></tr>
<tr><td>$3$</td><td>$[0.063, 0.160)$</td></tr>
<tr><td>$4$</td><td>$[0.025, 0.063)$</td></tr>
<tr><td>$5$</td><td>$[0.010, 0.025)$</td></tr>
<tr><td>$6$</td><td>$[0.004, 0.010)$</td></tr>
</tbody>
</table>

# Standard Input

The first line of the input is $T$ (no more than $1000$), which stands for the number of test cases you need to solve. 
Every case contains one line with a single real number standing for the star's brightness relative to Vega.

# Standard Output

For every test case, you should output `Case #k: ` first, where $k$ indicates the case number and counts from $1$, then output the grade of apparent magnitude. If the star is equally bright or brighter than Vega you should output `Too Bright`. If the star is less bright than a sixth magnitude star you should output `Invisible`. (The test data is specially designed so that you can simply ignore the precision problem of the float number)

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>5
1.0001
0.8
0.17
0.015
0.001</td><td>Case #1: Too Bright
Case #2: 1
Case #3: 2
Case #4: 5
Case #5: Invisible</td></tr></table>


# Constraints



# Note



# Source


