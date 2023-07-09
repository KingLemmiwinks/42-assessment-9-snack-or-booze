### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
  It provides the ability for client-side routing in a web page.

- What is a single page application?
  A website that rewrites the current page instead of loading new pages.

- What are some differences between client side and server side routing?
  Client side routing provides smoother transition between "pages" because there is no full page refresh.
  Server side routing has a faster initial load because it loads smaller, single pages.

- What are two ways of handling redirects with React Router? When would you use each?
  Use a Redirect tag. This causes a new location to override the current location.
  Call .push on a history object. This is used to move the user to a new location after they complete something.

- What are two different ways to handle page-not-found user experiences using React Router?
  Use a catchall route.
  Use a Redirect component.

- How do you grab URL parameters from within a component using React Router?
  useParams hook

- What is context in React? When would you use it?
  Universal data accross the application. This is used when a deeply nested component needs to access data. This avoids passing props from a parent to a child.

- Describe some differences between class-based components and function components in React.
  Class-based components have state initialized in the constructor and use setState to change.
  Class-based components rely on 'this', which can lose context so you may need to bind methods in the constructor.

- What are some of the problems that hooks were designed to solve?
  Hooks remove Duplication and repetition of code and logic within class components or shared components.
  They also remove the need for higher order components and render props. We can use hooks to avoid wrapper hell.