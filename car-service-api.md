1. POST: `/cars` customer car add his new car to a DB
2. GET: `/cars` admin and manager can retrieve a list of all car in DB with paging and sorting
3. GET: `/cars/by-owner/{ownerId}` manager can retrieve a list of cars by user id
4. PUT: `/cars/{carId}` customer can update own car and admin can update all cars info by car id
5. DELETE: `/cars/{carId}` customer can delete only own car and admin can delete all cars by id
6. GET: `/cars/my-list` customer can retrieve a list of all his cars
7. 