+++
date = 2020-06-21T16:00:00Z
draft = true
tags = ["Hugo"]
title = "How do I make this website ?"

+++
## Set-up

* Theme : [Cupper-Hugo-Theme](https://github.com/zwbetz-gh/cupper-hugo-theme)
* Framework : [Hugo](https://gohugo.io/)
* Language : Golang
* CMS : [Forestry](https://app.forestry.io)
* Deployed Server : [Netilify](https://app.netlify.com)

## Installation

1. Fork this [theme](https://github.com/zwbetz-gh/cupper-hugo-theme) to your Github account
2. Go to [Forestry](https://app.forestry.io) 
   1. Choose Hugo
   2. Choose Github provider
   3. Choose the repository you forked
   4. In Config Path , type : 

      ```html
       exampleSite/config.yaml
      ```

      Then , Click **Check for Config**

      A text **Config file found** should be shown
   5.  Click mark as done for all side-alerts
3. Go to [Netilify](https://app.netlify.com)
   1. Choose New Site from git
   2. Choose the repository you forked
   3. After Deploy, go to Setting and Domain management, and to customize your domain name (E.g: [https://ryuhugo.netlify.app/](https://ryuhugo.netlify.app/ "https://ryuhugo.netlify.app/") )
4. Go to Github, find the file config.yaml , which should be located in cupper-hugo-theme/exampleSite/config.yaml

   Change the baseurl to your own domain name

   {{< cmd >}}

   baseURL: [https://ryuhugo.netlify.app](https://ryuhugo.netlify.app "https://ryuhugo.netlify.app")

   {{< /cmd >}}
5.  **Finished !!!!**

## Usage