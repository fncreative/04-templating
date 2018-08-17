![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 04: HTML Templating w/HandlebarsJS
===
## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/simple-validation-of-a-username-with-regex) and follow the submission instructions from Lab 01.

## Lab 04 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)

[Arrow Functions MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## Configuration
_Your repository must include:_

```
04-templating
└── starter-code
└── driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
  └── PULL_REQUEST_TEMPLATE.md
  └── README.md
```

## User Stories and Feature Tasks

*As a user, I want my app to render articles with consistent formatting so that I can visit the site often and have the same experience each time.*

- Include the Handlebars.js CDN in your project to replace the `$.clone()` template.

*As a developer, I want to utilize the Handlebars library to dynamically render the articles using a template so that I can easily edit the way articles are rendered.*

- Convert your existing HTML template into a Handlebars template.
- Update the `Article.prototype.toHtml()` method to utilize the Handlebars template.

*As a developer, I want to utilize modern JavaScript features so that my code is up to date with industry standards.*

- Refactor the functions and methods in youasr code to use ES6 arrow functions when possible.

### Stretch Goal
*As a developer, I want to use Handlebars to build my filters so that my code is more DRY.*

- Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it.

## Documentation
_Your README.md must include:_

```md
# Project Name - 04 - Templating with Handlebars

**Author**: Candice / Daniel
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
The application is now using Handlebars for the templating engine. There is a tmeplate created in the HTML that is being populated on the fly by Handlebars.js

## Getting Started
Download the source code, and fire up live server. Optionally, you could push it to a server.

## Architecture
Handlebars.js / JQuery / HTML / (minimal) CSS

## Change Log
Author: Candice 'canned-ice' Thomas <candicebthomas@gmail.com>
Date:   Fri Aug 17 12:22:13 2018 -0700 - got arrow functions to work

Author: Daniel Frey <dann.frey@me.com>
Date:   Fri Aug 17 10:58:45 2018 -0700 - finialized template

Author: Daniel Frey <dann.frey@me.com>
Date:   Fri Aug 17 10:30:58 2018 -0700 - added handlebars template

Author: Daniel Frey <dann.frey@me.com>
Date:   Fri Aug 17 09:20:50 2018 -0700 - updated readme / index.html / pull request template

Author: Daniel Frey <dann.frey@me.com>
Date:   Fri Aug 17 09:12:19 2018 -0700  - created starter code folder and branch

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource.

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
-->
```
