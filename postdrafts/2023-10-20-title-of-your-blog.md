---
layout: post
title: "TITLE"
author: "AUTHOR"
categories: blog
tags: [TAGS, TAGS]
image: BLOG-HEADER-IMAGE.jpeg
---

some texts....

-------

if you want to add a <a href="https://somewebsite.com" target="_blank" rel="noopener noreferrer" style="color:blue;">link</a>, this opens a new tab.

-------

to add an image:
<figure>
  <img src="/assets/img/location-of your-image.jpg" alt="IMAGE-NAME" height="300">   
  <figcaption>Figure X: Add some caption underneath...</figcaption>
</figure>

-------

If you want the image to float to the right of some paragraphs, you can use the following:

<floatright>
<img src="/assets/img/location-of your-image.jpg" alt="IMAGE-NAME" height="250"><br>Figure X: Some caption. Similarly you can also use floatleft to place the image on the left
</floatright>

<p>
Then the paragraph of text should come here.

to add a line break use this:
<br>

continue with a new paragraph... Then this section should be shown on the left of your image.
</p>

-------

You can also line up to 4 images in a row like a gallery in your blog.

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="/assets/img/link-to-your-image1.jpg">
      <img src="/assets/img/link-to-your-image1.jpg" alt="IMAGE1-NAME" width="300">
    </a>
    <div class="desc"> </div>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="/assets/img/link-to-your-image2.jpg">
      <img src="/assets/img/link-to-your-image2.jpg" alt="IMAGE2-NAME" width="300">
    </a>
    <div class="desc"> </div>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="/assets/img/link-to-your-image3.jpg">
      <img src="/assets/img/link-to-your-image3.jpg" alt="IMAGE3-NAME" width="300">
    </a>
    <div class="desc"> </div>
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <a target="_blank" href="/assets/img/link-to-your-image4.jpg">
      <img src="/assets/img/link-to-your-image4.jpg" alt="IMAGE4-NAME" width="300">
    </a>
    <div class="desc"> </div>
  </div>
</div>

<div class="clearfix"></div>

You can add a caption under the images using this:

<div class="caption">
         Figure X: CAPTION FOR YOU IMAGES.
</div>

------- 

Other simple text formating can be found on this demo website:

https://lenpaul.github.io/Millennial/text-formatting