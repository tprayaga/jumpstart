+++
date = 2021-08-18T07:00:00Z
title = "How to Create your Custom Domain Free Static Website with Hugo + Netlify + Forestry.io + GitHub"

+++
If you want to create your own static website and do it free, and wondering how to do it, you have come to the right place. Static websites don't need an active web server or hosting, which will cost you money at most places. CMS solutions like Wordpress are dynamic websites where there is a web server and database running and this kind of solutions are often prone to security vulnerabilities and attacks. Unlike dynamic websites, static websites are static files read and rendered by your web browser.

In this post, I will go through how you can setup your custom domain static website using the following tools and services

* [GitHub](https://github.com/ "GitHub")
* [Netlify](https://www.netlify.com/ "Netlify")
* Forestry.io
* Google Domains (setup your custom domain)
* Mac (to work on your files locally)

# Step-1: Create GitHub Account and Setup Repository

git init

git add .

git commit -m "Initial commit"

git remote set-url origin git@github.com:tprayaga/jumpstart.git

Setup Netlify

Setup build hook

    create a new build hook
    
    specify this build hook in the Github repo

Setup Forestry