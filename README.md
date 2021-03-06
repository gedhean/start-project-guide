# Start project guide

A simple guide to use when start a new project.

## Getting Started

Let's prepare the environment.

### Prerequisites

- git
- npm

### Initialize a git repository 

```
mkdir my-project 
cd my-project

git init
```

### Configure npm

This is a script to configure npm.

```
npm set init-author-name "Gêdhean Alves Vieira"
npm set init-author-email "gedhean1@gmail.com"
npm set init-license "MIT"

npm get init-author-name
npm get init-author-email
npm get init-license

```

### Add gitignore

```
npm install gitignore -g

gitignore -types

gitignore type

```

### Add package.json


```
npm init

```
### Use a Style Guide

See [JSCS](http://jscs.info/).
See [Editor Config](editorconfig.org).

## Important files

### REABME.md

See [How to write a README.md file](http://jfhbrook.github.io/2011/11/09/readmes.html).

### Contributing

Please read [CONTRIBUTING.md]() for details on our code of conduct, and the process for submitting pull requests to us.

### License

See [open source licenses](https://opensource.org/licenses).

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/gedhean/start-project-guide/blob/master/LICENSE) file for details
