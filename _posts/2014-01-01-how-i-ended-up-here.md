---
layout: post
title:  "How I Ended Up Here..."
date:   2014-01-01 21:00:00
categories: github jekyll blog
---

... of course, I *did* want to collect/organize my thoughts/knowledge and transform the blogosphere/cyberspace/[megastructure][blame] with my consciousness - all that jazz, but how did I end up choosing [GitHub][github] for this venture? This is what essentially transpired:

>\> Knowledge in cybersphere good, but not well [organzized][taxi-driver]  
>\> [Me start blogging (again) to transform the cybersphere!][birdman]  
>\> I already haz [Blogger][blogger] space, once re-init'ed for sanity; Use again?  
>\> What 'dis [wordpress][wordpress] buzz? Compare before start  
>\>\> *Blogger is [Google][google]. Google do whatever with it whenever. Too risky...*  
>\>\> *Wordpress is engine. Self-host or [wordpress.com][wordpress]*  
>\> I can haz [LAMP][lamp] self-host?  
>\>\> *Bad idea. Bandwidth/traffic/hax0rz headache*  
>\> Sigh... [wordpress.com][wordpress] only choice left...  
>\> I can haz vim? Whaddabout version control? I can haz git?  
>\> Wait... Is there [GitHub][github] based blog? I already haz account...  
>\> Profit! [GitHub Pages][github-pages]. Wordpress? Not a chance no more...  
>\> I can haz [vim][ed]! I can haz blog like code!  
>\> Setup using [Jekyll][jekyll]... Hmmm  
>\> On [Arch][archlinux]:
{% highlight bash %}
$ export PATH="$(ruby -e 'puts Gem.user_dir')/bin:$PATH"
$ # Insert PATH="$(ruby -e 'puts Gem.user_dir')/bin:$PATH" into .bashrc for eternity
$ gem install jekyll
$ mkdir blog
$ git clone https://github.com/manzdagratiano/manzdagratiano.github.io
$ git checkout -b blog
$ jekyll new blog
{% endhighlight %}
>\> Config much? They haz [Jekyll bootstrap][jekyll-boot] and [Octopress][octopress]  
>\> Naah... Too much abstraction. Me barebones fan  
>\> Steal some config from [Jekyll][jekyll]. Looks good. Let's edit...  
>\> ... editing...  
>\> `jekyll serve` plusgood.
{% highlight bash %}
$ git add .
$ git commit -m "Genesis"
$ git checkout master
$ git merge blog
$ git push origin master
{% endhighlight %}

Profit!!!

[archlinux]:    https://www.archlinux.org
[birdman]:      https://en.wikipedia.org/wiki/Harvey_Birdman
[blame]:        https://en.wikipedia.org/wiki/Blame!
[blogger]:      https://manzdagratiano.blogspot.com
[ed]:           https://www.gnu.org/fun/jokes/ed-msg.html
[git]:          https://en.wikipedia.org/wiki/Git_%28software%29
[github]:       https://github.com
[github-pages]: https://pages.github.com
[google]:       https://google.com
[jekyll]:       http://jekyllrb.com
[jekyll-boot]:  http://jekyllbootstrap.com
[lamp]:         https://en.wikipedia.org/wiki/LAMP_%28software_bundle%29
[octopress]:    http://octopress.org
[taxi-driver]:  http://www.imdb.com/title/tt0075314/?ref_=fn_al_tt_1
[wordpress]:    https://wordpress.com
