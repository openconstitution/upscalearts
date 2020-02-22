# Upscale Arts

Project to keep alive the art within us though artist who lacks computer and does not know how to publish content. Helping artist across the globe to share , protect and rise.


##Why Upscale ARTS

You can create per post a story and share story about an art or help an artist who cannot access computer and does not know how to publish art over internet.

All the art published here are copyrighted through a Non_Profit Org in Denmark: Muellners Foundation.

## How does it work

We upload every art for copyright protection over bitcoin based blockchain's like BTC, BCH, DASH usually a small fee is shared by a donor to publish the art over the internet and it will be co-owned by both donor, foundation and the artist.

## Donations Proceeding

Any donation proceeding goes directly to the artist , they use a crypto wallet to recieve funds and using local p2p liquidity pools gets fiat out.

## Help

If you are a developer and knows an artist you can contribute by simply forking this repo and creating a post refer to
[Create Posts] (#createposts)

## Initial Setup
* [Installation](#installation)
* [Create Posts](#create-posts)
* [Create Pages](#create-pages)
* [Create Navigation](#create-navigation)


### Installation
Jekyll requires all dependencies to be saved in the ````Gemfile````. Run ````bundle install```` (Install [Bundler](http://bundler.io/) if it is not already) on your command line after downloading or cloning the theme. You can then run ````bundle exec jekyll serve```` or ````npm start```` to see your development site. Run ````bundle exec jekyll build```` or ````npm run build```` to build a production ready site for deployment.


### Create Posts
All posts go upder the ````_posts```` directory. You can also have a ````_drafts```` directory with posts that will on your development page, but not in production.

```
---
layout: post
title: "Escape from city"
date: 2020-02-21
description:
image: /assets/images/placeholder-8.jpg
author: Saransh Sharma
artist: Shantaram Kadam
artist_description:
donate: You can donate to this address
copyright: Muellners Foundation
tags:
  - Squid
  - Moon Drinking
  - Kale
---
```

The front matter has to have a layout of page. All the other fields are completely optional. If you have an ````author```` variable, then it must match an author's name in ````_config.yml```` (see [Update Settings](#update-settings)). The ````tag```` variable will add a related section to the post and popular tags to the footer.

### Create Pages
Creating a static page is the same as creating a post. The only difference is a page is in the root of the directory rather than the ````_posts```` directory.

```
---
layout: page
title: Style Guide
image: /assets/images/placeholder-18.jpg
---
```

You just have to make sure the front matter has a layout of page instead of post. If there is no title or image, then the page will default to the site configuration.

### Create Navigation
You can create a navigation in ````_includes/navigation.html````. Visitors can be linked directly to pages right on the top of your website.

***


### Source Code
The source code is broken down to make finding what you need as easy as possible. Almost everything runs through ````gulpfile.js````, so you will need to run ````npm install```` on your command line before doing any additional development. You can then run ````gulp```` or ````npm run gulp```` to compile everything.

```
.
├── _assets
|   ├── js
|       ├── components
|       ├── vendor
|       ├── _inits.js
|       └── app.js
|   └── scss
|       ├── base
|       ├── components
|       ├── fonts
|       ├── regions
|       ├── tools
|       ├── utils
|       ├── vendor
|       └── app.scss
├── _includes
|   ├── contact.html
|   ├── disqus.html
|   ├── footer.html
|   ├── formcarry.html
|   ├── head.html
|   ├── header.html
|   ├── navigation.html
|   ├── pagination.html
|   ├── post-card.html
|   ├── share.html
|   ├── social.html
|   └── subscribe_form.html
├── _layouts
|   ├── compress.html
|   ├── default.html
|   ├── page.html
|   ├── post.html
|   └── tag.html
├── _plugins
├── _posts
├── _site
├── assets
|   ├── css
|   ├── images
|   ├── js
├── .eslintrc
├── .gitignore
├── .stylelintrc
├── 404.html
├── _config.yml
├── Gemfile
├── Gemfile.lock
├── gulpfile.js
├── index.html
├── package.json
├── README.md
├── style-guidle.html
└── subscribe.html
```

The CSS is written in Sass. The JavaScript is written in ES6, so your code is up to date with the newest standards.

### Donations

* PayPal – <https://www.paypal.me/samesies>
* Bitcoin – 1PSzNmcfAFJY1PtBK5u9R5bTGfF7KAuLcq
* Ethereum – 0x392F7116e4171F1D740397B6000EadD2e4bb9670
* Litecoin – LSH9AnjcUTV5T7PUxXQuxPqb9W5aSR9GEP

### Support
Email <info@muellners.org> if you need any additional support or info.
