As a CUSTOMER I can:

1. register a new account
2. fetch info about my account
3. register a new car
4. update info about my cars
5. delete my car from the list
6. get the list of my cars
7. create a new order for repairing my car with setting complaints
8. cancel the order when its status CREATED
9. retrieve a list of all my orders
10. get info about order by its id
11. pay the order
12. left the comment to the order

As an ADMIN I can:

1. delete role from a user by its id
2. add role to a user by its id
3. find any users info by id
4. retrieve a list of all cars from DB with pagination
5. update any car in DB by id
6. delete any car from DB by id
7. create new account for manager and mechanic
8. delete any account by id

As a Manager I can:

1. find any users info by id
2. retrieve a list of all cars from DB with pagination
3. retrieve a list of cars by user id
4. approve a new order and set the visit time
5. cancel the order when its status CREATED, APPROVED, CAR_RECEIVED OR IN_PROGRESS
6. approve the arrival of the car and set status CAR_RECEIVED to the order
7. set status SUSPENDED to an order when it is a leak of some details
8. create a new detail in DB
9. add an amount of details to the store
10. change detail info
11. add detail to an order
12. remove detail from order
13. add work to an order 
14. remove work from an order

As a mechanic I can:
1. approve that the car is on the post by setting status IN_PROGRESS
2. add a new performed work to an order
3. add a new detail to an order
4. inform the manager about the missing details through repairing log
5. after completing the repairing set status COMPLETE 
6. get info about his account