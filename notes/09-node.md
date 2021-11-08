# MVC
npm run start, debug and run window- either way will start the server but the debug window is best

Connect atlas Db can be commented out if you are not connecting to a database

Super is the first "door" in the 'hallway'

Base controller attaches your code to the door

.put('/:id')

key should be in string "name"

npm i -g bcw to update

in command line, cd into previous file and -> "cat .env" will show env file, we can then copy and paste.

If you clone a file from github, yo must create a new env file

Don't break the login, it's part of the checkpoint!

Account references the person logged in. Profile references a user on the system, as it shows less information.

Mongoose is an ORM, which essentially translates information to and from database

params are what's passed in through the url and the body is what's passed in the delete and put methods.

Many-to-many relationships can use an intermediary to tie together relationships. Class and student both have many relationships but can be tied together using enrollment.

One to one is least common type of data. Must point to each other.
One to many is most common. Parent (one) doesn't point to children (many), but children point to parent

404 error, it's not hitting the controller

collection/:id/collection is the restful url pattern
classes/:classId/books
theParent/parentId/childCollection
haveCollection/haveId/needCollection
/:param/

enum:[contains acceptable values] enum:['basic', 'priority', 'express'], uppercase: true, default: 'basic'