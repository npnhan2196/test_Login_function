# test_Login_function
There are many functions on this code file.
I will saparate login page with many steps:
1. Check the load of login page
2. After clicking Register/ Login button > Verify the load of next page
3. Input username
4. Input password
5. Click login button
All of these small functions will be combined in the keyword page (Page Object Model) which was created to control others functions (like logout, register,...)
After that, I will use robot framework to add this page as a library, after that, I will call these functions and run by robot file.
