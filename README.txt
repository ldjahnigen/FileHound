FileHound

this is a simple Java library containing three file handling functions:

fileRead()
fileWrite()
fileAppend()

to start, first create a filehound object

FileHound filehound = new FileHound();

then, use the methods with the following syntaxes:

filehound.fileRead("README.txt");
filehound.fileWrite("hello", "README.txt");
filehound.fileAppend("hello", "README.txt");
