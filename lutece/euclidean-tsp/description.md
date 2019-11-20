
# Content

![title](/source/lutece/euclidean-tsp/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMTExNi8yMDE1MDUxNjE1MzUwMjk2NzcxLmpwZw==.jpg)

The famous Arora-Mitchell approximation algorithm for the Euclidean Travelling Salesman Problem (Euclidean TSP) was discovered independently by Sanjeev Arora and Joseph S. B. Mitchell in 1998. It can approximate the value of an optimal TSP tour in d dimensions within a factor of 1+1/c in running time

####$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ n(\log n)^{O((c \sqrt d)^{d-1})}$

where n is the number of nodes in the tour.

Miroslava works for a computer security company and it is time to renew a shared cryptographic key in many data centres across Europe. To do this, Miroslava is going to rent a private jet and deliver the key to employees waiting at all major European airports. She wants to be back as soon as possible.

Miroslava’s company has a computer that is able to execute p billions of operations per second. Since we can approximate Europe by a two-dimensional plane, we assume that the Arora-Mitchell algorithm runs for exactly

###$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{n(\log _2 n)^{c \sqrt 2}}{p\cdot 10^9}$

seconds on this computer to produce the exact (1+1/c)-approximation of the optimal tour.

Miroslava noticed that c is a parameter of the algorithm that can be used to her advantage, but one also needs to be very careful when choosing the right value. If she sets c too low, the algorithm will finish very fast but the time she spends flying around Europe will be too long. On the other hand, setting it too high will force her to wait for an answer from the computer, while she could be flying instead.

Miroslava used to work in a different company and from there she knows that the optimal tour of all major European airports is s meters long, but she wasn’t ranked high enough in the company to know the actual tour. Given the speed v of the private jet in meters per second, Miroslava needs s(1+1/c)/v seconds to complete the tour produced by the algorithm run with parameter c. For the sake of simplicity, we assume that Miroslava can land, leave a copy of the private key and take off from each airport in an instant.

How long does it take Miroslava to first run the algorithm and then distribute all the keys, assuming that she chooses the optimal parameter c?

# Standard Input

The input consists of one line with four numbers:

>#####an integer n $(4≤n≤1000000)$, the number of airports;
>#####a real number p $(0.001≤p≤5000)$, the number of billions of operations the computer can execute per second;
>#####a real number s $(10^6≤s≤10^9)$, the length of the optimal tour of all European airports in meters;
>#####a real number v $(50≤v≤900)$, the speed of the private jet in meters per second.

All real numbers will have at most 10 digits after the decimal point.

# Standard Output

Output one line with the shortest possible time t in seconds to distribute the keys and the value of the parameter c Miroslava should use to achieve time t. Your answer should have an absolute or relative error of at most $10^{−6}$.

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
<tr><td>10 8.9 40075000 272.1</td><td>157079.04857106 15.598261092309</td></tr><tr><td>47 4.2 1337102.4 256</td><td>5836.2936298227 8.9113418228146</td></tr></table>


# Constraints



# Note



# Source


