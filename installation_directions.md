#IS452 Installation Instructions

## What you'll be doing

You’ll be installing two things:


![](installation_pics/2-checkthatbox.png)

### Give it a test

### Step 1: Open your command line

Mac:
![](installation_pics/3-terminaltest.png)

Windows:
![](installation_pics/4-cmdtest.PNG)

## Install PyCharm Education edition

On the next screen you’ll want change a few things:

![](installation_pics/7-hookinganaconda.png)

### Step 3:  Make a python file and try running it
	* ![](installation_pics/8-newpythonfile.png)
2. Name is something like ‘testing’. 
	* ![](installation_pics/9-nameit.png)
3. You’ll now see an empty file in the main part of the PyCharm window.
4. Type in the following into that screen:  `print(“Hello world”)`
	* ![](installation_pics/10-makecodego.png)
5. A green “play” arrow should appear next to line 1 next to that text.  It may take a moment or two for the green button to appear.  That is completely normal and just PyCharm connecting to your anaconda installation.
6. Click that green button!
7. A new panel at the bottom should appear, with text that starts with “Hello world”. “Process finished with exit code 0” means that everything worked and is not something to worry about.  Looks weird, though, I know.
	* ![](installation_pics/11-output.png)
8. Now, let's test that you got Python 3 and not Python 2.
9. Change that code to `print "hello world"`.  PyCharm should now be putting some red on your screen to warn you that this is an error.
	* ![](installation_pics/12-errorcode.png)
10.  Try to run the code.
11.  You should see an error!
	 * ![](installation_pics/13-erroroutput.png)