If you take a look at the example site, https://laderast.github.io/academic_site_workshop/ , you'll notice a menu bar at the top. You'll see links to other pages on the site in the menu. We can add and remove these links and their respective pages fairly easily.

Looking at the files in your main directory (which are the contents from `academic_site_workshop/`), the menu is generated based on the files that end in `.md` (except `LICENSE.md` and `README.md`) and have a little YAML entry. If you take a look, you can see `index.md` and `cv.md`. Similarly named links should be in the menu.

To create a new static page that shows up in your menu bar, you need to have the following at the top of your .md file and just change the text for the title.

```
---
layout: page
title: Coursework
---

Text for your page goes here.
```

Try adding a `coursework.md` file in the main directory by pasting the text above and then writing some content, such as classes you've taken. You can add some bullets by using the `+` symbol like this:

```
+ Basket Weaving
+ Cooking
+ GitHub Class
```

Which will show up like this:

+ Basket Weaving
+ Cooking
+ GitHub Class

Then you'll have to edit the `_data/navigation.yml` file to add that menu item. Here's my `navigation.yml` file:

```
# Site navigation links
- title: Home
  url: /

- title: Presentations
  url: /presentations/

- title: CV
  url: /cv/

- title: Blog
  url: /blog/

- title: Workshops
  url: /workshops/
```
Add another `title`/`url` entry for coursework. We named our file `coursework.md`, so the `url` will be `/coursework/`. Make sure that you start out with `-`.

When you're done, commit and load your website again. Confirm that "Coursework" shows up in the menubar. Neat!

If you don't want your blog to show up, you can delete its `title`/`url` entry here.
