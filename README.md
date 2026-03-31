# PROJECT-TEMPLATE
This repository contains a template that can be used to seed a repository for a new NRELab open source project.

This template uses the Apache license, as is NRELab's default. See the documentation for instructions on using alternate license.

## How to use this template

1. Clone it from GitHub.
    * There is no reason to fork it.
1. Create a new local repository and copy the files from this repo into it.
1. Modify README.md and docs/CONTRIBUTING.md to represent your project, not the
   template project.
1. Develop your new project!

``` shell
git clone https://github.com/nrelab/PROJECT-TEMPLATE
mkdir my-new-thing
cd my-new-thing
git init
cp -r ../PROJECT-TEMPLATE/* ../PROJECT-TEMPLATE/.github .
git add *
git commit -a -m 'Boilerplate for new NRELab open source project'
```
