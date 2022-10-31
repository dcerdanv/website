# BU website dev repo

This repo will host the development of the new website for the CNIO
Bioinformatics Unit.

The idea is that this will only serve as a development repository: once we
have the first working version of the page we'll create a new repository and
this one will be archived, meaning that the history of this repo will not be
included in the new one.

For the sake of simplicity, in this exercise @tdido will be the code owner and will orchestrate the
merging of all pull requests (PR).

## Development workflow

1. Issue created, discussion about what/how to implement happens there.
2. Issue is assigned to developer (by code owner or developer her/himself).
3. Developer creates new branch (naming: [issue\_number]\_[name] e.g.
   10\_fix\_fontawesome)
4. Developer creates PR based on branch. Discussions on
   code-level implementation details happen here.
5. Once code is ready history is rewitten if necessary and changes are rebased
   into main.

## Preview of the current state of main

The resulting website from the code in main is automatically published to
https://cnio-bu.github.io/website/.

## Using Hugo with the Advance Theme

Hugo Advance is a premium, multi-purpose Hugo theme.

- [Demo](https://hugo-advance.netlify.app/)
- [Documentation](https://www.zerostatic.io/docs/hugo-advance)

![Hugo Advance Theme screenshot](https://www.zerostatic.io/theme/hugo-advance/hugo-advance-screenshot.png)

### Installation

Make sure you have Hugo installed - For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.

### Getting started

Unzip the hugo advance pro zip file. It already contains the Hugo site and theme. All content is ready to go.

Inside the unzipped folder run:

```
hugo
```

Hugo's built-in local server.

```
hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.
