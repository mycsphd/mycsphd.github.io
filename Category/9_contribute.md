---
layout: category
title: Contributing
category: contributing
---

## What to Contribute

If you have an idea for blog post or page that you think might be useful to
people navigating their way to a Ph.D. in CS, we'd love to hear about it.

Some things to keep in mind:

* Despite the existence and usefulness of [school rankings]({% post_url 2021-03-10-school-rankings %}), the site does not promote some schools over others.
* The site loves hearing about your _first-hand_ experience getting, advising, and having a Ph.D. in CS.
* The site loves hearing about useful/relevant data about Ph.D. and analysis thereof.

All contribution are made under the <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Providing Links to Resources

If you have a resources (e.g., a blog post you've written) that you think would
be useful, please submit a pull request that adds the appropriate link, and we
will take a look.

## How to Contribute

There are two mechanisms you can use to help us improve this web site:

1.  Is something broken?  Submit a [bug report](https://github.com/mycsphd/mycsphd.github.io/issues).
2.  Is it something you can fix?  Submit a [pull request](https://github.com/mycsphd/mycsphd.github.io/pulls).
3.  Do you want to write an article or blog post?  Read on:

## Contributing an Article or Blog Post

We welcome contributions to the site.  If you have an idea for an article, please send email to swanson@cs.ucsd.edu to discuss what you're interested in writing and how it would fit into the site.

Once that's done the mechanics are like this:

1. Clone a copy of the site on github: {{ site.hydeout.repo }}.
2. Copy `_drafts/article-template.md` to `_drafts/good-short-name-for-your-article-not-like-this.md`
3. Populate it with interesting advice and information based on your experience, expertise, or research.  Write in [markdown](https://commonmark.org/help/).
4. If you need images (we love graphs!) put the images in `assets/img` and name them in a short descriptive way.
5. Commit and push everything.

We have found [hackmd.io](http://hackmd.io) to be very useful for providing
feedback on articles.  It can pull from github and is free for collaboration.
Setup a collabortive version of your article:

1. Visit [hackmd.io](http://hackmd.io) and create an account.
2. Click on the three dots on the right of the green button to "import a file from GitHub".
3. Click "authorize more repos".  It will take you to GitHub.  Give hackmd access to your fork of mycsphd.io.
4. Select your file, and click 'Pull'.
5. Click "apply all changes"

You can edit your article in WYSIWYG.  It also provides a commenting mechanism,
which is very handy.

You can preview your work locally.  The `Makefile` will start a local web
server that serves the site.  Your draft article will (confusingly, perhaps)
appear in the [Blog]({{site.baseurl}}{% link _blog.html %}).

Let swanson@cs.ucsd.edu know that your article is ready and we'll take a look.
Once everything looks good, we'll have you generate a pull request to merge it
into the site.






