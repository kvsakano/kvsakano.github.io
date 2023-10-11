---
layout: post
title:  "How To Make Your Own Webpage"
description: "Zero to Hero: How to Make Your Own Webpage (even if this is your first webpage!)"
type: card-img-top
categories: latin text
image: http://placehold.it/750X300?text=Header+Image # for local images, place in /assets/img/posts/
caption:
foo:   "2023-10-11"
categories: 
tag: 
author: Kristy Sakano
card: card-1
---

Did you like my webpage? Thanks! I used this theme from Tyler Butler called <a href="https://github.com/tcbutler320/Jekyll-Theme-Dumbarton" target="_blank" style="color: DodgerBlue; font-weight: bold;">Dumbarton</a>. It's not originally built to be hosted on GitHub pages, but I found a workaround that might help you host your own webpage for free on GitHub Pages!

<br/>

#### Introduction

If this is your first time making a webpage, don't worry - I didn't have any web design experience before making my own website. You'll first need a few applications:

1. A text editor (of your choice). Personally, I use <a href="https://code.visualstudio.com/" target="_blank" style="color: DodgerBlue; font-weight: bold;">Visual Studio Code</a> because their file explorer is very intuitive, but you can use anything from Vim, Emacs, or Atom. Check out <a href="https://medium.com/swlh/why-visual-studio-code-is-the-best-code-editor-for-web-development-1b2096051c64" target="_blank" style="color: DodgerBlue; font-weight: bold;">this article</a> comparing code editors if you want to see other alternatives!

2. <a href="https:/github.com" style="color: DodgerBlue; font-weight: bold;">GitHub Account</a> - it's free! And you don't need GitHub Pro either.
    - Your GitHub username will be part of your webpage's hyperlink, so pick carefully!
    - You will also need <a href="https://git-scm.com/downloads" style="color: DodgerBlue; font-weight: bold;">git bash</a> unless your terminal already has git commands.
    - Don't forget to create your keys on your machine & upload your public key to your GitHub account.

3. <a href="https://www.ruby-lang.org/en/" target="_blank" style="color: DodgerBlue; font-weight: bold;">Ruby</a> (+ devkit package) - I used Ruby 2.7.2 which is an older version, but compatible with jekyll-scholar and <a href="https://open-research.gemmadanks.com/tutorials/how-to-use-jekyll-scholar-with-github-pages/" target="_blank" style="color: DodgerBlue; font-weight: bold;">recommended by researcher Gemma Danks</a>. (Thanks Gemma!)
    - Run `ridk install` on the last stage of the installation wizard (this installs gem)
    - Open a new terminal and run `gem install Jekyll bundler`
    - Check if Jekyll has been installed by running `jekyll -v`

#### Useful References

When creating my own webpage, I referenced a number of Youtube videos and blogs. This is an incomplete list of all the sources I utilized during my initial setup, but I want to credit the following:

1. <a href="https://open-research.gemmadanks.com/tutorials/how-to-use-jekyll-scholar-with-GitHub-pages/" target="_blank" style="color: DodgerBlue; font-weight: bold;">How to use jekyll-scholar with GitHub Pages</a> by Gemma Danks
2. <a href="https://www.youtube.com/watch?v=g6AJ9qPPoyc&ab_channel=SpencerPao" target="_blank" style="color: DodgerBlue; font-weight: bold;">How To Build A Website | GitHub Pages | Jekyll | Template</a> by Spencer Pao
3. <a href="https://www.youtube.com/watch?v=o5g-lUuFgpg&ab_channel=TonyTeachesTech" target="_blank" style="color: DodgerBlue; font-weight: bold;">How to Create a Free Website Using GitHub Pages</a> by Tony Florida


#### Instructions

<figure>
    <img src="/assets/img/posts/webpage/dumbarton_clone.png"
         width="50%"
         align="right">
</figure>
1. Clone the repository from the Dumbarton Github page.
    - Select the "Create new repository" option.

<figure>
    <img src="/assets/img/posts/webpage/github_newrepo.png"
         width="50%"
         align="right">
</figure>
2. Create a new repository on GitHub - your repository name will be [GitHub username].GitHub.io 
    - Set the repository to Public

