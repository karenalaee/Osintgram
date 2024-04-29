What is Osintgram ? 
--------------------
Osintgram is hacking tool to have a control to some one profile or page.

how to install Osintgram.
--------------------------

You need to open terminal first, and then write this git code to download it :  $ git clone https://github.com/Datalux/Osintgram.git 

write these codes :
-------------------


         $ ls
         $ cd Osintgram/

you need to download Python3.6 and pip3

If you have Python3, you don't need to install.
-----------------------------------------------

        $ sudo apt install python3

Write your password and wait for download...

If you see this message -------> Do you want to continue? [Y/n]

ckick on "y" and then ENTER.

install pip3
------------

        $ sudo apt install python3-pip

Install requirements.
----------------------

        $ pip3 install -r requirements.txt

Create config folder
--------------------

        $ mkdir config

if your app have a config folder you don't need to create.

        $ cd config

Create a username, password and setting for your Osintgram.
------------------------------------------------------------

But just check your config folder, if you have a "setting.json" you don't need to create settings, but if you don't have, write these codes.

        $ ls

$ echo "ENTER username" > username.conf

For example:

        $ echo "best.how" > username.conf


$ echo "ENTER your password" > pw.conf

For example:

        $ echo "securitypasswordintheworld" > pw.conf


        $ echo "{}" > settings.json

        $ ls

And then come out from config folder.

        $ cd ..

Then find "main.py" in Osintgram.

        $ ls

        $ python3 main.py ENTER your target

For example:

        $ python main.py vbdhbhvfuizdb


And then write "list"

        $ list

And done, you can do your feeling with that page.
--------------------------------------------------
