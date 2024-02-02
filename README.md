# <img src="https://cdn.simpleicons.org/sass" title="Styling Practice Repo" alt="Styling Practice Repo" width="30"> Styling Practice
Repository created to record my practice learning CSS and SASS with exercises based on the [Udemy Course](https://www.udemy.com/course/advanced-css-and-sass) of [Jonas Schmedtmann](https://www.udemy.com/user/jonasschmedtmann/).

## Table of contents
- [Status](#status)
- [Requirements](#requirements)
- [Setup](#setup)
- [How to run it](#how-to-run-it)
- [Repo structure & what i learned in each exercise](#repo-structure--what-i-learned-in-each-exercise)
- [Other practice repos](#other-practice-repos)

## Status
- Current repo's version is ![Styling practice version](https://img.shields.io/github/package-json/v/nicolasomar/styling-practice?color=success&label=%20&style=flat-square)

### What does that version number mean?
| Number | Meaning |
| ------ | ------ |
| `X.0.0` | How many exercises I have completed |
| `0.X.0` | How many times I made progress on my next exercise |
| `0.0.X` | Dependencies version updates and specific patches while course is not completed |

## Requirements
- [Node](https://nodejs.org/en/download/) `v20.10.0` or above
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) (VisualStudio Code Extension) to launch a development local server.

## Setup
Just in case you want to make your own version with specific releases and version updates.
After cloning the repo, go to the created folder and install the node packages.
```sh
git clone https://github.com/NicolasOmar/styling-practice.git
cd styling-practice
npm run setup:all
```

`setup:all` is the command to install all the projects, but if you want to do it one by one, you can change that last line for one of the following:
| App Setup | Command |
| ------ | ------ |
| All | `npm run setup:all` |
| Natorus | `npm run setup:natorus` |

## How to run it
- Open the `index.html` file on any of exercise's index.
- Click on `Go Live` button on VSCode bottom-right corner.
  - It should open a new windows with your page

## Repo structure & what i learned in each exercise
- Natorus project (`1-natorus` folder)
  - Refreshing some concepts related to coloring and positioning (using `relative` and `absolute`)
  - Handle element properties with `transform` and `translate`
  - Learn to create custom animations using `@keyframes` and `animation`
  - Refreshing some concepts related to pseudo-classes (using `:link` and `:visited`)
  - Learn how to use pseudo-elements like `::after`
  - Learn how to impement a more maintainable styling using relative units like `rem` or `em`
  - Learn about `bem` ([block element modifier](https://getbem.com/)) and implement it in current project status
  - Learn `sass` basics (like variables, nesting, operators, mixins and functions)
  - Install sass compiler with [node-sass](https://www.npmjs.com/package/node-sass) to generate css code using `scss` sintaxis.
  - How to build a sass achitecture based on [7*1 pattern](https://sass-guidelin.es/#the-7-1-pattern) and move the code following the structure.
  - How to create a grid system from scratch (styling like Bootstrap).
  - Learn how to use mixings for repetitive pieces of styling code
  - Learn how to use `calc` function for calculated values (like specific widths)
- Bonus
  - Inclusion of libraries for code formatting and linting ([prettier](https://github.com/prettier/prettier) and [stylelint](https://github.com/stylelint/stylelint))
  - Inclusion of libraries for code review based on git-hooks ([lint-staged](https://github.com/lint-staged/lint-staged) and [husky](https://github.com/typicode/husky))

## Other practice repos
| Node | Angular | GraphQL | React | Typescript | HTML & CSS |
| :---: | :---: | :---: | :---: | :---: | :---: |
| [<img src="https://cdn.simpleicons.org/node.js" title="Node Practice Repo" alt="Node Practice Repo" width="48">](https://github.com/NicolasOmar/node-practice) | [<img src="https://cdn.simpleicons.org/angular" title="Angular Practice Repo" alt="Angular Practice Repo" width="48">](https://github.com/NicolasOmar/angular-practice) | [<img src="https://cdn.simpleicons.org/graphql" title="GraphQL Practice Repo" alt="GraphQL Practice Repo" width="48">](https://github.com/NicolasOmar/graphql-practice) | [<img src="https://cdn.simpleicons.org/react" title="React Practice Repo" alt="React Practice Repo" width="48">](https://github.com/NicolasOmar/react-practice) | [<img src="https://cdn.simpleicons.org/typescript" title="Typescript Practice Repo" alt="Typescript Practice Repo" width="48">](https://github.com/NicolasOmar/typescript-practice) |  [<img src="https://cdn.simpleicons.org/html5" title="HTML and CSS Practice Repo" alt="HTML and CSS Practice Repo" width="48px">](https://github.com/NicolasOmar/html-css-practice) |