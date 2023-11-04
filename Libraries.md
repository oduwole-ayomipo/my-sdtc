# Libraries

This section documents the libraries I am familiar with.

## 01 React

React is a popular JavaScript library for building user interfaces. It is maintained by Facebook and a community of individual developers and companies. React makes it easy to create interactive and dynamic web applications.

### Usage

React is commonly used to build modern web applications, including single-page applications (SPAs) and mobile applications. You can use React to create reusable UI components and manage the state of your application. It follows a component-based architecture, which encourages a modular and structured approach to development.

Example usage:

```jsx
import React from 'react';

function MyComponent() {
  return <div>Hello, React!</div>;
}

export default MyComponent;
```
### Installation

To get started with React, you can create a new React project using `create-react-app`, which is a tool that sets up a new React application with all the necessary configurations.

```shell
npx create-react-app my-react-app
cd my-react-app
npm start
```

### Official Website

You can find more information about React on its [official website](https://react.dev/).

## 02 IconsScout

IconsScout is a popular resource for finding and downloading icons for your projects. It provides a vast collection of icons that can be used in web and mobile applications.

### Usage

IconsScout is used to search and discover icons for various purposes, including adding visual elements to your user interfaces. You can find icons for different categories and styles to match your project's design.

#### Use individual icons

```jsx
import React from 'react';
import UilReact from '@iconscout/react-unicons/icons/uil-react'

const App = () => {
  return <UilReact size="140" color="#61DAFB" />
};

export default App;
```

You can customize icons as below:
```jsx
<Unicons.UilReact size="140" color="#61DAFB" 
```

#### Usage as full Package
```jsx
import React from 'react';
import * as Unicons from '@iconscout/react-unicons';

const App = () => {
  return <Unicons.UilReact />
};

export default App;
```

### Installation
To get start with using Iconscout with react, you could install it in your current react project.

```shell
npm install --save @iconscout/react-unicons
```

