rubymotion-learn
================

# RubyMotion Book 

I have started writing a RubyMotion Book , it is hosted on gitbook

repository
https://github.com/railsfactory/rubymotion-cookbook

you can download a copy here
https://github.com/railsfactory/rubymotion-cookbook/downloads

you can submit your feedback/corrections/code here
https://github.com/railsfactory/rubymotion-cookbook/issues

Most of you are coming to this page to find all interesting RubyMotion projects

I have tried to automate the process of downloading all the new projects for you to discover on your mac. If you follow the following steps you can checkout over 40 repositories as of now, more would be added in coming days

## Clone the RubyMotion Cookbook repository

     $ git clone https://github.com/railsfactory/rubymotion-cookbook.git
     Cloning into rubymotion-cookbook...
	remote: Counting objects: 143, done.
	remote: Compressing objects: 100% (88/88), done.
	remote: Total 143 (delta 53), reused 115 (delta 28)
	Receiving objects: 100% (143/143), 1.11 MiB | 178 KiB/s, done.
	Resolving deltas: 100% (53/53), done.
	
	$ cd projects
	$ sh clone_all.sh
	....
	
It will take some time as about 100mb is downloaded directly from the repositories.

## Reading the code and Running the apps

You can read all the project code in your favorite text editor or IDE, I prefer Textmate. Running individual app is simple change into the directory and run rake and it compiles and runs.


## Running all these apps at a stretch
     
    $ # in projects folder
    $ sh run_all.sh
