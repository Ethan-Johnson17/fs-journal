# C#
dotnet new to create new project
propG
Constructors are all public methods with the name of the class, no constructor. Created using ctor shortcut.
Can also generate constructor from the class.
Random number:
Random rand = new Random();
int moneyMade = rand.Next(1,5); //random number between 1 and 5
<> means of type --> <IEnumerable<string>> of type IEnumerable of type string
[HttpGet] identifies the code below as a get
Transient makes service(or other file) available to controllers(or other files) that are created. Done instead of export and import. 
In a post request, the req.body of old is now FromBody and must be defined within the class

launch JSON is wehre you can change where app spins up. reference Santas Workshop. Base URL will also need to be changed in env.js file.
Console.Beep()

View model is used to capture the additional information needed for a many to many relationship. Without it, the information will not be stored and just disappears.

When doing a SELECT, FROM, JOIN, WHERE --> don't feel like you have to go top to bottom. Start with what's easiest. Usually, that's FROM, WHERE, JOIN, and SELECT.
JOIN is where you inout what you want to get back. Find stations (s) ON ...
SELECT s (^From above)
AS renames the column, this will prevent one id from overriding another.




Checkpoint
Create a different server call for the home page filters
Warm up with leetcode, edabit, or similar

REVIEW WEEK
TINYINT can be used for boolean. The value can be either 0 (false), or 1 (true). Bool is changed to tinyint anyway. 

Interface basically says whatever model uses this interface requires what is on the interface. Interface does not give those properties, inheritance does. 
Inheritance is singular but can be combined with interface, Interface can have multiple.
Inheritance is done by extending a class. Interface is it's own class.
Interface should be limited to the things absolutely necessary, like if you had a purchaseable interface, color is not required to purchase but price is.

To make tinyInt nullable, add elvis operator in the model. Reference Habits model in MyResolutions app.
[MinLength] can be used in the model as well, it would go above the property.

Split on splits on id, so join order matters.

DTO creates a model that contains other models.
GroupMemberView model extends the group model, so it contains the GroupMemberId and all group properties.

On front end, if you want to do something as soon as user is authenticated, put it in authservice. Reference Mick's GroupMe.
For class binding examples, also see GroupMe.

If you do an interface with a <t> type, use the int or string when extended it. -> class : interface<int>
Text cannot have a default value, must use varchar. reference GoodEats.