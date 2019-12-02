
# Content

You're assigned the job of making a booking system for a special services company. This company conducts all sorts of services, but you are told not to ask any questions. There have been some developers before you that have tried making this system, but sadly none of them are anywhere to be found, so you can't ask them for any help.

The system is receiving bookings (and cancellations) one by one, and must immediately accept/reject the booking.

All bookings last for a whole day, and the part of the system you're making needs to keep track of a single day.

The company has a number of employees, each having one or more qualifications. Each booking, in addition to having been a given numeric identifier, demands a number of people (employees), each having a specific qualification. One person can cover at most one demand from one booking during the whole day. The director used Mario as an example; while Mario can be both a plumber and an assassin, in a single day he can only do one of the jobs for one booking (in this company).

A booking is accepted if and only if there are no active bookings with that specific identifier, and it is possible, using the given employees, to cover all the demands of the currently active bookings as well as the new one.

A cancellation is accepted if and only if there is an active booking with that specific identifier.

# Standard Input

The first line contains $T$, the number of test cases that follow. Each test case starts with a line containing the numbers $N$ and $B$, the number of employees and bookings/cancellations in the test case.

Then there follow $N$ lines, each specifying an employee. Each line consists of a number, $c$, followed by $c$ strings delimited by whitespace, giving the names of each qualification of that particular employee.

Subsequently there follows $B$ lines, each containing either a booking or a cancellation.A booking starts with the word book. Then follows the numeric identifier I of that booking, followed by the number d and then finally d strings delimited by whitespace. This gives all qualification demands this booking has. A cancellation consists of the word cancel followed by a number referring to the identifier I of the booking to be cancelled.

$0 < T \le 50$

$1 \le N \le 200$

$1 \le B \le 1000$

$1 \le c \le 16$

$0 \le d \le 16$

$0 \le I \le 1000$

Qualification names will be at most $10$ characters long. There will be no more than $100$ different qualifications shared among all the employees.

An active booking is one that has been accepted, and not successfully cancelled.

It is possible to make bookings reserving no people whatsoever. These bookings will be handled by the company manager, and you should keep on asking no questions.

This is an I/O-heavy problem. For Java programmers, this means that you should use BufferedReader for input reading (not Scanner).

# Standard Output

For each booking/cancellation, output a single line of output. The line should consist of the word Accepted if the booking/cancellation is accepted, or Rejected otherwise.

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
<tr><td>2
1 1
1 slacker
book 6 1 worker
3 6
2 plumber nurse
2 nurse assassin
2 assassin plumber
cancel 1
book 1 2 plumber assassin
book 123 1 nurse
book 4 3 assassin nurse plumber
cancel 1
book 4 2 nurse assassin</td><td>Rejected
Rejected
Accepted
Accepted
Rejected
Accepted
Accepted</td></tr></table>


# Constraints



# Note



# Source


