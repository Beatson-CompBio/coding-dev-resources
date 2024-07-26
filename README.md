# Software development resources

This document contains a collection of resources for software development. The resources are organized by programming language and topic. The goal of this repository is to provide a comprehensive list of resources for software development, including tutorials, best practices, and possibly tools.

## Table of contents

<details>
<summary><a href="#bash">Bash</a></summary>

- [Coding style guide](#coding-style-guides)

</details>

<details>
<summary><a href="#javascript">JavaScript</a></summary>

- [Coding style guides](#coding-style-guides)

</details>

<details>
<summary><a href="#python">Python</a></summary>

- [Coding Style](#coding-style)
- [Python package development guides](#python-package-development-guides)

</details>

<details>
<summary><a href="#r">R</a></summary>

- [Coding Style](#coding-style-guide)
- [R package development guides](#r-package-development-guides)
- [shiny_resources](#shiny_resources)

</details>

## Bash

### Coding style guides

- [Google's Shell Style Guide](https://google.github.io/styleguide/shellguide.html)

## JavaScript

JavaScript(JS) is the most popular programming language and has many style guides developed by multiple organisations. To keep things consistent, we recommend using Google's JavaScript style guide.

### Coding style guides

- [Google's JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)

## Python

### Coding style guides

While PEP 8 is the most comprehensive style guide for Python, we recommend using Google's python style guide. It is more concise, easier to follow, and covers all the important aspects of writing clean code.

- [Google's Python Style Guide](https://google.github.io/styleguide/)

In case you are interested in PEP 8, you can find it here:

- [PEP 8](https://peps.python.org/pep-0008/)

### Python package development guides

The following resources are useful for developing Python packages:

As of 2021, the most comprehensive guide for developing Python packages is the `py-pkgs` guide. It covers all the important aspects of package development, including the structure of a package, testing, documentation, and distribution.
- [Package development guide(latest)](https://py-pkgs.org/01-introduction)

The following resources are also useful for developing Python packages with setuptools:
- [Package development guide(older)](https://packaging.python.org/en/latest/overview/)


## R

### Coding style guide

For R programming, we recommend using the Tidyverse style guide which was used to develop Google's R style guide.

- [Tidyverse style guide](https://style.tidyverse.org/)

### R package development guides

- [Bioconductor package development guide](https://contributions.bioconductor.org/index.html)
- [R package development guide](https://r-pkgs.org/)

### shiny_resources

Any useful resources for the design and deployment of shiny apps

#### Design

-  [General best practices](https://mastering-shiny.org/scaling-intro.html)
-  [Layouts](https://shiny.posit.co/r/articles/build/layout-guide/)
-  [Pretty shiny widgets](https://shinyapps.dreamrs.fr/shinyWidgets/)
-  [Improved user feedback/error messages](https://merlinoa.github.io/shinyFeedback/)
-  [Cheatsheet](https://shiny.posit.co/r/articles/start/cheatsheet/)
-  [Production-ready shiny guide](https://engineering-shiny.org/index.html)
-  [Writing better error messages](https://shiny.posit.co/r/articles/improve/validation/)

#### Deployment into shinyapps.io server

-  [Storage](https://docs.posit.co/shinyapps.io/guide/storage/)
-  [Accessing external databases](https://docs.posit.co/shinyapps.io/guide/applications/#accessing-databases-with-odbc)
-  [Security and Compliance of shinyapps.io](https://docs.posit.co/shinyapps.io/guide/security_and_compliance)
-  [shinyapps.io: ubuntu default packages](https://docs.posit.co/shinyapps.io/guide/appendix/#default-system-packages)
-  [Be aware that you should not have an explicit install.packages() call within your ui.R or server.R files.](https://docs.posit.co/shinyapps.io/guide/getting_started/#using-your-r-packages-in-the-cloud)
