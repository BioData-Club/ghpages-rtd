# Adding Reveal.js Presentations

In Jekyll Academic presentations are actually set up as posts, and live in the same _posts folder as your blog posts. They also must use the same file naming convention as posts (`yyyy-mm-dd-title.md`). The main difference between a blog post and a Reveal.js presentation is the layout and category used in the YAML front matter.

If you wish to begin your Reveal.js presentation with a blank markdown file, you must paste the following YAML front matter at the very beginning of your file.

```yaml
---
layout: slide
title: Add Your Title Here
excerpt: "Add an excerpt here, the excerpt will appear underneath the blog title"
modified: 2016-01-13 20:41:38
tags: [intro, beginner, jekyll, tutorial]
comments: true
category: presentation
---
<section data-markdown>
# Add Reveal.js slide content here, following the Reveal.js format
</section>
```

Note that Reveal.js presentations must use `slide` as the `layout` and `presentation` as the `category`.
