# News-Recommendation-Engine

A real time news recommendation application. The recommendation engine is based on an offline training pipeline for topic modeling (Tensorflow, DNN, NLP).

## Notes

1. `className` instead of `class` in JSX

`class` is a keyword in ES6, using `class` in JSX will cause compile error in React.

2. Use `this.setState` instead of `this.state` to update state:

Although `this.state` can change the value of `state` but it will not trigger UI update in React. So use `this.state` in read-only situation.