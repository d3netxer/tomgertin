---
defaults:
  # _posts
  - scope:
      path: ""
      type: posts
    values:
      layout: single
      author_profile: true
      read_time: true
      comments: true
      share: true
      related: true
id: 402
title: Designing Accessible Maps
date: 2014-02-17T19:28:22+00:00
author: admin
#layout: post
guid: http://www.tomgertin.com/?p=402
#permalink: /geoblog/designing-accessible-maps/
categories:
  - GeoBlog
---
When making maps or any type of graphic I never thought of how the product would be perceived to people who have color vision impairment. I didn’t know how big of an issue it was. After reading Benhard and Nathaniel’s _[Color Design for the Color Vision Impaired](http://colororacle.org/design.html)_ paper I now know it affects a significant amount of people, especially men. Therefore I agree it is preferable to create maps that can be understood by people who have color vision impairment.

I think that this type of design consideration will not always be followed because of the increased overhead it requires. Maybe some designers will not follow these best practices if they are not enforced. Other reasons for designers not making maps for the vision impaired include ignorance of the situation or some designers will not want to sacrifice their original design to cater to people who have color vision impairment.

I believe that the best remedy would be to cure people of their color-blindness by injecting trillions of copies of a genetically engineered virus into their retina. [DeWeerdt&#8217;s Seeing Red](http://sarahdeweerdt.blogspot.com/2010/03/seeing-red.html) paper explained how this has been tested on squirrel monkeys and enabled their cone cells to produce red-sensitive pigment. Why should us as cartographers alter our maps just accommodate less than 10 percent of the population? Of course I’m not being serious. Fortunately there are guidelines out there on how to make your maps better for those who have color vision impairment.

For every type of user, spectral color schemas, otherwise known as rainbow color schemas are not recommended for quantitative or ordered data. This is because there is no inherent magnitude message in a rainbow. In _[Spectral Schemes: Controversial Color Use on Maps](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&ved=0CCYQFjAA&url=http%3A%2F%2Fwww.personal.psu.edu%2Fcab38%2FPub_scans%2FBrewer_1997_Spectral_CaGIS.pdf&ei=3cMCU6nRAqT00QHX_YGgAg&usg=AFQjCNGu72JYsV7qcRqWkgAbQNIiBGrRfQ&sig2=pRVjCA_TiFG6JYEsWCOCWA&bvm=bv.61535280,d.dmQ)_, Brewer believes that spectral color schemes should be encouraged for diverging quantitative data. I agree somewhat, more so if a diverging spectral scheme is matched with diverging data. I think spectral schemes have an advantage of the amount of different hues they use, I think that this increased ‘spectral resolution’ can bring out details in the dataset. The disadvantage is that I don’t have any association of magnitude between green and blue. Reading Brewer’s paper I have come to appreciate the diverging two-tone spectral scheme:

[<img class="alignnone size-medium wp-image-403" title="diverging_two_tone" src="{{ site.baseurl }}/img/2014/02/diverging_two_tone-300x27.png" alt="" width="300" height="27" />]({{ site.baseurl }}/img/2014/02/diverging_two_tone.png)

Brewer gives some recommendations for people who have color vision impairment. Skipping over yellow-greens should accommodate map-readers with red-green visual impairment. I think this is a fairly straightforward rule I can remember. I also stumbled upon [Colorbrewer2.org](http://colorbrewer2.org/), a site that helps you pick appropriate color schemes. Copyrighted by Cynthia Brewer, Mark Harrower and The Pennsylvania State University. Clever play on words Cynthia! In the Bernhard paper a piece of software called [Color Oracle](http://colororacle.org/index.html) is mentioned. I installed this and think it is great. With just one button click you can quickly see how people with Deuteranopia, Protanopia, or Tritanopia see. This can be a very useful tool for cartographers creating barrier-free maps!
