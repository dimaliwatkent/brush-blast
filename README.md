# Project Title

## Links

- Deployment: [Brush Blast](https://dimaliwatkent.github.io/brush-blast/src/index.html)

## Description

A fictional website to showcase sketch arts.This project uses a bootstrap css framework, it showcases the use of bootstrap grid.

## Built with

- Vite
- Bootstrap
- JavaScript

## Installation

```bash
git clone https://github.com/dimaliwatkent/brush-blast.git
npm install
npm run dev
```

## Usage

### Screenshots

![](/docs/screenshot_1.png)
![](/docs/screenshot_2.png)

## Documentation

### Problem 1: Sass

- I previously wrote my css codes in a .scss file because I followed the installation process in the bootstrap docs and it is included there to use a .scss file. When deploying to Github Pages it does not read the scss file. I tried bunch of solutions but in the end I gave up and just used a regular css file.

### Problem 2: Bootstrap Default Styling

- I am having a hard time overwriting the default style in Bootstrap. Sometimes, when a certain code doesn't work, I don't know if it is a problem with my code or it just can't overwrite the style. My simple solution is !important.
