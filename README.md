# PROJECT-Vintage-cars-database
 -use the requests module facilities    -cooperate with a remote database using REST.
 
 Your client has asked if you are able to write and deploy a software solution managing a small database that gathers data about vintage cars. Of course you are! It's a piece of cake for a programmer like you.

To be honest, all the blocks needed to construct such an application are already at your fingertips. Your task is to integrate them into one cooperating product.

Information to run Json server with CMD.

...if you're a Windows user, run the CMD.EXE program.

Node.js utilizes its own native tool for installing and updating components. Its name is the same under all the platforms covered, so when you issue the following command:

npm

Now we’re going to ask the npm to download and install the json-server package, along with all the packages needed to run it, so you should expect some delay – be patient and issue the following command:

npm install -g json-server

We need to perform a brief test to ensure that the server is operating correctly. Do the following actions:

download the JSON file cars.json ,and save it in your home directory or any other directory you have the proyect

return to the system console and issue the following command:

json-server --watch cars.json


Now open your favorite Internet browser and type the following URL into the address line:

http://localhost:3000

after that you can run code , it should work.



