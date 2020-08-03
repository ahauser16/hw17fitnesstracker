nosql table in mongo
====================================
{
    name
    type of weight
    sets
    duration-of-exercise
}
 =======================================

 <aside> you could either make a new table adding "distance" or just add "distance to the previous table and not use it.  best practice is to make another table

 ====================================
 {
    name
    type of weight
    sets
    duration-of-exercise
    distance
}
=========================================

step 1: create a no sql table for resitance and cardio as seen above.


///////////////////////////////////
step 2: set up the server to make ajax calls
point a = database
point b = server
you connect the two with an API call



///////////////////////////////
step 3: make an ajax call to backend server from the frontend to establish connection.


///////////////////////////////
step 4: create html and css elements


///////////////////////////////
step 5: fill in javascript functionality



///////////////////////////////
step 6: debug and refactor



///////////////////////////////
other steps would include:
1.  set up routes
2.  schema (is setup already)
push new exercise line 24

how do you keep track of the person's session?
choices:
1. localstorage or session storage
2. have a database for sessions, then grab th emost recent session with an ajax call
    if we get something back then render continue button 
    else render only the new workout button

session

{
    
time

}

{

time

}
{

time

}