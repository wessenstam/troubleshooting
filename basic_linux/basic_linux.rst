.. Adding labels to the beginning of your lab is helpful for linking to the lab from other pages
.. _basic_linux:

--------------------
Basic Linux Commands
--------------------

Overview
--------

As our Nutanix CVM is running within a CentOS O/S, we can use the default Linux bash commands to look, search and manipulate files. In this module you will learn the most common and handy commands to use.

- grep
- ls
- cat
- tr
- cut
- sar
- ifconfig
- less
- more
- find
- mv
- rm
- ps
- top
- tail
- df
- ssh

As this is just the list some usefull commands, a bigger list can be found at `this webpage <https://centoshelp.org/resources/commands/linux-system-commands/>`_ or just search for **bash commands**.

Commands
--------

grep
....

The ``grep`` command can be used to:

- filter information from a file or command from its standard output using the **|** (pipe) sign
- search for a specific word in file(s)

**Lab 1**

Lab 1 is about filtering information using the output of a file. For this we are going to use the ``cat`` command.

- Login to the CVM using the IP address you have been assigned as user **nutanix**. The coressponding password is **nutanix/4u**.
  #. After the login was succesful type the following commands to go to the logs directory of the CVM.
    - ``cd /home/nutanix/data/logs`` instead of typing all, use the **tab key** to have the path automatically filled.
  #. run the following command to see which files are available ``ls -al`` rm *.


ls
......

This ``ls`` command is the alterative to the ``dir`` command we might know form **DOS**. The command is to show (list) the files that are available in a specfic directory.

cat
...


tr
...



cut
...


sar
....


ifconfig
........


less
....


more
....


find
....


mv
...


rm
...

ps
...


top
...


tail
....


df
...


ssh
...



------------------

Takeaways
---------

- Here is where we summarize any key takeaways from the module
- Such as how a Nutanix feature used in the lab delivers value
- Or highlighting a differentiator
