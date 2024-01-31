# Cloud Resume Challenge

Series of challenges, which deepen AWS knowledge and provide an opportunity to perform technical experience using AWS.

## Table of Contents

- [Cloud Resume Challenge](#cloud-resume-challenge)
  - [Table of Contents](#table-of-contents)
  - [Benefits of the challenge](#benefits-of-the-challenge)
  - [Challenge stages](#challenge-stages)
    - [Step 1 - Certification](#certification)
    - [Step 2 - HTML](#html)
    - [Step 3 - CSS](#css)
    - [Step 4 - Static Website](#static-website)
    - [Step 5 - HTTPS](#https)

## Certification
Work in progress.

## HTML
I already had a plain resume format which I use to apply to jobs, so I converted it into HTML.

## CSS
I added the CSS code to match the style of my resume format.

## Static Website

For challenge 4 of the Cloud Resume Challenge, I was tasked with deploying my resume online as an Amazon S3 static website.

## Documentation
On the AWS Console, I searched for S3 and clicked on it.

On the general purpose buckets screen, I clicked on create bucket and ended up on the screen in the screenshot shown below.

![](https://i.imgur.com/GOm5yfi.png)

From here, I named my bucket rwcloudresumebucket, left the remaining settings on the screen as default for now, and saved my changes.

Back on the general purpose buckets screen, I clicked on my newly created bucket, and was presented with the objects tab.

Objects are the entities that are stored in Amazon S3. In my case, the objects the HTML and CSS files for my static website, so I uploaded both files as seen below. 

![](https://i.imgur.com/TuOoe7z.png)

Under the properties tab, I had to enable static website hosting so I scrolled to the bottom of the screen where it says static website hosting and clicked edit to enable the feature. 

![](https://i.imgur.com/WTsl5Dl.png) 

There was not much to change here except for enabling the feature, selecting host a static website, and specifying the index document as index.html.

![](https://i.imgur.com/xJq6u3C.png)

Once those changes were saved, I went to the permissions tab, clicked edit on Block public access (bucket settings) and disabled the block all public access feature by deselecting the option. 

![](https://i.imgur.com/rnBy9Vh.png)

This step is crucial for enabling the resume to be accessed by the public, which is essentially the end goal here.

This is the end of challenge 4. The documentation for challenge 5 will be a continuation of this.

## HTTPS


