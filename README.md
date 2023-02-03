# practical-machine-learning-2023


# some basic linux commands

`ls` - show the contents of the current directory

`pwd` - show the current path (i.e. where you are in the file structure)

`cd <directory_name>` - change directory into `<directory_name>`

`cd ..` - change directory up one level

`cd` - change into your home directory

`mkdir <directory_name>` - make a directory called `<directory_name>`

Also remember you can use the up arrow to see previous commands entered, and the tab key to do tab completion on commands you start typing.

# how to run on linux

The first time you want to run you need to get the code from github.  You can start by making and changing directory into the area you want to work in, and then do the following:

On this page click on the green "code" button to get the repository address then do:

`git clone https://github.com/abbeywaldron/practical-machine-learning-2023.git`

Now you can change into the directory and look around to check you successfully got the files:

`cd practical-machine-learning-2023`

`ls`

Remember you can use tab completion!  Now we can launch the TensorFlow environment and Jupyter:

`source activate tf2.11`

`jupyter notebook`

After you have checked out the code you only need to run the last two commands, so if you come back tomorrow and want to work on the same thing, just run the last two commands.