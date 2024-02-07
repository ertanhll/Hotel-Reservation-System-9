Below, you can find the description of your ninth assignment, which also
includes its output in the Application Walkthrough section.
In this assignment, you are expected to improve your existing Hotel
Reservation System by incorporating couple of exception handling
mechanisms.
When the application starts, it should prompt the user with the existing menu
structure as before:
1. Create new Reservation with Room Type
2. Display all Reservations
3. List the reservations for a specific city
4. Add extra services to a reservation
5. Calculate total cost for each service
6. Display the total cost of every customer
7. Add an employee
8. Add a bill
9. Get monthly balance
10. List all Services sorted based on cost
11. List all Reservations sorted based on hotel names
12. Exit
However, now if the user selects a non-existing menu items – i.e. enters a
number that does not existing in the menu structure – the system should
response with an error (System.err) output stating that user has entered an
invalid menu option as shown below.
You entered an invalid menu option. Enter again.
You newly improved system should now check for user errors as part of its
interaction with the Hotel Reservation System. Accordingly, this improves
application should be able to catch at least some of the user’s intentional or
unintentional mistakes.
Therefore, during reservation creation, if the user enters a non-existing room
type or misspells it then the system should react and state that the Room type
entered is invalid. Furthermore, while entering reservation details, the system 
should prevent users entering text based information as the Reservation Start
and End values. The same control mechanism should be also valid when
creating a Laundry request and adding the number of clothing, booking for Spa
days, adding an Employee and checking whether the salary is provided in the
right format and adding new bills to the system.
All of the above exceptions could be checked using existing Exception classes.
However, to evaluate room type errors you should implement your own
exception called RoomTypeException. This exception should be thrown when a
room type input mismatch is detected



