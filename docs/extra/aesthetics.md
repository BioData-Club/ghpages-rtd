# Aesthetics & Appearance with "Layouts"

One of the fundamental elements of Jekyll is the ability to utilize different layouts for different types of pages.  The layouts are found in the `_layouts` folder. These are .html files that drive the layout of any particular page.  For example the `slide` layout contains all of the necessary includes to power Reveal.js slides.  The current available layouts in Jekyll Academic are:

- `home` - This layout is the layout for the homepage of your website. It automatically includes your 5 most recent blog posts in the space to the right of the social media section.
- `page` - This layout is used for any individual page, like the "About Me" page.  It is a blank page that can be formatted using Markdown.
- `post-index` - This layout is used on the blog archive.  It lists every blog post chronologically - separated by year.
- `post` - This layout is used for blog posts.  It includes a few more functionality elements than the `page` layout.
- `resume` - This layout is used for the Resume page.
- `presentation-post-index` - This layout is identical to the `post-index` layout except it is used on the presentations index to post all presentations you have on your site in one location, chronologically.
- `slide` - This layout is used for creating a Reveal.js slide deck.
