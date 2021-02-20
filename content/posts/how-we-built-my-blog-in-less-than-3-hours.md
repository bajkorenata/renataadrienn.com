---
date: 2021-02-20T17:00:59+02:00
hero_image: "/content/images/qinghong-shen-2kk81yj8tm8-unsplash.jpg"
title: How We Built My Blog (in less than three hours)
author: Renáta-Adrienn

---
First things first. It's highly advised that you don't start building something new before you know you have a clean and organized slate. Especially if you're a Virgo.

So I proceeded exactly how I would proceed with a messy kitchen before cooking a fresh meal: cleaning up my Github profile. I deleted everything outdated and set to private all that isn't quite ready, or relevant.

## The Constraint

There was only one constraint that I set myself: time.

I sat out that I cannot trouble my partner for more than one hour for the whole setup process. And that I wouldn't spend more than two hours customizing the website.

Without further ado... this is how we actually built the blog.

The decision for this tech stack was made by my partner a couple of months back when he researched all types of technologies for our future projects. We built the current website for MerakiDesigns with it, and I find that it's perfect for something like this small blog of mine.

Let's do this.

### Installing Forestry and Basic CMS Setup

This didn't take 10 minutes in total and I was absolutely delighted that it's this easy.

![](/content/images/how-we-built-01.jpg)

1. On [Forestry](https://forestry.io/ "Forestry"), I first went to "Select a Starter Template"
2. I chose the "[Brevifolia](https://brevifolia-gridsome-forestry.netlify.app/ "Brevifolia")" starter because it's already very close to what I wanted my site to look like and it's built with Gatsby
3. It was extremely easy to create my Github repository and import it to Forestry (I didn't even need to leave their page, at all)
4. And there we go, my install was complete
5. I now followed the setup process suggested by the CMS, but that's totally optional
6. Added the site name, site info, and other details in the "Settings"
7. Hello there, our basic CMS setup is also complete

### Local Setup

It took me five minutes to get the project working locally.

1. I cloned my repository directly into Visual Studio Code, through the Explorer page
2. Opened the project's folder after the clone was done
3. We're very much playing by the rules, so I scanned through the readme file
4. Installed all dependencies
5. Ran the local project. Nice

![The original "Bravifolia" template, before any changes were made to it.](/content/images/screenshot-2021-02-19-at-14-30-27.png 'The original "Bravifolia" template, before any changes were made to it.')

### Styling the Template

As I already mentioned, for this task I gave myself two hours. There were a couple of things I wanted to modify, but I didn't want to go overboard. It's a personal blog. The most important thing was to get it deployed as quickly as possible and write as much as possible. Small HTML and CSS customizations can go a long way.

I started fiddling with the CSS at around 13:30. Here's a couple of things that I did:

* Switched the sidebar to a topbar
* Overall layout changes: made everything tighter and aligned to the center
* Made some updates to the typographic style, and also switched to a mix between "[EB Garamond](https://fonts.google.com/specimen/EB+Garamond "EB Garamond")" and "[Inter](https://fonts.google.com/specimen/Inter "Inter")" rather than keeping everything in "[Work Sans](https://fonts.google.com/specimen/Work+Sans "Work Sans")"
* Had an idea to add a fixed position to the navbar, and I liked it, so we kept it
* Changed the layout and style of the blog list on the homepage

I took a 10-minute stretch and coffee break at 15:00 and realized I have half an hour until I need to commit all my changes.

* Changed the favicon to an olive branch
* Removed a setting that made all images on the homepage's blog list the same height regardless of their original ratio
* More tweaking the way images appear on different screen sizes, especially on the article page (this added a half an hour delay, but hey)
* Other very small spacing and typographic fixes

![A sneak peak into how the template will look after customization.](/content/images/screenshot-2021-02-20-at-15-54-06.png "A sneak peak into how the template will look after customization.")

### We're Ready to Deploy

I committed and pushed all the changes to my Github repo. Quickly tested if everything still works, and looks good.

### Getting it Live

1. I imported the Github project to [Vercel](https://vercel.com/ "Vercel") to deploy our static build. Here we created the connection between my domain and Vercel's DNSs. This canceled out the need to buy hosting the old-fashioned way. Gorgeous.  
   ![Importing the Github project to Vercel for deployment](/content/images/screenshot-2021-02-20-at-16-14-24.png)
2. After the deployment, I changed the "A" and the "DNS" records on my domain provider's website to the ones indicated by Vercel
3. A quick celebration that all went well and seamlessly and the website is already up and runninggggg!

### Final Stage

I cleaned out the CMS from all the dummy content that came with the template and I started to add my very first article about "[Why Start a Blog](https://renataadrienn.com/blog/why-start-a-blog "Why Start a Blog")".

![A final screenshot with my website's homepage](/content/images/screenshot-2021-02-20-at-17-31-55.png)

There we go. It's live. It's ready.

We built it in under three hours, and I spent another hour, probably an hour and a half finishing and publishing the first two posts. Pretty rad. Pat on the back.

Challenge complete, and I couldn't be more pleased with what we built.

PS: Thank you for your patience and your guidance, my love!