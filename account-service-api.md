1. POST: `/register` registration a new user with default role 'customer'  (permit all)
2. GET: `/users/{id}` find user info by user id (customer, manager, admin)
3. PATCH: `/users/{userId}/delete-role?value=<role-name>` admin can delete specified role from users role list
4. PATCH: `/users/{userId}/add-role?value=<role-name>` admin can add specified role to users role list
5. 