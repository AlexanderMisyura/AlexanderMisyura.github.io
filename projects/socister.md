---
layout: project
type: project
image: img/socister/socister-square2.jpg
title: "Socister"
date: 2022-11-17
published: true
labels:
  - HTML
  - CSS
  - JavaScript
  - Node.js
  - Express
  - Handlebars
  - MongoDB
summary: "Social media website."
---

<hr>

### A full stack social media website.

### Features:
 - user login/registration
 - user profile dashboard
 - manageable categories:
   - posts (can be public, private, visible only to friends. Users can add new, edit or delete existing own posts.)
   - comments (when deleting a comment, it is marked as *Comment was deleted* if it has non-deleted replies, otherwise it is completely deleted )
   - bookmarks (save/delete posts to a separate list)
   - friends (send/cancel own friend request, accept/reject someone else's request, remove a user from friends list)
 - post and comment likes (increase user rating)

**Link to project:**
<a href="https://socister.onrender.com">socister.onrender.com</a>

<hr>

<img class="img-fluid" src="../img/socister/socister3.gif">

<hr>

Project is built using Node.js runtime and Express.js web framework.
Server side rendering with Handlebars templating engine, styling with Bulma CSS framework.
Data: MongoDB Atlas and mongoose ODM, image storage and management by Cloudinary service.

<hr>

Source: <a href="https://github.com/AlexanderMisyura/social-media-app"><i class="large github icon "></i>AlexanderMisyura/social-media-app</a>
