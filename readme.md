# XUProc.py
This is a simple script that concats attribute classname to the attribute name of a testcase element
*   This functionality is activated with the flag -j.
* * Example: `python xuproc.py -j file.xml`
### The script can also print test statistic
*   This functionality is activated by not providing a flag. 
* * Example: `python xuproc.py file.xml`
### Project also contains small amount of tests
*  This can be runned with command: 
* * `python -m unittest discover -s tests`  