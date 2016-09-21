## Project: Item Catalog - Alessandro Giacomini
## Description
-----------------------------------
This application provides a list of holiday trips within a variety of categories and provides a user registration and authentication system. Registered users, anyone with a Google or Facebook account, will have the ability to post, edit and delete their own trip posts.

## How to Run
------------------

Please ensure you have Python, Vagrant and VirtualBox installed. This project uses a pre-congfigured Vagrant virtual machine which has the [Flask](http://flask.pocoo.org/) server installed.

```bash
$ cd vagrant
$ vagrant up
$ vagrant ssh
```

Within the virtual machine change in to the shared directory by running

```bash
$ python catalog.py
```

Then navigate to localhost:5000 on your favorite browser.