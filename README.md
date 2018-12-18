Here is the class project  - a campus  car rental system. Users (students and faculty)  can rent cars to use for errands or pleasure.  
Arlington Auto has a fleet of 9 cars as follows (only one of each kind):
 	 	Rate	Extra Rates (/day)
    
Car Name	Capacity	Weekday	Weekend	Week	GPS	OnStar	SiriusXM
Smart	1	$32.99	$37.99	$230.93	$3.00	$5.00	$7.00
Economy	3	$39.99	$44.99	$279.93	$3.00	$5.00	$7.00
Compact	4	$44.99	$49.99	$314.93	$3.00	$5.00	$7.00
Intermediate	4	$45.99	$50.99	$321.93	$3.00	$5.00	$7.00
Standard	5	$48.99	$53.99	$342.93	$3.00	$5.00	$7.00
Full Size	6	$52.99	$57.99	$370.93	$3.00	$5.00	$7.00
SUV	8	$59.99	$64.99	$419.93	$3.00	$5.00	$7.00
MiniVan	9	$59.99	$64.99	$419.93	$3.00	$5.00	$7.00
Ultra Sports	2	$199.99	$204.99	$1,399.93	$5.00	$7.00	$9.00

Arlington Auto club members get a 10% discount on all rentals. Tax is 8.25%. Weekends are Sa & Su.
Partial day rentals are charged a full day. Rentals are 24-hour periods - if any portion of that 24-hour period is a weekend rate the entire day is charged weekend. For example, a Car rental that starts on Thursday at 6pm and returns on Sat 10am would be charged one Weekday rental and one Weekend day rental. A week rental is 7-days.
Arlington Auto is only open during the following hours:
Day	Hours
M-F	8am-8pm
Sa	8am-5pm
Su	noon-5pm

Check-out dates and return dates must conform to these times.
 
Three different kinds of users for the system:

1.	Rental manager 
a.	creates own profile
b.	views calendar of all cars rented
c.	views details of a specific rental
d.	views available cars for a given date/time
e.	deletes a rental
f.	update his own profile

2.	User
a.	creates own profile
b.	requests rental - items, number of occupants, date, time, duration, extras
i.	The software only shows available cars that meet the minimum occupant capacities
ii.	each car shows estimated prices based on selections.
c.	view my reserved rentals
d.	cancel my reserved rentals
e.	confirm/pay for my reserved rentals
f.	update profile

3.	Admin
a.	creates own profile
b.	edit user profile
c.	change user roles
d.	revoke renter (renter still exists in system but cannot rent a car)

All users will have the standard functions like register, login, logout. Each system user must register and for simplicity selects their role during registration. Assume that a single user that has multiple roles, e.g. User and Rental manager would register twice with different ids. Each user registers with at least a user name, role, UTA id, and personal details, contact information.
The system takes only credit cards: Visa, MasterCard, AMEX and Discover. For simplicity, payments that have valid credit card formats will be accepted. A confirmation is returned once payment is accepted.
Project must use - Java, Eclipse, Tomcat and MySQL.   Testing must use JUnit and Selenium. PHP and JavaScript is NOT allowed.
Please indicate your team's experience in the chosen solution approach above.
Project weighting:
1.	A01 - Application attributes and validation requirements - 15%
2.	A02 - Team demonstrations of working functionality - 25%
3.	A03 - Team demonstration of Half App Testing - 30%
4.	A04 - Team demonstration of Full App Testing - 30%
