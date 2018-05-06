# News-Recommendation-Engine

A real time news recommendation application. The recommendation engine is based on an offline training pipeline for topic modeling (Tensorflow, DNN, NLP).

## Notes

1. `className` instead of `class` in JSX

`class` is a keyword in ES6, using `class` in JSX will cause compile error in React.

2. Use `this.setState` instead of `this.state` to update state:

Although `this.state` can change the value of `state` but it will not trigger UI update in React. So use `this.state` in read-only situation.

3. Use `express-generator`

[[Github](https://github.com/expressjs/generator)], [[Document](https://expressjs.com/en/starter/generator.html)]

The generated app has the following directory structure:

```
.
├── app.js
├── bin
│   └── www
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views (was .jade in order version)
    ├── error.pug
    ├── index.pug
    └── layout.pug

7 directories, 9 files
```