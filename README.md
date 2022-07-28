<h1> What Is Contact Mangement System? <h1>
In ganagrel a contact management system is like your phone book, so a contact management system is a system where you can store your all contact information, you can edit and delete the contact number also you can search contact information. That means it is a way to manage your contact information.


![menu](https://user-images.githubusercontent.com/95553859/181513232-615afe37-0dff-435f-b11e-4afcd11b61bb.jpg)

Use Of Contact Management System: 

The main use of contact management program is organizing your contact information. For example you can

Store all of your clients contact information.
You can send them a quick response and get beack to your communication history.
You can set automated remainder.
You can set schedule.

Language Used: C

How Programe is createde:

If you take a closer look to our project you will see a menu appearing at the beginning and from there you can easily choose what you want to do. Also the menu keeps appearing until we exit the program. We have used While Loop and Swich case to creating this features.
You will see that if we restart the program after exit the program completely the previously stored data are still there. We have created this freatues by file handling in c programing language. We have store the data in the text file, so you have to have an idea about how to create or delete a file, how to write something in that file, how to rename the file etc.
You may also notice that in some parts of the project some lines are being printed very nicely and its feel like automatically typing. We have created this features using Sleep method of c programing language.
We have divided all of our functionality in different different function so that we can manage our project easily. So you should have an knowledge about function in c programming like how can to declare function in c programming, how to call and return function in c programming, how can we pass string and return string in c programming etc.
Besides that the For Loop or Loop, if-else, variable all these things are there.

What can be done by this project:

What Can Be Done With Contact Management Project
You may already know what can be done in this project, so here is a list so that you can understand in a moment what can be done in this contact management system.

You can store a new contact number.
You can show all the contact numbers together.
You can search a contact number from many numbers.
You can edit the contact number.
You can delete a contact number.
You can delete all the contact numbers at once.

How Does The Manu Works:

To create menus, by normally printing a string in a formatted way and then we have call the function in a whale loop so that the menu show repeatedly until user exit the program.

How To Store A New Contact Number?
Storing a contact number means storing its name, phone number and its email address. So we will take input all these things from the user as strings and save each thing in the form of a new line in our text file.
While taking input, we will keep in mind some validation rules like

How to store information:

A name should be unique and cannot be more than twenty characters long.
A phone number should be unique cannot be more than twenty characters log.
A Email address should be unique and must be a maximum of 30 characters.


![store](https://user-images.githubusercontent.com/95553859/181515890-ba3ae227-ae78-4073-9093-62a296bd806e.png)

How To Show All The Numbers Together:
It is very easy to show all the contact numbers. We will read our text file where we stored our contact information. We will print all line until the file reading is finished. We should know that a contact number is consist by three number that means 1st line is Name, 2nd line is Phone, and 3rd line is Email address so at the time of printing the line we will follow this arrangement.
In our project we have very nicely shown all the numbers one by one in a table. To do this we have done formatted our string which means we have added some space at the end of each string. For example, if a user inputs a name of eight characters, then we add twelve more spaces to this name and make it twenty. Similarly, we have done this for phone number and email address so that everything is always the same length.

![Show All](https://user-images.githubusercontent.com/95553859/181516014-68243d3f-4587-4b28-93e5-ebe052ca77cb.png)


Search A Contact Number Out Of Many Contact Numbers:
To find out a contact number from many contact numbers, we will search by name. Here, this search is very easy. If you understand how we show all number from our text file then you will understand this easily. We will take out all the lines one by one from our text file. And if the frist line of a contact matches with the given name to search, then we can understand that there is a phone number or a contact number. And we will show those three lines to the user.

How To Edit A Contact Number:
Editing a contact number is a bit technical, if we look closely then we will understand that our purpose is to give the user a chance to input three new lines and keep remain same all other lines.
In the same way, like searching for a contact, the user will first give a name of a contact number he wants to edit. And we will continue to search line by line in our file one by one. Whenever a line matches the contact name given by the user, we will ask the user to renew that line and the next two lines and all other lines will remain the same.
Now we will use a little ingenuity to put all these things together. We will copy everything from our existing file to a temporary file with our three new lines.That means our temporary file will contain all the previous ones and will have that updated contact number. Now all we have to do is delete the existing file and rename the temporary file to the existing file name so that temporary file will become the existing file.
Another nice system we've seen here is if user donot wan to edit a line he can easly skip the line.
One thing to keep in mind is that we will save each item as a new line, such as the name in one line, the phone number in second line, and the email address will be stored in thired line.


How Can![Edit](https://user-images.githubusercontent.com/95553859/181516092-f67ffb28-33c9-4e83-adff-67de6bd80c3d.png)


I Delete A Contact Number:
If you understand how to edit contacts, you can easily understand how to delete contacts. In our editing the contact featu we moved everything from our previous file to a temporary file and took three new lines. Now for deleting a contact number, we will do the same thing. We will bring everything from our existing file to the temporary file except for three lines. And finally we will delete our existing file then rename the temporary file as Existing file.


How To Delete All Contact Numbers At Once:
It is very easy to delete all the contact contact numbers at once. By deleting the file in which we have saved all our contact numbers you can delete all contact number at once.

![deleteall](https://user-images.githubusercontent.com/95553859/181516215-fe87f2b8-364b-4df9-bacc-03b4d6fcf435.png)
