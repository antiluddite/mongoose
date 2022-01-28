# mongoose
Make sure you have a separate terminal opened into mongodb
use:

    mongod --dbpath=data 

in the mongodb folder to run.
have that running in the background before you run node-mongoose 

to start run this line in terminal:
npm start

***
if you run into this error:
    E11000 duplicate key error collection
with a bunch of other lines in the terminal

change the name of React Lake Campground in the index.js. and save and run again. that fixed it for me.
    const newCampsite = new Campsite({
        name: 'React Lake Campground',
        description: 'test'
    });
***