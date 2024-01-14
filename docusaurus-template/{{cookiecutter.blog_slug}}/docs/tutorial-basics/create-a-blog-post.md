---
sidebar_position: 3
---

# Create a Blog Post

Docusaurus creates a **page for each blog post**, but also a **blog index page**, a **tag system**, an **RSS** feed...

## Create your first Post

Create a file at `blog/2021-02-28-greetings.md`:

```md title="blog/2021-02-28-greetings.md"
---
slug: greetings
title: Greetings!
authors:
  - name: Thang Bui Quang
    title: Developer of Projectopia
    url: https://github.com/thangbuiq
    image_url: https://github.com/thangbuiq.png

  - name: Chinh Dinh Minh
    title: Developer of Projectopia
    url: https://github.com/lelouvincx
    image_url: https://github.com/lelouvincx.png
tags: [greetings]
---

Congratulations, you have made your first post!

Feel free to play around and edit this post as much you like.
```

A new blog post is now available at [http://localhost:3000/blog/greetings](http://localhost:3000/blog/greetings).
