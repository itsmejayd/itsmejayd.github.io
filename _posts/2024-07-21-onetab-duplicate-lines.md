---
title: "OneTab Duplicate Lines Removal Mini Project"
excerpt_separator: "<!--more-->"
categories:
  - Blog
  - Coding Project
tags:
  - Python
  - Flask
  - OneTab
  - GitHub
  - filter
  - parser
font: 14px
---

Have you ever heard of the browser extension/add-on called [OneTab](https://www.one-tab.com/)? <!--more-->It’s great. If you’re like me and you often end up with 30 tabs open while researching some random thing and you realize you should revisit this another time and you want to move on to something else for now, but you want to save your links and the order they were (simply from left to right) and don’t really want to spend 5-10 minutes bookmarking each one categorically or even 1-2 minutes to bookmark them haphazardly/figure out how to save a browser state and where you would find that again blah blah - Then this extension might be a great tool for you!

[![Screenshot of OneTab website splash page](/assets/images/onetab_splash.png)](https://www.one-tab.com/)

[![Screenshot of OneTab website splash page](/assets/images/onetab_splash.png)](https://www.one-tab.com/)
{: .full}

It sits as a button in your browser's toolbar like other extensions. When you have that moment of needing to move on but wanting to save this journey, you JUST CLICK THE BUTTON. Two seconds, done. It will save all the URLs in the order they were from left to right, in a grouping of URLs on a master list of saved URLs which show up in a browser tab when you click the extension. It will automatically save the date and time you saved them as well.

And there are some other nice features but I won’t get into them because, believe it or not, this is not an advertisement for OneTab (its free by the way, and this is from their site: "OneTab is free of charge and is not designed to make money. It was created because we badly *needed* it for our own use, and we wanted to share it with the world.")

I’m also not only writing this to just let you know about a cool tool. That’s half true. But I’d like to share a little coding project I did when I ran into a shortcoming of the extension.

First things first, to save you some time: if you don’t really care about the “story” here, let me just give you the last actionable information beyond the prospect of using OneTab: If you end up exporting/importing OneTab lists and run into issues with having many duplicates, [I made something](https://github.com/itsmejayd/filter-duplicate-lines?tab=readme-ov-file#readme-top) to help - I made a Python tool with an (optional) Flask web interface designed to remove duplicate entries from line break delimited lists while maintaining the relative position of blank lines in the input text. Originally created to clean up OneTab exports (maintaining tab groups), it can be used for any text list with similar requirements.

Flask web app:
![Screenshot of Flask web app being run in browser](/assets/images/flask_web_app.png)
{: .full}

I’ve been using OneTab for years, and I have used its import/export feature to sync up URL lists from different browsers and devices. Recently I was looking for some stuff which I knew I saved in there, but I was having no luck with command+f and I decided I would just manually scan through to find it. Then I saw the scroll bar. The list was huge. I copy-pasted it into a .txt file in VSC and it was nearly 4,000 lines! I started poking around and realized there were A LOT of duplicate links, and I mean like I saw more than 5 instances of link groups with 20-30 links duplicated. This was a result of my own lazy mismanagement, syncing exports/imports in a lazy but “safe” way which would retain everything from both.

So, out of my long 4000 line list, how many were duplicates? It turns out nearly half of them! So how to get rid of those? Well I found some online “duplicate finder” tools but they were either looking for words or other tokens which didn’t line up with what I needed. I also did a quick web search and GitHub search for a python script to remove duplicate lines from a list but what I found wasn’t working the way I wanted and didn’t deal with maintaining the format of the empty lines between sub lists of URLs (the groupings of tabs which were “OneTab-ed” together), so I just decided to make my own little solution.

Check out the [readme](https://github.com/itsmejayd/filter-duplicate-lines?tab=readme-ov-file#readme-top) and [other files](https://github.com/itsmejayd/filter-duplicate-lines) in the [GitHub repo](https://github.com/itsmejayd/filter-duplicate-lines.git) for more info, and feel free to [contact me](https://itsmejayd.github.io/about/#-contact-me) with any questions/feedback!
