in order to have username and email configured globally by git, do this (on your termninal, obviously):

``git config --global user.name "your name"``

and

``git config --global user.email "my_name@example.com"``

you might also want to have git autocorrect incase you misspell commmands:

``git config --global help.autocorrect 20``

the ``20`` means the the autocorrect will run after ``2`` seconds. you're free to choose a number you're comfortabke with.
