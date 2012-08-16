== First Application

This Application contains two data model Users and Microposts.

User			Action	Purpose
/users			index	page to list all users
/users/1		show	page to show user with id 1
/users/new		new		page to make a new user
/users/1/edit	edit	page to edit user with id 1

HTTP request	URI				Action		Purpose
GET				/users			index		page to list all users
GET				/users/1		show		page to show user with id 1
GET				/users/new		new			page to make a new user
POST			/users			create		create a new user
GET				/users/1/edit	edit		page to edit user with id 1
PUT				/users/1		update		update user with id 1
DELETE			/users/1		destroy		delete user with id 1


Micropost
HTTP request	URI					Action	Purpose
GET				/microposts			index	page to list all microposts
GET				/microposts/1		show	page to show micropost with id 1
GET				/microposts/new		new		page to make a new micropost
POST			/microposts			create	create a new micropost
GET				/microposts/1/edit	edit	page to edit micropost with id 1
PUT				/microposts/1		update	update micropost with id 1
DELETE			/microposts/1		destroy	delete micropost with id 1
