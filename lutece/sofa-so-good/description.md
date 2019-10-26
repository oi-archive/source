
# Content

Sofia's Sofa Salon specializes in synthesizing and supplying spectacular specialty sofas. Their manufac-turing process has been couched in mystery until recently, when it was revealed that the creation of a sofa is divided into two phases: framing and upholstering. When an order for a set of sofas comes in, the management team uses their knowledge of how quickly any particular worker can frame any given sofa to decide which worker will frame which sofa so as to minimize the total time spent framing.

Management always ensures there are exactly enough workers on the job to handle the order being lled, and each worker can frame only one sofa per order (due to a recurring series of repetitive motion injury claims).

Once the workers have begun framing, management performs an analysis of the upholstering phase knowing the time it takes each worker to upholster any given sofa. They must assign each worker exactly one sofa to upholster (potentially different from the one they framed) when they finish their framing. A worker may have to wait until the sofa they are assigned to upholster is finished being framed by another worker, so they start work on it once it's available. If they are idle between the framing and upholstering phases they usually relax in the company's recreational facility where they play tag (this room is called the chase lounge). Management tried to stop them from playing this game,but they were stymied by a sign reading "Do not remove this tag."

Since the workers are paid by the hour whether they are working or playing tag, management would like to assign them sofas to upholster so as to minimize the total number of hours that the workers are on-site (given the framing assignment determined earlier and the fact that each worker leaves as soon as they finish upholstering). Management is not prepared to solve such a deep-seated problem, so they have requested that you furnish a program to help them.

# Standard Input

Each test case will start with a positive integer $n \leq 50$ indicating both the number of sofas and the number of workers (no workers get to sit out). The following $n$ lines each contain $n$ positive integers;the $i\_{th}$ value on the $j\_{th}$ line indicates the time it takes the worker $j$ to frame sofa $i$ (workers and sofas are numbered starting at $1$).
Following this are $n$ more lines each containing $n$ positive integers describing the upholstering times in a similar format. All times given will be no greater than $1000$. A line containing a single $0$ will terminate the input.

# Standard Output

For each test case, output the case number followed by $n$ lines, one per worker (starting with worker$1$). For each worker, list the sofa they framed, the sofa they upholstered, and the time at which they finished their upholstering work, assuming all workers start framing at time $0$. There will be exactly one optimal pairing of workers and couches for each phase. Following these lines, output the total idle time spent by the workers in the chase lounge during that order. Use the format shown in the example.

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
<tr><td>4
8 6 12 19
13 2 18 10
9 15 16 17
5 18 4 10
2 6 3 3
8 5 9 2
5 8 4 3
4 4 5 2
0</td><td>Case 1:
Worker 1: 2 3 9
Worker 2: 4 4 12
Worker 3: 1 1 14
Worker 4: 3 2 10
Total idle time: 2</td></tr></table>


# Constraints



# Note



# Source


