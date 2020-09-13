## Add a Blog Entry

Your website is set up to publish blog entries. In your root folder, you'll find folder named `_posts`. This is where you'll put new blog posts. Open this folder and create a new file.

Each post you make should be in the form `YEAR-MONTH-DAY-title.md`, so for example, `2017-04-21-github-pages-tutorial.md`. You'll also want this `.yaml`-like text near the top.

```
---
layout: post
title: Awesome Blog Post
excerpt: "Why you should read my website"
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: blog
---

Text for your post goes here.
```

This is a great opportunity to practice some Markdown!

## Like Headers

and **bolding**

- and lists

```
## Like Headers

and **bolding**

- and lists
```

Note there's lots of fields you can change: `title`, `excerpt`, `tags`, and `category`. `category` is the most important field, since your posts can either be a `presentation` or a `blog` depending on this field.

When you're done, commit the file into GitHub and confirm that your new blog post is up. You can also delete the sample blog posts so they don't show up on your page.
