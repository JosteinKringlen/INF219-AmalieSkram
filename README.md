# Making data available - Real data for students
This project was started by Amalie Skram high school in Bergen, Norway. 
Having the possibility to use "real data" for tasks and problems for the
students, they wanted to use the buoy Gabriel in Store Lungaardsvann and
its measurements, and making these measurements available to the students.

When this project was initiated, the database already had data going back to May 2015, but there was no simple way for the students to access this information. Amalie Skram high school asked for volunteers from the University in Bergen to create their solution. A group of four students picked up the offer, and using the project as a course in our studies. The result can be found here: http://www.ektedata.no/no/innhold/utvalg-av-data

What needed to be done was connecting the database to a user friendly 
environment for the students to use. The stack we ended up using was:

* **MongoDB** for DB (this was the database already up and running)
* **Node.js** for back-end
* **Pug-Bootstrap** for front-end

While creating and testing the program, we have used Heroku to run the 
node.js application, and Mlab to host the database. Both of these 
services had free options suiting our needs well. In the end this is 
probably going to be hosted by the University in Bergen itself.

## This is the foundation (hopefully) of a bigger project
This project and this repository is hopefully the foundation of a bigger
project. There are monitoring stations like the buoy Gabriel in many places,
everything from weather stations to drill holes in the mountains, where
data is measured, but not easily available for the public, or schools,
to use. These measurements, if saved in the same way, can hopefully use 
our code, probably needing some adjustments, but hopefully not many, to
make it available in the same way, in the same portal created here.


### Installation
The installation is easy, and can be done locally on a machine, or on a server.
To install and run the project, you need to have Node.js installed. For more information on Node.js, and installation guides, check out https://nodejs.org/en/

When Node.js is installed, clone the project:

`git clone https://github.com/JosteinKringlen/INF219-EkteData.git`

After that, enter the project folder and run the following command:

`npm install`

This will install all the necessary files for the project to run.



When the installation is done, you can start the project!
This can be done by either running _www.js_ in the _bin_ folder **or**
running the following command:

`npm start`
