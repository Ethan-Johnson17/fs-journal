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