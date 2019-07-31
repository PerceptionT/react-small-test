## First Page should be login screen. After login below grocery list page should display.

## Grocery List Page

You have a Grocery product list class, which receives a list of products, each one with name and votes. Properties of your class is Grocery name (text) and upvote (integer)

Products can be upvoted or downvoted. (This is same feature like we have upvote and downvote on stackoverflow.com)

The app should render a list according to upvoted product should be display first then downvoted product should be display.

User can upvote or downvote the product and list should be refreshed again. You can do this by local state update.

Also add search bar on top of list and add functionality of local search (i.e. search from the array). 

## API for Login
(Identify the below payload fields and add your inputs to login screen).

Api : - https://wwwdev.lugelo.com/api/v0/login/
Method :- Post

``` Sample Payload :-
var payload = {
  email: "aamir@perceptionsystem.com",
  password: "123456"
}````

