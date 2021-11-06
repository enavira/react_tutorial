npx is a package runner tool that comes with npm5.2+


it create react app just create a frontend build pipelines means you can use any backend
you want.
under the hood it uses **Babel** and **webpack**


a lot of tools I can see for now **Next.js** lightweight framework for static and
server-rendered applications build with React. It assumes Node.js as the server env.


**Gatsby** is a the best way to create static websites with React. it outputs the
pre-rendered HTML and CSS to guarantee the fastest load time.


A package manager, such as Yarn or npm. It lets you take advantage of a vast ecosystem of third-party packages, and easily install or update them.
A bundler, such as webpack or Parcel. It lets you write modular code and bundle it together into small packages to optimize load time.
A compiler such as Babel. It lets you write modern JavaScript code that still works in older browsers.


https://www.reactiflux.com/learning looks like a good resource for learning React.

React is declarative, efficient, and flexible javascript library for building user
interfaces.

**components**
component takes in parameters, called props and returns a hierarchy of views to display
via the render method.

the render method returns a description of what you want to see on the screen.
React takes the description and displays the result.

render returns a React element. remember the "JSX" which is a special syntax which makes
these structures easier to write.

each React element is a javascript object that you can store in a variable or pass
around in you program.

passing data through props


```
this.props.value
```

the concept of arrow function

onClick={function() { console.log('click');}} is going to be converted to below
onClick={() => console.log('click')}

to remember things, components use state


in javascript classes you need to always call super when defining the constructor of a
subclass.


since the Square components no longer maintain state, the square components receive values
from the board component. In React terms, the square components are now controlled components.

why immutability is important:
- detecting changes easier
- determining when to re-render in React


# function components
there is a simpler way to write components that only contain a render method and don't have their
own state. instead of defining a class which extends the React.Component, we cna write a function
that takes props as input and returns what should be rendered.
