# THE C BLOG

## This is a personal blogging website where [I](https://github.com/GEORGE-GICHURU) can create and share my opinions via a blog post and other users can read and comment on posts, 16/5/2022.


## By **[George Gichuru](https://github.com/GEORGE-GICHURU)**

## Description
[This] is a web application that allows me, as a writer, to create blog posts to share my opinions. Users, who are readers, can reader my posts and comment on them. They can also subscribe for updates when there is a new blog post.<br>

Other functionalities that the writer has are: <br>
- deleting a post
- updating a post
- deleting comments that the writer finds insulting or degrading

## User Stories
As a user I would like:
* to view the blog posts submitted
* to comment on blog posts
* to be alerted when a new post is made by joining a subscription. <br>

As a writer I would like:
* to sign in to the blog.
* to create blog posts from the application.
* to delete comments that I find insulting or degrading.
* to update or delete blogs posts I have created.

## Specifications
| Behavior        | Input           | Outcome  |
| ------------- |:-------------:| -----:|
| Register to be a user | Your email : gichurugeorge092@gmail.com <br> Username : gichuru  <br> Password : 5678 | New user is registered |
| User Log in | Your email : gichurugeorge092@gmail.com <br> Password : 5678 | Logged in |
| Display post title | N/A | List of post titles with the writer's name |
| See an entire post | **Click** on a **post's title** | Directed to a page with the post's title, writer's name and comments on the post |
| Comment on a post | **Click Comment** | An authenticated user is directed to a page with a form where the user can create and submit a comment on a post |
| Writer Log in | Your email : writer@login.com <br> Password : writer | Logged in and can access writer's routes |
| Create a Post | **Click Create Post** | An authenticated user with a writer's role is directed to a page with a form where the user can create and submit a new post |
| Delete a comment | **Click delete** for the specific comment | An authenticated user with a writer's role deletes a comment |
| Delete a post | **Click Delete Post** | An authenticated user with a writer's role deletes a post and its comments |
| Update a post | **Click Update Post** | An authenticated user with a writer's role is directed to a page with a form where the user can update the post and submit it |

## Setup/Installation Requirements

* Click [The C Blog] <br/>
  or <br/>
* Copy [The C Blog] and  Paste the link on your prefered browser

This requires internet connection.

## Known Bugs

No known bugs

## Technologies Used
- Python3.10.4
- Flask
- Bootstrap
- Postgres Database
- CSS
- HTML

### License

MIT (c) 2022 **[George Gichuru](https://github.com/GEORGE-GICHURU)**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions.

