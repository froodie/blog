---
title: 'Moving to Static '
date: 2019-06-08T17:37:46.153Z
---
![hugo & netlify](/site/static/img/blog/hugonetlify.jpg)

I don’t blog very often. Calling me a sporadic blogger would be overly generous. I’ve probably used Facebook for much of my longer-length bits and pieces over the past few years. On Thursday I’d a day off work and wrote a diatribe about the scourge of “like and share” scams on Facebook. I posted it to Facebook, where it got surprisingly little traction (maybe because I was being patronising, maybe because people only share nonsense on Facebook, not anything useful).

I realised not long after posting that it was actually more of a blog post than a Facebook post, and I decided to add it to my very neglected blog at niria.in. This was a WordPress installation which I had last posted to (and probably updated) back in 2017. So not only was it lonely and sad, it was full of vulnerabilities. I tried to log in and promptly crashed the whole site.

When my (extremely talented software engineer) boyfriend arrived home, I asked him for some help. He suggested it might be time to try a different, more secure route, namely using a static site generator which I could couple with free hosting, thereby saving myself the worry about keeping my WordPress instance and assorted plugins updated \*and\* the cost of hosting the site, hooray for Netlify’s free plan!

We decided on using Hugo because it seemed to be quick & easy, so I signed up to Netlify, dusted off my almost totally unused GitHub account and we were off.

\((< tweet 1137410576131530752 >}}

Our first step was extracting my old WordPress blog posts - most of which had actually originally come from LiveJournal. There’s a handy WordPress plugin that exports your posts in Hugo-friendly format which we were able to install via command line from cPanel (remember, I couldn't actually get into the WordPress backend at this point).

As many of the old LJ entries were private posts, our next job was moving all of the private posts to a separate directory. <code>grep</code> came in very handy at this point and we were left with genuine posts.

I spent a lot of time here getting used to using the command line again, playing with the config files and learning how to actually use GitHub. I hadn’t realised before that Windows Subsystem for Linux was a thing either, so saying Hi! to Ubuntu again was nice too :)

I definitely was glad to have [Jonathan](https://crem.in/) around to help when I got stuck with anything - he was able to guide me through installing my first try at a theme and then help when I had some difficulties getting another version of the theme working instead. He also did some magic to make it easy for me to refresh the css any time I fancy a change (this bit hadn’t been working in the theme template that I ended up going for).

I’ve still got some changes to make and probably things to tidy up with this new installation, but so far I’m very much enjoying playing with it and learning how it all works. You never know, I might even get around to adding some posts to this fourth version of having a personal blog (anyone remember Diaryland?)
