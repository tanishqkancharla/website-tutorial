# Website Tutorial
This repository contains docs about how to make a website!

We'll be making a website using [Github Pages](https://pages.github.com) and [11ty](https://www.11ty.dev). You will __not__ need to know how to program, to use this guide. However, if you do know HTML/CSS, you'll be able to use it to make your website a little more spiffy.

## Introduction

*What are we gonna do?*

When you request a website on your browser, that request goes to a server (a kind of computer). The server then returns ("serves") the website to the browser in the form of HTML and CSS. The browser then renders this message into a website. 

This means to make a website, you need to have two things: a **hosting provider**, and the **HTML/CSS** of the website.

### Hosting provider

A hosting provider sets up a server to host your website for you. For this project, we'll be using Github Pages as the provider (since its free and easy). It's free because 1. It's very cheap for Github to set this up and 2. Github gets a marginal amount of advertisement by automatically putting "github" in your URL domain. If you want to use your own domain, you can read about that [here](https://docs.github.com/en/github/working-with-github-pages/configuring-a-custom-domain-for-your-github-pages-site).

### HTML/CSS

As for the HTML/CSS, I'm going to stay true to my promise; you won't need to know how to program in those languages (although if you're interested, [this is a great tutorial](https://html-css-js.com/html/tutorial/). Instead we're going to write the content of our website in something called [**Markdown**](https://www.markdowntutorial.com). Then, we use [11ty](https://www.11ty.dev) to convert those Markdown files into the final HTML/CSS files.

## Setting up Github

*What's Github, and how will we use it?*

Github is basically like a Google Drive, OneDrive, or Dropbox, but for code. People all over the world use it for their programs and code. Then they can share these with other people or make it public to the world. A single project/website will be hosted in something called a **repository**. This entire website was made using this tutorial, by the way! The repository for this website is [here](https://github.com/moonrise-tk/website-tutorial). 