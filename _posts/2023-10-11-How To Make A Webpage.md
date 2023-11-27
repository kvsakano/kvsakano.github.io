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
    - You will need to first install a Ruby version of >3.0. I downloaded the <a href="https://rubyinstaller.org/downloads/archives" target="_blank" style="color: DodgerBlue; font-weight: bold;">Ruby+Devkit 3.2.2-1 (x64)</a>. installer.
    - Run `ridk install` on the last stage of the installation wizard to install gem. Alternatively, if you check the box on the last page, it will auto run this command. Hit <b>Enter</b> a few times to install all the recommended packages.
    - Open a new terminal and run `bundle install` and then `gem install Jekyll bundler`
    - Check if Jekyll has been installed by running `jekyll -v`
    - Lastly, you'll need to install <a href="https://rubyinstaller.org/downloads/archives" target="_blank" style="color: DodgerBlue; font-weight: bold;">Ruby+Devkit 2.7.2-1 (x64)</a> and follow the rest of the instructions for downgrading ruby locally that Gemma detailed in her blog.


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
1. <b>Clone the repository from the <a href="https://github.com/tcbutler320/Jekyll-Theme-Dumbarton" target="_blank" style="color: DodgerBlue; font-weight: bold;">Dumbarton Github Page</a> page </b>.
    - Select the "Create new repository" option.

<figure>
    <img src="/assets/img/posts/webpage/github_newrepo.png"
         width="50%"
         align="right">
</figure>
2. <b>Create a new repository on GitHub </b>- your repository name will be [GitHub username].github.io 
    - For example, I set my repository to <b>kvsakano.github.io</b>, and my GitHub username is kvsakano.
    - Set the repository to Public

3. <b>Use your GitBash to clone your new repository to your desired location on your computer.</b>

4. <b> Open the directory in VSCode</b> - or whatever your preferred text editor is.

5. <b> Run `bundle exec jekyll serve` in the repo's folder via GitBash</b> - this command runs the exact jekyll server version that is specified in your Gemfile.

6. <b> Open your web page locally </b> using the URL pasted in your GitBash. You can paste the Server address (example: http://127.0.0.1:4000) in a webpage and your website should pop up.
- Note that if you terminate the batch job/exit out of the jekyll command, it'll close your local page connection. 

7. <b> Make your edits, then save & push your changes </b>. You can either terminate the batch job and use the same GitBash app, or open up a second tab and do so there.
- Useful Git commands: 
  - `git add *` 
  - `git commit -m "[Insert your message here]"`
  - `git push`
