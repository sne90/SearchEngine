Project Details: 
**********************************
 
Step 1: Please import the project to your Eclipse workspace from my GitHub respository.

Here are steps how to do so :- 

Go to Windows->Preferences->Version Control and choose GIT

Clone https://github.com/sne90/SearchEngine.git to your local repository and  import the project into your workspace.

*********************************************************

Step 2: How to Test 

1.index.buildIndex() method inside the InvertedIndex class contains the file location of my local machine.
PLease change the file location to your local machine.

example : "C:\\Users\\iyerrsne\\Desktop\\testfile1.txt"   => "YourLocalpath\\testfile1.txt"


testfile1.txt,textfile2.txt,textfile3.txt are the input test files.
location: https://github.com/sne90/SearchEngine

*********************************************************

Git commands used: 

$ git clone https://github.com/sne90/SearchEngine.git

iyerrsne@WL359159 MINGW64 ~/Documents/SourceCode/SearchEngine/SearchEngineAPI (master)
$ git add .

iyerrsne@WL359159 MINGW64 ~/Documents/SourceCode/SearchEngine/SearchEngineAPI (master)
$ git status

$ git commit -m "Added Input Text files used for testing "


$ git remote set-url origin https://sneh90@github.com/sne90/SearchEngine.git/

iyerrsne@WL359159 MINGW64 ~/Documents/SourceCode/SearchEngine/SearchEngineAPI (master)
$ git push origin master

Note:  When trying to do a Git PUSH received error "fatal 403  declined access to github "  
	Solution : git remote set-url origin https://sneh90@github.com/sne90/SearchEngine.git/		

***********************************************************
Java Environment Details :

JDK 11 used 

C:\Users\iyerrsne>java -version
java version "11.0.10" 2021-01-19 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.10+8-LTS-162)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.10+8-LTS-162, mixed mode)

Eclipse IDE for Java Developers with Version : 2021-09 (4.21.0)

***************************************************

Findwise_SearchEngine.jar can be found in the Github 
location : https://github.com/sne90/SearchEngine/tree/master/SearchEngineAPI










