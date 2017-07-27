# Item Catalog Web Application
Item-catalog Udacity FSND project


## Project Overview
An application that provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit and delete their own items.

## Why This Project?
Modern web applications perform a variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data. In this project, you’ll combine your knowledge of building dynamic websites with persistent data storage to create a web application that provides a compelling service to your users.

## What Will I Learn?
You will learn how to develop a RESTful web application using the Python framework Flask along with implementing third-party OAuth authentication. You will then learn when to properly use the various HTTP methods available to you and how these methods relate to CRUD (create, read, update and delete) operations.

## How Does This Help My Career?
* Efficiently interacting with data is the backbone upon which performant web applications are built
* Properly implementing authentication mechanisms and appropriately mapping HTTP methods to CRUD operations are core features of a properly secured web application


## Installation and Requirements :

1.Install Vagrant & VirtualBox <br>
2.Clone the Udacity Vagrantfile <br>
3.Clone this repo in the vagrant dir <br>
4.Launch the Vagrant VM by vagrant up command <br>
5.Log into Vagrant VM vagrant ssh command <br>
6.Navigate to cd/vagrant as instructed in terminal <br>
7.Setup application's database by running database_setup.py <br>
8.Insert fake data items by running fakeItems.py .This would create a database named catalog.db <br>
9.Run the application project.py <br>

Access the application locally using http://localhost:8080


## Using Google Sign In
To get the Google login working there are a few additional steps:

1.Go to Google Dev Console <br>
2.Sign up or Login <br>
3.Go to Credentials <br>
4.Select Create Crendentials > OAuth Client ID <br>
5.Select Web application <br>
6.Enter name 'My Project' <br>
7.Authorized JavaScript origins = 'http://localhost:8080' <br>
8.Save Changes <br>
9.Copy the Client ID and paste it into the data-clientid in login.html present in the templates folder <br>
10.On the Dev Console Select Download JSON <br>
11.Rename JSON file to client_secrets.json 
12.Place JSON file in your directory where project.py is present
Run application using python /item-catalog/app.py
