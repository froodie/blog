+++
author = "Sarah"
categories = ["Geekery","Music","Tech"]
date = "2015-01-11T16:19:38+00:00"
description = ""
featured = "combinefm.png"
featuredalt = "combine.fm"
featuredpath = "date"
linktitle = "niria.in| Match Audio"
title = "Match Audio – a solution to a problem you didn’t know you had"
type = "post"
tags = ["match audio","interview","jonathan","combine.fm"]
+++
_<a href="http://match.audio" target="_blank">Match Audio</a> is a new music-sharing app created by Jonathan Cremin aka <a href="http://twitter.com/kudoz" target="_blank">@kudoz</a> aka my boyfriend. I take a look at how to use match.audio and why &#8211; and chat with the dev about his plans for its future._

With more and more people turning to subscription sites to explore new music, the way we listen to and consume music has undergone another radical change. It’s easier to find and it’s easier to share. Fewer and fewer speedbumps prevent making music accessible to new audiences.

One new speedbump that is part of this new world is the variety of different music services available. The primary subscription service is probably still Spotify but Google Play Music, Beats Music, Deezer and Rdio are some of the options for users and they are all growing their user bases.

So, if you are a musician, a music blogger or a music fan and you want to share some music to people who use these services, you have to either look for links on each of the subscription services, or else have accounts on all of the primary ones. This is a lot of time that could be better spent doing, well, almost anything else. If you just want to tell your twitter followers what classic album is rustling your jimmies this week, cue an awkward &#8220;I&#8217;m not on Spotify though, I&#8217;m on Google Play Music/Deezer/Rdio&#8221; conversation.

But no more! Match.audio, the new website from the maker of [hostr.co][1], will make this part of sharing music easier. Either paste a link from your preferred services, or use the handy-dandy chrome extension, and you’ll get a page with links to <a href="http://www.spotify.com" target="_blank">Spotify</a>, <a href="http://www.deezer.com/" target="_blank">Deezer</a>, <a href="http://beatsradio.ca/" target="_blank">Beats Radio</a>, <a href="https://www.apple.com/itunes/itunes-radio/" target="_blank">iTunes Radio</a>, <a href="http://play.google.com/about/music/allaccess/" target="_blank">Google Play Music</a> and <a href="http://www.rdio.com/" target="_blank">Rdio</a>, as well as a link to YouTube.

Now you can just use one link instead of many. And you never even realised you had this problem, did you?

## But how does it work?

[<img class=" wp-image-1896 size-large aligncenter" src="/img/blog/2015/01/Results-952x1024.jpg" alt="Results" width="952" height="1024" srcset="/img/blog/2015/01/Results-952x1024.jpg 952w, /img/blog/2015/01/Results-279x300.jpg 279w, /img/blog/2015/01/Results-624x671.jpg 624w, /img/blog/2015/01/Results.jpg 1209w" sizes="(max-width: 952px) 100vw, 952px" />][2]At the moment, there are two options &#8211; copy the link from the address bar of the music you&#8217;re listening to, and paste it into the search bar on match.audio. You&#8217;ll get a page with results from the other subscription sites, as well as a YouTube link that matches as closely as possible.

[<img class="alignright size-full wp-image-1911" src="/img/blog/2015/01/Share-button1.jpg" alt="Share button" width="101" height="68" />][3]The other option for users of chrome is the chrome extension, which simplifies sharing via match.audio to a single click. This will take you to the match page for the music you&#8217;re currently listening to. You can then share via social networks so everyone will know your awesome taste in music.

I think it&#8217;s pretty cool that I don&#8217;t have to go digging for links in order to share tunes. I&#8217;d love to see the extension rolled out to other browsers, and maybe some quick how-tos for people who don&#8217;t grasp how to use it immediately. I can definitely see this becoming a great way to share what I&#8217;m listening to in a more accessible way.

## Interview with the developer

I spoke to Jonathan while he was sitting on the couch next to me, to see what inspired him to work on match.audio and what he sees happening with it in the future.

**Where did you get the idea for match.audio?**

I have a friend who I share lots of good programming music with. He uses Spotify and I use Google Music. It was a pain in the ass for him to either find the music himself on Spotify or for me to find it on his behalf when all I really wanted to do was copy a link and give it to him.

So I ended up just not sharing music a lot of the time.

**You had a little bit of time to work on it.**

This was an idea that I had around October of 2014 and then I got made redundant at the end of November 2014. Suddenly, I had some free time to work on it. So I spent a couple of days investigating all the various services to see which ones had APIs that I could use to do matching. I then spent the next couple of days after that building a minimum viable product to actually see it all working and just work through the whole thing to see how well it would actually work.

**You’ve open sourced the project**

Yeah, I open sourced it from the very beginning. I figured since I was already looking for work that it would help in my job hunt. But I was also interested in having a significant open source project that I could work on and maybe gain collaborators on.

**Have you had much interest?**

I have had one whole pull request on Github, plus I&#8217;ve had a couple of issues created reporting bugs and asking for features. One was for browser extensions and I’ve since gone on to build a chrome browser extension.

**The Chrome extension seems like a logical step. Any other browsers in the pipeline?**

There’s also an open ticket for a Firefox extension and it’s been labelled “help wanted”. I could probably build it myself but it’s not the browser I use so someone else could probably do a better job.

**What stage is it at right now?**

Basically it’s in this awkward phase of being re-factored a lot.  It was taking about ten seconds to find matches and you&#8217;d stare at a blank page while it was doing that. I&#8217;ve just pushed an update that displays matches as it finds them. That involved a lot of re-factoring and migrating database schemas and other complicated things so it took me longer than I&#8217;d hoped, but it&#8217;s totally worth it.

The next step is to figure out how to communicate effectively to people what Match.Audio does. Sometimes the automated matching isn&#8217;t great, so I want a way for people to be able to fix them manually. I also have plans for an android app but that’s further down the road.

**Who do you feel will benefit most from match.audio?**

I built match-audio to scratch my own itch. It’s great that some techy music enthusiasts have found it useful too, but I didn’t really have a target audience in mind.

**You’re coming to the end of your job hunt. Do you still think you’ll be able to invest time in match-audio to support and develop it?**

Sure, but I won’t be able to do a week-long sprint, but a lot of that exploratory work is done now and that’s the hardest part. It’s almost at the stage now where I can just hack on it on occasion without needing to invest as much into it.

**The subscription music model is a bit of a movable feast at the moment, things are changing very quickly.**

I think this is where it being open source comes in. Anyone can contribute fixes to the matching libraries and submit bug reports and all the additional effort I’d have to do myself on detecting and fixing these issues on some level can be done by other people.

**Is there scope for monetisation?**

I don’t think it makes a very good acquisition target because it doesn’t do anything to lock people in to a particular subscription service. If anything, it makes it easier to move from one to another. The only monetisation strategy I have is for using referral links for the services but I don’t expect it to cover its costs.

**Do you have anything you’d like to add?**

I highly recommend people use the free time they get from being made redundant productively like this. I’ve been told I’ve been able to skip technical interviews because of it. It has sped up the whole interview process everywhere &#8211; as well as making it easier to share music with my friends.

 [1]: http://hostr.co
 [2]: /img/blog/2015/01/Results.jpg
 [3]: /img/blog/2015/01/Share-button1.jpg