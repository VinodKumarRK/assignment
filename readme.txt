
Open index html file 
Create an account by clicking on create account link on login page
Login with same credentials which you have used while creating account.
After login it will be redirected to checklist page
you add item by entering name and clicking on add button.
Added item will be displayed on bottom of text field with checklist label.
You can to move item to completed state by clicking on checkbox on left side of item.
You can delete item by clicking on delete button on right side of item.
You can move item position by entering index value like 0,1 or 2 in given input field on right side on item



Used javascript sessionStorage for storing user data with unique id(userid).
Storing added list items into sessionStorage with respect to userid.

Faced issues:
1.After adding item just do logout and login after login not able to retrive items with respect to user.
solu: Before showing checklist content checking userid is exist or not in sessionStorage if exist then added item data will be retrived wrt userid.

2.After adding item just do logout and login after login not able to move check list items to completed state.
3.After adding item just do logout and login after login not able to delete check list items.
4.After adding item just do logout and login after login not able to move check list items.
solu: Before performing any action with checklist items checking data is exist or not with respect to userid in sessionStorage.




