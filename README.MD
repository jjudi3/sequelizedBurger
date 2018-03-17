Burger App Using Sequelize
1. Create a new folder called sequelizedBurger
2. Copy the contents of your completed assignment from last week.
o Remove the older git connection with rm -R .git.
o Then connect this folder with a new github repo.
3. Run sequelize init to create the necessary files.
4. Note: If for any reason you don't have a finished assignment for last week, no problem. Message the instructor, who will provide you will a skeleton file to work of for this week.

Remove all references to your vanilla MySQL queries and replace them with Sequelize queries.

That means:
Replacing your MySQL Burger model with a Sequelized equivalent.
	Don't forget to edit the model and initial migration file to make the burger's devoured field carry a default value of false -- otherwise you might encounter bugs.
There's no option to include that default in the command line, so you'll need to open up your editor to make this change.
	Don't forget to sync the models!
	Edit your new config.json file to include your database configurations. Place your JawsDB details in the production property of your json file; the details of your local database go in the developer property.
	Remove your old ORM file, as well as any references to it in burgers_controller.js. Replace those references with Sequelize's ORM methods.


Make sure you install all the dependencies you need for the project
Once you have Node.js installed on your computer
Navigate to the working directory and do the following in your terminal

Before you proceed, make sure you fork the repo

> npm install

The above command will install all the dependencies you need


> npm install -g nodemon

The above command will install nodemon globally for you
nodemon will watch the files in the directory in which nodemon was started, and if any files 
change, nodemon will automatically restart your node application.


> nodemon server.js
The above command will start the server for you


> Open your browser to http://localhost:3000/

If you see "App listening on PORT 3000" in your CLI, then you're good to go :thumbsup:!


# sequelizedBurger
