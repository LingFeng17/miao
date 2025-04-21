# [React](https://react.dev/) &middot;[![githublisence](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/facebook/react/blob/main/LICENSE) [![npm version](https://camo.githubusercontent.com/9b33f253eb1c389ad196feb8b398d00d23fad5de7391fb9bb1f951fd405b62bd/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f72656163742e7376673f7374796c653d666c6174)](https://www.npmjs.com/package/react) [![runtimebuildandtest](https://github.com/facebook/react/actions/workflows/runtime_build_and_test.yml/badge.svg)](https://github.com/facebook/react/actions/workflows/runtime_build_and_test.yml) [![complier](https://github.com/facebook/react/actions/workflows/compiler_typescript.yml/badge.svg?branch=main)](https://github.com/facebook/react/actions/workflows/compiler_typescript.yml) [![prs](https://camo.githubusercontent.com/d88d8d77fa79e828eea397f75a1ebd114d13488aeec4747477ffbd2274de95ed/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e2e737667)](https://legacy.reactjs.org/docs/how-to-contribute.html#your-first-pull-request)

React is a JavaScript library for building user interfaces.

* **Declarative:** React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right components when your data changes. Declarative views make your code more predicatable, simpler to understand, and easier to debug.
* **Component-Based:** Build encapsulated components that manage their own state, then compose them to make complex UIx. Since component logic is written in JavaScirpt instead of templates, you can easily pass rich data through your app and keep the state out of the DOM.
* **Learn Once, Write Anywhere:** We don't make assumptions about the rest of your technology stack, so you can develop new features in Recat without rewriting existing code. React can also render on the server using [Node](https://nodejs.org/en) and power mobile apps using [React Native](https://reactnative.dev/).

[Learn how to use React in your project](https://react.dev/learn).

## Installation

React has been designed for gradual adoption from the start, and **you can use as little or as much React as you need:**

* Use [Quick Start](https://react.dev/learn) to get a taste of React.
* [Add React to an Existing Project](https://react.dev/learn/add-react-to-an-existing-project) to use as little or as much React as you need.
* [Create a New React App](https://react.dev/learn/start-a-new-react-project) if you're looking for a powerful JavaScript toolchain.

## Documentation

You can find the React documentation [on the website](https://react.dev/). 

Check out the [Getting Started](https://react.dev/learn) page for a quick overview.

The documentation is dicided into several section:

* [Quick Start](https://react.dev/learn)
* [Tutorial](https://react.dev/learn/tutorial-tic-tac-toe)
* [Thinking in React](https://react.dev/learn/thinking-in-react)
* [Installation](https://react.dev/learn/installation)
* [Describing the UI](https://react.dev/learn/describing-the-ui)
* [Adding Interactivity](https://react.dev/learn/adding-interactivity)
* [Managing State](https://react.dev/learn/managing-state)
* [Advanced Guides](https://react.dev/learn/escape-hatches)
* [API Reference](https://react.dev/reference/react)
* [Where to Get Support](https://react.dev/community)
* [Contributing Guide](https://legacy.reactjs.org/docs/how-to-contribute.html)

You can improve it by sending pull requests to [this repository](https://github.com/reactjs/react.dev).

## Examples

We have several examples [on the website](). Here is the first one to get you started:

```javascript

import { createRoot } from 'react-dom/client';

function HelloMessage ( { name }) {
    return <div>Hello {name}</div>;
    }

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />);
```
This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax;[we call it JSX](https://react.dev/learn#writing-markup-with-jsx). JSX is not required to use React, but it makes code more readable, and writing it feels like writing HTML.

## Contributing

The main purpose of this reponsitory is to continue evolving React core, making it faster and easier to use.
Development of React happens in the open on GitHub, and we are grateful to the community for contributing bugfixes and improvements.Read below to learn how you can take part in improving React.


### [Code of Conduct](https://code.fb.com/codeofconduct)

Facebook has adopted a Code of Conduct that we expect project participants to adhere to. Please red [the full text](https://code.fb.com/codeofconduct) so that you can understand what actions will not be tolerated.

### [Contributing Guide](https://legacy.reactjs.org/docs/how-to-contribute.html)

Read our [contuibuting guide](https://legacy.reactjs.org/docs/how-to-contribute.html) to learn about our development process, how to propose bugfixes and improvements, and how to build and test your changes to React.

### [Good First Issues](https://github.com/facebook/react/labels/good%20first%20issue)

To help you get your feet wet and get you familiar with our contuibution process, we have a list of [good first issues](https://github.com/facebook/react/labels/good%20first%20issue) that contain bugs that have a relatively limted scope. This is a great place to get started.

### Licese

Recat is [MIT licensed](https://github.com/facebook/react/blob/main/LICENSE).
