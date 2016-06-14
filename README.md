# Hello Code School

This is a sample project to test out how projects work at Code School.

[![Build Status](https://travis-ci.org/codeschool/HelloCodeSchoolProject.svg?branch=master)](https://travis-ci.org/codeschool/HelloCodeSchoolProject)

# Forking

To get started, fork this repository to your account and clone it down locally. If you want, you can also try doing this completely from GitHub!

# Tasks

Once you've forked this repository, go ahead and make the following changes to the `index.html` file.

* Change the `title` to your Code School account name.
* Add an `h1` saying "Hello, Code School!".
* Create a `ul` element with at least 2 `li` elements.
* In these `li` elements, list out what you want to learn.

Once you've completed all of the tasks, go ahead and commit those to your fork.

# Running Tests Locally

You don't need to run and of the tests locally -- they'll all run when you submit your project. If you're an overachiever and want to try running the tests locally, here's what you'll need to do.

First off, install [node.js](https://nodejs.org/en/) locally. Next you'll need to run a few commands from this folder.

```
$ npm install
$ npm test
```

If everything is working, you should see something like this:

```
HelloCodeSchoolProject (answer) $ npm test

> hello-codeschool-project@1.0.0 test /Users/adam/code/projects/HelloCodeSchoolProject
> mocha test/



  Your HTML Page
    ✓ should have a different title
    ✓ should have a different h1
    ✓ should have a ul
    ✓ should have at least 2 li elements


  4 passing (306ms)
```

# Submission

In order to submit this project, create a pull request from your fork back to the "codeschool/HelloCodeSchoolProject" project. After you see your pull request green, everything is passing!

# Making it Public

Once all tests are passing, try pushing your master branch up to the `gh-pages` branch -- this will make your webpage available on the web! Here's a command to do that:

```
$ git push origin master:gh-pages
```

This will make your `index.html` file available at the URL:

`http://<username>.github.io/HelloCodeSchoolProject/`

For instance, our `answer` branch is available at the url [http://codeschool.github.io/HelloCodeSchoolProject/](http://codeschool.github.io/HelloCodeSchoolProject/).

# Submitting Back to Code School

TBD
