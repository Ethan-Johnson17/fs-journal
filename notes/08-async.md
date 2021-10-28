# Async
C- Create   .Post  Post takes two arguments (where, what)(url, data)('cars', carData)
R- Read     .Get ('cars')
U- Update   .Put ('cars/' + id, carData being saved)
D- Destroy  .Delete ('cars/' + id)
CRUD and HTTP METHODS

async getPeople(){
    try{
        await whatever.service.getPeople()
        console.log
    } catch (error)
}

!! console.log(res.data) !!

controller handles the try/catch

use splice and random number between 1-3 for trivia game


..../cars?make=ford&color=red
in a url this would essentially be saying category cars where the make is ford and the color is red

map turns pojo into array of cpecific class

data.desc.join('\n') joins on paragraph break.
.join() whatever is in the parenths is what string is joined on. 

single layer part of the or should be first, then put the deeper layer. On the deeper layer, you can use the elvis operator(?) to check if it even applies.

.find (s => s.id == id)
find spell WHERE spell id is equal to id