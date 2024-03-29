# project_2
# Item Catalog Project
An Udacity Full Stack Web Developer II Nanodegree project developed by Subhadeep Dey.

## About
This application provides a list of items within a variety of categories as well as provide a user registration and authentication system. Registered users will have the ability to post, edit, and delete their own items.

### Features
- Proper authentication and authorisation check.
- Full CRUD support using SQLAlchemy and Flask.
- JSON endpoints.
- Implements oAuth using Google Sign-in API

## The modules required in this file
Flask==0.12.0  
Jinja2==2.8.1  
gunicorn==19.6.0

So now run:

   ```bash
   pip  install  -r  requirements.txt
   ```
   regardless of any missing dependency, they will be able to smoothly install your app.

To learn more about pip and requirements.txt, also visit this link.

https://pip.readthedocs.io/en/1.1/requirements.html

## Steps to run this project

1. Download and install [Vagrant](https://www.vagrantup.com/downloads.html).

2. Download and install [VirtualBox](https://www.virtualbox.org/wiki/Downloads).

3. Clone or download the Vagrant VM configuration file from [here](https://github.com/udacity/fullstack-nanodegree-vm).

4. Open the above directory and navigate to the `vagrant/` sub-directory.

5. Open terminal, and type

   ```bash
   vagrant up
   ```

   This will cause Vagrant to download the Ubuntu operating system and install it. This may take quite a while depending on how fast your Internet connection is.

6. After the above command succeeds, connect to the newly created VM:

   ```bash
   vagrant ssh
   ```

8. Type `cd /vagrant/` to navigate to the shared repository.

9. Download or clone this repository, and navigate to it.

11. Install or upgrade Flask:
    ```bash
    sudo python -m pip install --upgrade flask
    ```
12. Set up the database:
    ```bash
    python database_setup.py
    ```
13. Insert dummy values. **If you don't run this, the application might not run.**
    ```bash
    python itemsofmenu.py
    ```
14. Run this application:
    ```bash
    python app.py
    ```
15. Open `http://localhost:5000/` in your favourite Web browser, and enjoy.
