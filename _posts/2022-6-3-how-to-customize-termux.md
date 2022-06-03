---
title: "How to Customize Termux" # Title of the blog post.
description: "How to customize termux,change color schemes and fonts.description." # Description used for search engine.
featured: true # Sets if post is a featured post, making it appear on the sidebar. A featured post won't be listed on the sidebar if it's the current page
draft: false # Sets whether to render this page. Draft of true will not be rendered.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
# menu: main
featureImage: "https://raw.githubusercontent.com/codingame120/uptech/ddb4b35dba5a98b609e1a06bb06cb3bf9a9f9712/content/images/termux/customize.jpg" # Sets featured image on blog post.
thumbnail: "https://raw.githubusercontent.com/codingame120/uptech/ddb4b35dba5a98b609e1a06bb06cb3bf9a9f9712/content/images/termux/customize1.jpg" # Sets thumbnail image appearing inside card on homepage.
shareImage: "https://raw.githubusercontent.com/codingame120/uptech/ddb4b35dba5a98b609e1a06bb06cb3bf9a9f9712/content/images/termux/customize1.jpg" # Designate a separate image for social media sharing.
codeMaxLines: 10 # Override global value for how many lines within a code block before auto-collapsing.
codeLineNumbers: false # Override global value for showing of line numbers within code block.
figurePositionShow: true # Override global value for showing the figure label.
categories:
  - Technology
  - How To
tags:
  - Termux
  - Android
series:
  - Termux
---

<br/>
<br/>

## Removing Termux Welcome Screen Text

We will start with removing termux welcome screen text.

Type:

```
cd ..
```

To change directory.

```
ls
```

To list directory.

```
cd usr/etc
```

Change directory to `etc`

```
ls
```

List directory.

```
rm -rf motd
```

Remove file named `motd`.

When you start new window you will see that there is no more welcome text and termux start with clean window.
With those commands we were to remove `motd` file.

Now lets see how to change color schemes and fonts.

There are more ways to do this, but we will use `Termux-Ohmyzsh`.

You will need `curl` installed.
So if you don't have it already
type those commands:

```
pkg update && pkg upgrade
```

And

```
pkg install curl
```

With curl you can download files from the Internet.

<br/>

## Install Termux-Ohmyzsh

So now when all is set we can proceed
type or copy this line in your termux terminal:

```
sh -c "$(curl -fsSL https://github.com/Cabbagec/termux-ohmyzsh/raw/master/install.sh)"
```

It will download `Termux-Ohmyzsh`.

<br/>

## Change Color Schemes

Now when you have installed.

Type:

```
chcolor
```

Or run:
`~/.termux/colors.sh`
To change color schemes.

You can change color schemes simple by entering the number of the scheme you want to use.

<br/>

## Change Fonts

To change fonts.

Type:

```
chfont
```

Or run:
`~/.termux/fonts.sh`

And same as for color scheme type number of font style you want to use and hit enter.
You can use two finger pinches to adjust font size.

And that is how you can change color schemes and font styles in termux with `Termux-Ohmyzsh`.

If you are interested in more termux tips and other interesting tech topics stay tuned.
If you have any questions or suggestions feel free to say us in comments.

## Watch Video Example

You can watch and video example:

{{< youtube sfk8rEVRrC4 >}}

<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>

<br/>
<br/>
<br/>
<br/>
<br/>
