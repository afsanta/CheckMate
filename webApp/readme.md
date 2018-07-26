To run this program, you will need to have a python2-compatible enviroment installed that includes pip. This could be:
* Python 2.7
* Anaconda 2.7
* Pypy 2.7

All of those have been tested. When you are ready to run this, do the following to ge tthe required python modules

```pip install -r requirements.txt```

For the pourpose of speed and efficiency, pypy might help the execution be more efficient (as it compiles the program as it is being run, rather than interpreting the script).

We also recommend setting debug to False (at the bottom of the file), as the debugging journal has a memory leak that can cause a denial of service on the server (crash/hang).

The gist will be to run the following after you have the requirements installed:

```python app.py```
