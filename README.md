# Speed File Library #

## What is this? ##
The module allows you to work with files in just one line of code, without the need to manually open and close the file each time

## Quick Guide ##
The module is based on the following structure:

    
    f = open('data.txt')
    data = f.readlines()
    f.close()
    
Which Python provides by standard.


----------


### Using ###


Using the library is as simple and convenient as possible:

Let's import it first:
First, import everything from the library (use the `from `...` import *` construct).

Examples of all operations:

Writing the contents of an entire file to a variable using the `read()` function:

    temp = File(path='test.txt').read()


Writing the contents of an entire file to a variable line by line using the `readlines()` function:

    temp = File(path='test.txt').readlines()


Write only the first line from a file using the `readline()` function:

    temp = File(path='test.txt').readline()


Writing data from a variable to a file using write() (overwriting or creating a file):

    temp = "Test data"
    File(path='test.txt', data=temp).write()
    

Adding data from a variable to a file using write() (or creating a file):

    temp = "Test data"
    File(path='test.txt', data=temp).add()


----------


## Developer ##
My site: [link](https://y-a-r-i-k.github.io/) 
