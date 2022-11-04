#               LINUX

##              TEXT MANIPULATION

### Viewing Files

- ``cat`` *command* can be used to display files. This will stream until it comes to an end hence inconvinient and an impractical way to view files. To show part of file contents the following waya can be used:
1. __Taking the Head__: Used to view the top most of a large text file.<br/>
    ``head mynewfile.txt`` the default will display 10 line.<br/>
    ``head -100 mynewfile.txt`` this will display the first 100 lines<br/>
    ``heead -50 mynewfile.txt | head 10``  this will display lines 50-60<br/>
2. __Grabbing the Tail__: Used to view the last rows<br/>
   ``tail mynewfile.txt`` the default will display the last 10 lines<br/>
   ``tail -20 mynewfile.txt`` this will display the last 20 lines<br/>
3. __Numbering the Lines__: This is to display line numbers to make it easy to reference changes and come to the same place within file. To do this we us ``nl``, *number lines.<br/>
   ``nl mynefile.txt``

### Filtering Text with ``grep``

The ``grep`` command is used to filter the contents of a file for display. If you want to see all lines including word input in a file you do as follows
  ``cat mynewfile.txt | grep output``
