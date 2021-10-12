Project Details: 
**********************************
 
Step 1: Please import the project to your workspace from my GitHub respository.

Here are steps how to do so :- 

Go to Windows->Preferences->Version Control and choose GIT

Clone https://github.com/sne90/SearchEngine.git to your local repository and  import the project into your workspace.

*********************************************************

Step 2: How to Test 

1.index.buildIndex() method inside the InvertedIndex class contains the file location of my local machine.
PLease change the file location to your local machine.

example : "C:\\Users\\iyerrsne\\Desktop\\testfile1.txt"   => "<Your Local path>\\testfile1.txt"


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

Findwise_SearchEngine.jar can be found in the Github 
location : https://github.com/sne90/SearchEngine/tree/master/SearchEngineAPI












