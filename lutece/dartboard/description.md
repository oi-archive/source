
# Content

Jaap is playing darts at the local pub with a group of friends. His darts throwing skills are not that great, so he just tries to aim at the center of the dartboard. His mathematical skills are better though, and he wonders what is his expected score for one dart. 

After a while Jaap estimates that his darts hit the dartboard (or often miss it) with a probability distribution that depends only on the radius $r$ from the center of the board, and has the Gaussian form $$f(r) = \frac{1}{2\pi\sigma^2}e^{-\frac{r^2}{2\sigma^2}} $$

That is, the probability of hitting a small surface area $\Delta x \cdot \Delta y$ at a distance $r$ from the center is given by $f(r)\Delta x\cdot \Delta y$ Here $\sigma$ denotes the standard deviation, and Jaap found out that this depends strongly on how many beers he has had.

For those not familiar with the game of darts, a dartboard is depicted below. The score for hitting each of the regions of the dartboard is as follows:

* the inner *bull's eye* is worth $50$ points;
* the *bull* annulus is $25$ points;
* each pie has worth of the respective number $1$ up to $20$, but
* the inner *triple ring* has triple the worth of the pie, while
* the outer *double ring* has double the worth.

Finally, if the dart lands outside the double ring, the score is zero. Note that the pies of all numbers have equal area.

![title](/source/lutece/dartboard/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODY1LzIwMTQwNTA0MDMwNzE1NzQ1MTgucG5n.png)

**Figure J.1: A standard dartboard (from Wikimedia, CC BY-SA 3.0 licensed by Tijmen Stam).**

# Standard Input

The first line contains 6 floating point numbers of strictly increasing size: the radii of the *bull’s eye*, *bull*, inner and outer *triple ring*, and inner and outer *double ring*, all in centimeters. The second line contains the standard deviation $\sigma$ in centimeters as a floating point number. All floating point numbers are in the range $[10^{-3}, 100]$.

# Standard Output

Print the expected score of one dart for Jaap as a floating point number on a single line. The answer should be correct up to either a relative or absolute error of $10^{-4}$.

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
<tr><td>1.27 3.1 10.9 11.7 16.2 17.0
17.0</td><td>5.266210658</td></tr><tr><td>1.27 3.1 10.9 11.7 16.2 17.0
0.5</td><td>49.00690019</td></tr><tr><td>0.1 0.2 0.3 0.4 99.9 100
20</td><td>10.50283655</td></tr></table>


# Constraints



# Note



# Source


