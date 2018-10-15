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
id: 270
title: Hyperspectral Imaging
date: 2010-12-26T11:33:12+00:00
author: admin
#layout: post
guid: http://www.tomgertin.com/?p=270
#permalink: /uncategorized/hyperspectral-imaging/
---
I feel much more relaxed now that my semester is over. Classes and work have been keeping me very busy in the fall. I thought I would write about my final paper in one of my classes, Hyperspectral Imaging.

<span style="text-decoration: underline;">Hyperspectral Concept</span>

This is basically straight out of one of the questions on my midterms…(I’m lazy)

When we use a regular color composite image it is made up of three wavelengths: red, green, and blue. Looking at the Electromagnetic Spectrum we know that there are many other wavelengths that we can detect. The range from which hyperspectral sensors can detect range from .4 to 14 micrometers, this includes the near, mid, and long wave infrared parts of the spectrum. In comparison, humans can only detect light from about .4 to .7 micrometers.

A hyperspectral image cube has many bands; it is common to have over 200 bands. The fact that the bands are narrow and contiguous enables users to extract a spectral signature from a certain pixel and use it to match other pixels. Hyperspectral imagery is useful for finding objects and detecting materials in a scene.

In the beginning of the semester around the time I received the final paper assignment, I found out that the department actually has a hyperspectral ground sensor. I thought it would be a great idea if I could combine the two, I’m glad it ended up working out.

<span style="text-decoration: underline;">Paper</span>

The scanner was a SOC 700 by Surface Optics Corporation. The system basically came into parts, the scanner and a processing computer. The images were 640 X 640, 120 bands, and utilized the spectral band from 0.43 – 0.9 microns. It was easy to initially set-up the system and start taking scans. The tricky part was saving the images to a format where I could open them in ENVI, the image processing software we used in class. Fortunately, someone at Surface Optic was able to help explain the settings to me as well as walk me through the steps in converting the radiance cube into reflectance. This was done two days before the paper was due, so luckily I was able to do the last scans in time and finish my paper!

<div id="attachment_271" style="width: 234px" class="wp-caption alignnone">
  <a href="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/system.png"><img class="size-full wp-image-271" title="SOC 700" src="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/system.png" alt="SOC 700" width="224" height="138" /></a>
  
  <p class="wp-caption-text">
    SOC 700
  </p>
</div>

<div id="attachment_272" style="width: 249px" class="wp-caption alignnone">
  <a href="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/cars.png"><img class="size-full wp-image-272" title="cars" src="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/cars.png" alt="cars" width="239" height="138" /></a>
  
  <p class="wp-caption-text">
    cars
  </p>
</div>

I took scans all over my front yard, mainly of cars. The white sheet taped to the cars is acting as the calibration panel. After I obtained the samples I was able to compare them to an above ground dataset I had. The results were mixed, one of the best results I had was using the asphalt spectral signature. Below is the result of using Spectral Angle Mapper:

<div id="attachment_273" style="width: 165px" class="wp-caption alignnone">
  <a href="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/asphalt.png"><img class="size-full wp-image-273" title="asphalt detection" src="http://www.tomgertin.com/blog/wp-content/uploads/2010/12/asphalt.png" alt="asphalt detection" width="155" height="294" /></a>
  
  <p class="wp-caption-text">
    asphalt detection
  </p>
</div>

As you can see from the bright spots in the image, it did a great job of detecting the roads and parking lots in the scene.

<div class="addtoany_share_save_container addtoany_content_bottom">
  <div class="a2a_kit a2a_kit_size_32 addtoany_list a2a_target" id="wpa2a_57">
    <a class="a2a_dd addtoany_share_save" href="https://www.addtoany.com/share_save"><img src="http://www.tomgertin.com/blog/wp-content/plugins/add-to-any/share_save_171_16.png" width="171" height="16" alt="Share" /></a>
  </div>
</div>