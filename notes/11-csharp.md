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