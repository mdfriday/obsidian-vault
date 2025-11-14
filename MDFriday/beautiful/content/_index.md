---
title: Home
subtitle: Build a beautiful and simple website in minutes
description: This is the home page of the example site for the beautifulhugo theme.
bigImages: ["img/triangle.jpg", "img/sphere.jpg", "img/hexagon.jpg"]

menu:
  nav:
    - title: "Home"
      url: ""
      weight: 1
    - title: "Blog"
      url: "/posts/"
      weight: 2
      children:
        - title: "Getting Started"
          url: "posts/2015-01-04-first-post.html"
          weight: 1
        - title: "Big Image Sample"
          url: "posts/2017-03-07-bigimg-sample.html"
          weight: 2
    - title: "Tags"
      url: "tags"
      weight: 4

organization:
  name: "MDFriday Inc."
  description: "MDFriday is a powerful Markdown editor and note-taking app."
  vision: "Focus on creating, MDFriday makes your sites shine."
  website: "https://mdfriday.com"
  logo: "/images/logo.png"
  contact:
    email: "team@mdfriday.org"
    address: "Remote, Global"
    phone: "+1-202-555-0100"
  social:
    github: "https://github.com/mdfriday"
    twitter: "https://twitter.com/mdfriday"

author:
  name: "Sun Wei"
  description: "Creator of MDFriday, passionate about Markdown, AI, and knowledge visualization."
  website: "https://sunwei.xyz"
  avatar: "/images/avatar.png"
  contact:
    email: "sunwei@mdfriday.org"
    address: "Remote, Global"
    phone: "+1-202-555-0101"
  social:
    website: "https://yourwebsite.com"
    email: "mailto:youremail@domain.com"
    facebook: "https://facebook.com/username"
    github: "https://github.com/username"
    gitlab: "https://gitlab.com/username"
    bitbucket: "https://bitbucket.org/username"
    twitter: "https://twitter.com/username"
    reddit: "https://reddit.com/user/username"
    linkedin: "https://linkedin.com/in/username"
    xing: "https://www.xing.com/profile/username"
    stackoverflow: "https://stackoverflow.com/users/XXXXXXX/username"
    snapchat: "https://www.snapchat.com/add/username"
    instagram: "https://instagram.com/username"
    youtube: "https://youtube.com/user/username" 
    soundcloud: "https://soundcloud.com/username"
    spotify: "https://open.spotify.com/user/username"
    bandcamp: "https://username.bandcamp.com"
    itchio: "https://username.itch.io"
    vk: "https://vk.com/username"
    paypal: "https://paypal.me/username"
    telegram: "https://t.me/username"
    500px: "https://500px.com/username"
    codepen: "https://codepen.io/username"
    mastodon: "https://mastodon.social/@username"   # 需要根据实例替换
    kaggle: "https://kaggle.com/username"
    weibo: "https://weibo.com/username"
    slack: "https://username.slack.com"
    medium: "https://medium.com/@username"
    discord: "https://discord.gg/XXXXXXX"
    strava: "https://www.strava.com/athletes/userid"
    lastfm: "https://last.fm/user/username"
    bluesky: "https://bsky.app/profile/username"


---

## Front Page Content
`beautifulhugo` supports content on your front page. Edit `/content/_index.md` to change what appears here. Delete `/content/_index.md` if you don't want any content here.