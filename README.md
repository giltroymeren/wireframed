[wireframed](http://www.tumblr.com/theme/36746)
==========

A tumblr theme with wires and boxes (waiting for moderators' approval)

Installation
------------
1. Open your blog, i.e. go to `http://your-tumblr-url.tumblr.com`
2. Click **Customize**
3. On the left panel click the **Edit HTML** button.
4. Just paste the Slats code to the text editor that will appear.
5. Save 
6. Customize the theme with the different options available

Documentation
-------------
### Overview
- Supports all nine kinds of tumblr posts
  1. Text
  2. Chat
  3. Link
  4. Quote
  5. Ask
  6. Photo
  7. Photoset
  8. Audio
  9. Video
- Header contains:
  - blog title
- Sidebar contains:
  - Item header (*About Me*, *Links*, etc.)
  - Blog description
      - a 96px by 96px photo intended for the blog
      - blog description (can contain HTML)
  - Links list
        - contains the basic links (Homes, RSS Feed, etc.)
        - custom pages are automatically added to this list
  - search form
  - Twitter integration (if you enable twitter connection with tumblr)
- Footer contains:
  - title of blog followed by a generic copyright format
  - this theme's information
  - credit to tumblr
  - sitemap featuring the sidebar links list
  - navigation

### Third Party Stuff
- CSS Hacks 
  - [Clearfix Hack](http://nicolasgallagher.com/micro-clearfix-hack/) by Nicholas Gallagher
  - [CSS Sticky Footer](http://www.cssstickyfooter.com/)
  - [Meyer Reset](http://meyerweb.com/eric/tools/css/reset/) by Eric Meyer
  - `normalize.css` from the [Bootstrap](http://twitter.github.com/bootstrap/) package
- Fonts by [Google Web Fonts](http://www.google.com/webfonts)
  - [Dosis](http://www.google.com/webfonts/specimen/Dosis) by Pablo Impallari
  - [Droid Sans](http://www.google.com/webfonts/specimen/Droid+Sans) by Steve Matteson

### Customization Defaults
- Colors
  - Accent: #0AF
  - Complement: #FF7300
  - Dark: #000
  - Mid dark: #AAA
  - Light: #F7F7F7
  - Lighter dark: #DDD
- Blog parts
  - Show header: True
  - Show blog photo: True
  - Show permalink: True
  - Show post separator: True
  - Show reblog source: True
  - Show sidebar: True
  - Show tags: True

### Known limitations/bugs:
- The Permalink sidebar is still rendered in the **Ask** and **Submit** pages (MUST BE REMOVED)

Updates
-------
*29 December 2012*

1. Removed `{block:Pagination} {/block:Pagination}` from footer so that the new and older page links will appear correctly
2. Changed `#header > a`'s `line-height` to 2ems.
