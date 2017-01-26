## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/DJD888/NINJA/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
$ ruby -rubygems -e 'require "jekyll-import";
    JekyllImport::Importers::MT.run({
      "engine"   => "mysql", # "postgres" is also supported
      "dbname"   => "name",
      "user"     => "myuser",
      "password" => "mypassword",
      "host"     => "myhost",
      "blog_id"   => nil,  # Set to specific ID to iimport just one blog
      "categories" => true, # Set to false to not save categories to front matter
      "src_encoding" => "UTF-8",
      "dest_encoding" => "UTF-8",
      "comments" => true
    })'
Posts will be generated and placed in _posts directory.
The only required fields are dbname and user. password defaults to "" and host defaults to "localhost".
comments, which defaults to false, control the generation of comment. If comments set to true, posts will be generated and placed in _comments directory.
All of the posts and comments will include post_id in YAML front matter to link a post and its comments.
To include imported comments as part of a post, use the yet to merge fork of mt-static-comments to include statically generate comments in your post. Fork and provide feedback if necessary.

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DJD888/NINJA/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact$ ruby -rubygems -e 'require "jekyll-import";
    JekyllImport::Importers::MT.run({
      "engine"   => "mysql", # "postgres" is also supported
      "dbname"   => "name",
      "user"     => "myuser",
      "password" => "mypassword",
      "host"     => "myhost",
      "blog_id"   => nil,  # Set to specific ID to iimport just one blog
      "categories" => true, # Set to false to not save categories to front matter
      "src_encoding" => "UTF-8",
      "dest_encoding" => "UTF-8",
      "comments" => true
    })'
Posts will be generated and placed in _posts directory.
The only required fields are dbname and user. password defaults to "" and host defaults to "localhost".
comments, which defaults to false, control the generation of comment. If comments set to true, posts will be generated and placed in _comments directory.
All of the posts and comments will include post_id in YAML front matter to link a post and its comments.
To include imported comments as part of a post, use the yet to merge fork of mt-static-comments to include statically generate comments in your post. Fork and provide feedback if necessary.

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
