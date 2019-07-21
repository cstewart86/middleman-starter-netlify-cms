---
title: How to audit your website’s speed
seoTitle: How to audit your website’s speed | Redwave Marketing
date: 2019-07-13T10:01:00.000Z
description: >-
  It’s now widely known that speed is one of the key factors that search engines
  use to determine the quality of your website. But how do you know if you have
  a problem?
metaDescription: >-
  It’s widely known that speed is a key factor that search engines use to
  determine the quality of your website. But how do you know if you have a
  problem?
image: /images/uploads/website-speed.png
---
It’s now widely known that speed is one of the key factors that search engines use to determine the quality of your website. But how do you know if you have a problem?

In this guide we’ll take you through some diagnostic tests to determine whether your website has a speed problem and what you can do about it.

## Auditing your website

Your first port of call is [Google Pagespeed Insights](https://developers.google.com/speed/pagespeed/insights/). This is a great tool which loads your site in Chrome in the background and spits out a list of recommendations to improve your website speed. 

Some of the recommendations you receive will be quite technical but it will provide your site with a speed score out of 100 for both mobile and desktop users - the key distinction between the two is that, since mobile visitors are often on a slower connection, what might seem like a reasonable speed on a WiFi connection might be unusually show for your mobile visitors.

![A snapshot of a Google Pagespeed Insights report, showing a desktop score of 100%](/images/uploads/D50CB878-92A8-46BE-89FF-C42482F29195.png)

It’s important to note that scores of 100 in this test are rare. Here at Redwave, we always ensure that our sites achieve a minimum score of 90 on mobile and 95 on desktop.

If your scores are significantly below this, you’re almost certainly being penalised to some extent by search engines so it’s worth taking the time to improve your score. 

If you’re hungry for more information, you can also visit [website.grader.com](https://website.grader.com) which will analyse your site on a number of key areas, including speed.

![A snapshot of a report from website.grader, showing its four scoring categories of performance, mobile, SEO and security.](/images/uploads/website-grader.png)

[GT Metrix](https://gtmetrix.com) is another good tool to assess site speed. The majority of recommendations it provides will only be understood by a developer but it does provide two grades, provided by two different scoring systems, which can give you an indication of how your site compares.

![A snapshot of a report from GT Metrix, showing its grades from PageSpeed and YSlow](/images/uploads/gt-metrix.png)

## Fixing the issues

A lot of speed issues are quite technical but we've set out below some fixes that you can make with yourself along with some more technical considerations to allow you to have an informed discussion with your developer.

### Optimising images

One of the major factors in a slow loading website is often image size. Fortunately this is quite an easy one to fix. 

The best way that we have found to optimise our images is to use an app called [Squoosh](https://squoosh.app) which was developed by the engineers at Google.

You can load your images into Squoosh which will compress them without any visible loss of quality. You can then download the optimised versions and replace the unoptimised versions on your site.

If you use WordPress, it’s also worth installing a plugin such as EWWW Image Optimizer or reSmush.it which will automatically compress any images you upload. They don’t tend to provide quite the same savings that Squoosh does but they do make the process very easy.

### Use a content delivery network

Another optimisation which can have a dramatic effect on performance is the use of a content delivery network. 

A content delivery network is a global network of servers which each hosts a copy of your files.

What this means in practice is that rather than your visitors potentially waiting for every file on your site to be sent to the, from a single server on the other side of the world, your visitors will be sent the files from a server much closer to them.

These servers are also specially configured to be able to deliver files quickly. 

If you own a large website, a content delivery network can be expensive to run but for smaller websites, the leading content delivery network provider, [Cloudflare](https://www.cloudflare.com/), offers a free package.

### Remove unused plugins

It’s possible that your website, particularly if it’s a Wordpress website, may have a large number of plugins. 

Plugins can be an incredibly useful and cost effective way of adding advanced functionality to your website but they often come with a speed cost. 

If there are plugins on your site which you don’t use, removing them is likely to improve the speed of your site.

### Reduce the number of files used on your website

If the tools mentioned above flag that your website has 'too many HTTP requests' then you'll want to look at reducing the number of files your website serves.

This doesn't necessarily mean visible files such as images and PDFs but can include the files which dictate how your website looks and functions.

A common fix is to remove unused files and to bundle others. Your developer will be able to talk you through the pros and cons of these approaches.

### Reduce the size of code files

The code files on your website (those we've mentioned above which dictate the design and functionality of your site) can often be unnecessarily bloated.

This can be caused by a number of issues but the most common is that a framework such as Bootstrap has been used and your website only uses a small amount of its functionality.

Whatever the cause, this issue can have a significant effect on the speed on your site as the browser has to download each file and then interpret it before it can load your site.

Cutting unused parts of your files will help as will 'minification' - the practice of removing spaces and developer notes from the files.

### Give priority to the content that visitors will see first

Your site may need a large number of files but how many of them are needed when a visitor first loads your site?

Some of the files on your site may need to be loaded before others, such as your hero image or a code library such as jQuery but, often, there are a large number of files on your site which won't be needed until a visitor scrolls down the page.

The solution is to defer the loading of code files or load them asynchronously (this downloads them in parallel with other content, meaning that they don't block the loading of the rest of the page) and to lazyload some images (they will only load as they scroll into view).

You'll want your developer to look at the loading of your code files but there may be plugins you can use to lazyload your images. For example, if your site is built on WordPress, you can use WP Rocket.

## Can we help?

We're passionate about helping small businesses punch above their weight online and we'd be happy to give further advice.

[Contact us](/contact/) for an informal, no obligation chat.
