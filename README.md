# Hugo Skeleton Site

#### ABOUT:

[Hugo](http://gohugo.io) is a fantastic Static Site Generator. However, for those new to it, it can be difficult to get your head round how it all works. One area of potential confusion [well, it was for me, when I first dived in!] is in how themes are put together. 

* What are all those directories and sub-directories for?
* What goes where and why?

This repo is intended to give complete newbies to Hugo an absolute bare-bones theme to tinker with. ~~And when I say "bare-bones" I mean "bare-bones".  There is only the minimum needed to get the job done. That means no styling, no 'responsive design', no 'mobile-friendliness', no 'boot-strapping' just plain old *"Hey! –the 1990s called. They want their design back!"* ugliness.~~

~~The thinking behind this is that there's nothing to distract you from what's relevant to the theme; everything in there is doing *\<something\>*. On the plus side, everything is commented to within an inch of its life and all pages will display some info about what template files are being used to produce them.~~

**UPDATE:** Out of a desire to keep your keyboards free from vomit, I've now added some basic styling to the site. So whilst it's still a 'Plain Jane', it's less likely to make you want to sandpaper your retinas to get rid of the horror they have beheld.

The site produced by Hugo Skeleton Site's ```skeletontheme``` features the following:

* A custom homepage
* Static page
* Posts organised under a separate 'Blog' section
* Dedicated 'Tags' section pages

#### DISCLAIMER:

As stated above, the primary purpose of Hugo Skeleton Site's ```skeletontheme``` is to let you pick apart a very very basic theme and see what makes it tick. There are alternative ways [sometimes better ways] to do some of the things this theme does. However, I've erred on the side of trying to keep the structure and the source code as simple and easy to decipher as possible. So please bear that in mind.

#### USAGE:

I'll assume that, if you've come here, you've already got Hugo installed. So all you need to do is:

* ```cd <your working dir>```
* ```git clone git@github.com:madranet/hugoskeletonsite.git```
* ```cd hugoskeletonsite```
* ```hugo server --watch```

Then view the generated site at ```http://localhost:1313```
The ```--watch``` flag on the ```hugo``` command will automatically re-generate the site as you tinker and save files. So you can have fun breaking stuff and putting it back together again. I also recommend you open your browser's 'Dev Tools' pane and inspect the generated HTML too. There will be plenty of ```<-- comments -->``` in there which will show you were various template fragments are being loaded and where loops are happening.

Have Fun!
