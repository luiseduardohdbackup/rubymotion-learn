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




I have posted it on Hacker News, you can follow the discussion there as well
http://news.ycombinator.com/item?id=3955779



expecting more people will push their projects today to github

added a HN Post
http://news.ycombinator.com/item?id=3939347



projects tested on my 2008 mbp 

6th May 13 projects

7th May 28 projects

8th May 40 projects

9th May 50 projects RubyMotion 1.3 released

10th May 59 projects

11th May 67 projects

13th May 70 projects

RUNS
====


https://github.com/HipByte/RubyMotionSamples.git
every sample app works

third party projects which work

https://github.com/latompa/griddler.git
simple game WIP

https://github.com/seanho/Currency.git
simple currency app with conversion rate list, with a small search box on top 

https://github.com/cebartling/rubymotion-spikes.git
MapKitSpike1, a fullscreen maps app WIP

https://github.com/evanphx/distance_between.git
uses GPS possibly better tested on a device

https://github.com/caike/MotionHello.git
first app seen to use a thirdparty library(bubblewrap), small graphic animation

https://github.com/rjowens/TableViewPullRefresh.git

https://github.com/samchandra/Fonts.git

https://github.com/jamesjn/fast_imgur_emailer-motion-ios.git

https://github.com/gpasq/RubyMotionZXingExample.git

https://github.com/anydiem/cocosmotion.git 40+mb to clone it

https://github.com/siuying/RubyMotion-PocketCoreImage.git a small instagram type app with image filters using core image


https://github.com/seanlilmateus/rmdialog.git 
depends on QuickDialog, clone it into vendor https://github.com/escoz/QuickDialog.git


https://github.com/siuying/NanoStoreInMotion.git
works but you need to install cocoapods and a podfile for NanoStore to get it to work

https://github.com/aaronfeng/facebook-auth-ruby-motion-example.git
app starts and then opens web browser window taking you to  facebook login page, possibly needs a api-key somewhere, need to read the code

8th May 2012

https://github.com/hellopatrick/wave.git
settings for a possible game app

https://github.com/tvandervossen/motion-webview.git
Simple RubyMotion example project to wrap a full-screen HTML5 app into an iOS app, basically a small draw app

https://github.com/ps2/MotionGL.git
a small GLKit demo, nice animation and texture

https://github.com/rounders/RestKitTest.git
RestKit Test app, but you need to clone RestKit in vendor(32mb) as well 

https://github.com/ryw/rubymotion-experiments.git

https://github.com/thbar/learning-rubymotion.git
porting a objective C app to rubymotion WIP

https://github.com/MarkVillacampa/rubymotion-tabbar
a Tab bar implementation

https://github.com/stiller/LOLCatApp.git
magic ball variant, LOLCat app

9th May

https://github.com/tnantoka/RubyMotionApps.git
browser app works now, possibly more apps to come

https://github.com/dalacv/WordSearcher.git
WIP, uses xib/nibs in resource folder with NSStoryboard

9th may after RubyMotion 1.3 upgrade 4 additional apps work on my mac

https://github.com/locousobscura/LastTime-iOS.git

https://github.com/macfanatic/rmotion.git

https://github.com/clayallsopp/remote_model.git
another library

https://github.com/rjfranco/pragmatic-rubymotion.git

10th May

https://github.com/seanho/SimpleView.git

https://github.com/siuying/SparrowInMotion.git
a Game built on Sparrow Framework, you would need to fix the Sparrow.podsec to get it working, but feels awesome to think you can do a good game in ruby itself 

https://github.com/spllr/TwitterApp.git
works fine, have posted on my twitter account

https://github.com/rjowens/SplitViewControllerExample.git
SplitViewController in rubymotion, targeted at iPad

https://github.com/eatcpcks/rubymotion-bars.git
I Need Booze, app runs but when getting location crashes

https://github.com/sakisakira/IBOutletActionRubyMotion.git
A sample project of IBAction and IBOutlet from .xib to RubyMotion code

https://github.com/nlehuen/MotionCalc.git
An RPN calculator for iPhone implemented using RubyMotion

https://github.com/Watson1978/RubyMotion-Benchmark.git
A Benchmark library for RubyMotion

11th May

https://github.com/mdks/rm-redgreen.git
ansi coloring for console output

https://github.com/makzan/RubyMotion-USD-to-MOP-Convertor.git
simple Currency converter

https://github.com/matsimitsu/itrakt_motion.git
one of the more polished applications, tabs, table view, remote data and images loaded. would be awesome if there was indicator, WIP

https://github.com/makzan/rubymotion-pan-view-example.git
Pan view


13th May
https://github.com/timidri/RandomCatz.git
loads random cat pitures from server, can be used for other purposes

https://github.com/mjmsmith/rubymotion-times.git
a RSS reader

https://github.com/andrew/lightning.git
lightning talk timer, one app which you can use in real life immediately awesom

FAILS
=====
getting errors DTiPhoneSimulatorErrorDomain
 
last tested on 9th May

https://github.com/siuying/RubyMotionCocos2d-Static.git
Cocos2d demo app, builds but when opening app crashes

https://github.com/seanho/SimpleView.git

https://github.com/siuying/hpple-motion.git
An XML/HTML parser for RubyMotion, with nokogiri style interface., fails for now



Tools and Libraries
===================

textmate bundle
https://github.com/libin/RubyMotion.tmbundle

https://github.com/kattrali/redcar-rubymotion.git
Basic RubyMotion workflow support in Redcar Editor

https://github.com/mattetti/BubbleWrap.git 
library to simplify development

https://github.com/adelevie/ParseModel.git
An Active Record pattern for your Parse models on RubyMotion.


https://github.com/matterker/testtests.git 
a BDD framework, but default rake task fails for me


https://github.com/AaronH/RubyMotion-UserSettings.git
A convenience wrapper to allow RubyMotion apps easy access to reading, writing, and persisting values via NSUserDefaults

https://github.com/mattgreen/spry.git
another framework WIP

https://github.com/jeremyruppel/lotion.git
it is about building helpers for rubymotion, potential drawback it is attempting to build a rubygem and it uses modules both a strict no-no in rubymotion world
maybe as a standalone code generator it can work


https://github.com/clarkware/Commotion.git
CoreData wrapper WIP, but it works 

https://github.com/malkomalko/motion-layouts.git
