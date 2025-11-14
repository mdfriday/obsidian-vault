---
title: Home
subtitle: Build a beautiful and simple website in minutes
description: This is the home page of the example site for the beautifulhugo theme.
bigImages: ["img/triangle.jpg", "img/sphere.jpg", "img/hexagon.jpg"]

menu:
  nav:
    - title: "Home"
      url: "zh/"
      weight: 1
    - title: "Blog"
      url: ""
      weight: 2
      children:
        - title: "Getting Started"
          url: "zh/posts/2015-01-04-first-post.html"
          weight: 1
    - title: "Tags"
      url: "zh/tags"
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
    facebook: "https://facebook.com/username"
    github: "https://github.com/username"
    twitter: "https://twitter.com/username"

---

## Front Page 内容
`beautifulhugo` supports content on your front page. Edit `/content/_index.md` to change what appears here. Delete `/content/_index.md` if you don't want any content here.