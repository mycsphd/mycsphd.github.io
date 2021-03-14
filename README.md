# mycsphd.github.io

Computer Science Ph.D. Information for Future Students.

## How to add a new post

1. create a new markdown file in the _post directory.
2. naming convension is date + title + .md.
3. Create Front matter for the post
    - first line and last line is '---'
    - in the middle add
        - layout: post
        - title: post title
        - tag: tags you want to add
        - category: if you want to add this post to a specific category page (so that they can be accessed from the side bar pages like "Info Session"). Available options are in the Category folder. Check the front matter in each markdown file to see its category.
        - author: contributors.
4. contents behind the front matter.

## How are the pages in the sidebar being added?
1. markdown file in root folder
    - add the following to the front matter, just like the 2_wiki.md file
        - layout: page
        - title: Page name you want to show in the side bar
        - sidebar_link: true  (if you forget this, it won't be added to the side bar)
2. markown file in the Category folder
    - add the following front matter, just like the Category/1_faq.md
        - layout: category
        - title: Title for this page that will appear in the sidebar
        - category: category_name that will be used to link the category specified by posts
3. Order in the sidebar
    - markdown file in the root folder always shows before those in Category folder in sidebar
    - within each class, they are sorted by number in the file name.

## Important Attributes
_config.yaml: cite name, cite description.
sidebar color: assets/css/main.sass
