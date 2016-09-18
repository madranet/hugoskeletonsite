# Hugo Skeleton Site

![](https://s3-eu-west-1.amazonaws.com/madrapublic/grafix/github/hugoskeletontheme.png)

#### ABOUT:

[Hugo](http://gohugo.io) is a fantastic Static Site Generator. However, for those new to it, it can be difficult to get your head round how it all works. One area of potential confusion [well, it was for me, when I first dived in!] is in how themes are put together.

* What are all those directories and sub-directories for?
* What goes where and why?
* How do I organise my Content?

Hugo Skeleton Site contains `skeletontheme`, which is heavily commented both via on-screen elements and within the code comments, and will help beginners get to grips with building a Hugo theme.

![](https://s3-eu-west-1.amazonaws.com/madrapublic/grafix/github/hugoskeletonthemess.jpg)


In order to keep things simple, the site produced by Hugo Skeleton Site's `skeletontheme` has a very minimalist design. It features the following er... 'features', which can sometimes confuse newcomers to Hugo:

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

*[NOTE: If you find that `hugo server --watch` isn't working properly to update the site preview [Later versions of Hugo cache files in RAM and I've found that sometimes it doesn't always pick up file changes], you can try `hugo server --watch --renderToDisk`. This will cause Hugo to write all file changes to disc, which might be a wee tiny bit slower, but will ensure all your updates are picked up in preview.]*

Have Fun!
