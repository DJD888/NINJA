## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/DJD888/NINJA/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown
engines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rb"
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List
* 		TABLE OF CONTENTS
* 		Enabling the Engine 
* 		Configuring the Engine
engines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rb"engines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.rengines:
  grep:
    enabled: true
    config:
      patterns:
        no-set-methods:
          pattern: def set_\w+
          annotation: "Don't define methods that start with `set_`"
          severity: minor
          categories: Bug Risk
          content: >
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nunc id
            urna eget libero fermentum bibendum. Duis dapibus, neque vel aliquet
            tincidunt, diam eros tempor neque
          path_patterns:
            - "**/*.r

            - "**/*.rb"
Configuring the Engine
 general:
  build_dir: api

checkout:
  post:
    - git submodule sync
    - git submodule update --init

checkout:
  post:
    - cp ./ci-server/config.yml ./app-server/config.yml

dependencies:
  post:
    - python ./install-packages

database:
  override:
    - mysql -u ubuntu circle_test < my-database-setup.sql

test:
  override:
    - php ./test-suite/run.php --unit-tests

test:
  override:
    - php ./app/run-server.php --daemon
    - php ./test-suite/run.php --unit-tests








HTML formatter, run codeclimate analyze -f html > out.html and inspecting out.html in a browser.


1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DJD888/NINJA/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
