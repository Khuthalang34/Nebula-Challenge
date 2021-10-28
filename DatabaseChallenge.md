Question 1

In the ERD diagram I think EventID is a preferable foreign key / reference to phone number, because what if an employee is managing 
more then one event? What if two employees share a phone number? What if those two manage different events? I think it might even be 
justified to add another table for EventID, EmployeeGUID so you could have any amount of Employees managing an Event, and have any 
Employee managing any amount of Events. Normalizing the ERD diagram would be an appropriate solution.

Question 2

CREATE VIEW [Tickets] AS
SELECT Genre
FROM Movies
WHERE Month = "December";
