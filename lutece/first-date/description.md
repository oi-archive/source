
# Content

In 1582, pope Gregory XIII decreed a calendar reform to bring the mean length of the calendar year (counted in days)
  more in line with the actual number of days in an astronomical year.
This calendar reform entailed a transition from the Julian calendar to the Gregorian calendar.

Both the Julian and Gregorian calendars have regular years with 365 days, and so-called *leap years* with 366 days.
In regular years, the month February has 28 days, while in leap years, it has an extra `leap day`: February 29th.

The single difference between the Julian and Gregorian calendars is in their rule to determine if a year is a leap year.
In the Julian calendar, leap years are those years that are divisible by~4.
The Gregorian calendar's rule for determining leap years is a bit more complicated: years divisible by 4 are leap years, unless they are divisible by 100 but not by 400.

Following these rules, the years 1600, 1700, 1800, 1900, 2000, 2100, 2200, 2300, and 2400 are all leap years in the Julian calendar. In the Gregorian calendar, the only leap years in this list are 1600, 2000, and 2400.

The old Julian calendar has a mean year length of 365.25 days, while the new Gregorian calendar has a mean year length of 365.2425 days.
Given that the actual number of days in an astronomical year is about 365.24219 days, you can see why the Gregorian calendar is an improvement.

As part of the Gregorian reform, a number of dates were skipped, to reverse the effects of having used the Julian calendar for over 1500 years.
Specifically, the Gregorian reform decreed that October~4, 1582 (Julian) was to be followed by October~15, 1582 (Gregorian).

However, by the end of the 16th century the Reformation was in full swing.
While the Catholic countries tended to follow the Papal decree, many countries continued using the Julian calendar until much later.
For example, the United Kingdom switched from the Julian calendar to the Gregorian calendar on September~2, 1752 (Julian) which was followed by September~14, 1752 (Gregorian) --- by that time, 11 dates had to be skipped to make the switch.
The last European country to switch was Greece, which made the transition as late as February~15, 1923 (Julian) which was followed by March~1, 1923 (Gregorian), skipping 13 dates.

Given the last day for which the Julian calendar is in effect for some country (expressed as a Julian date),
determine the next day's Gregorian date, i.e., the first date that uses the Gregorian calendar.

# Standard Input

For each test case, the input consists of one line containing a date in the Julian calendar, formatted as `YYYY-MM-DD`.
This date will be no earlier than October~4, 1582, and no later than October~18, 9999.
The given date represents the last day that the Julian calendar is in effect for some country.

# Standard Output

For each test case, print the first Gregorian date after the calendar transition.

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
<tr><td>1582-10-04
1752-09-02
1900-02-25
1923-02-15</td><td>1582-10-15
1752-09-14
1900-03-10
1923-03-01</td></tr></table>


# Constraints



# Note



# Source


