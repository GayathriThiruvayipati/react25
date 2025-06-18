# Notes

- files that can be generated shouldn't be pushed to github repository.

# Parcel

1. Dev Build
2. Local Server
3. HMP = Hot Module Replacement
4. File Watching Algorithm - written in c++
5. Caching - Faster Builds
6. Image Optimization
7. Minification
8. Bundling
9. Compress
10. Consistent Hashing
11. Code splitting
12. Differential bundling - support older browsers
13. Diagnostic
14. Error Handling
15. HTTPS
16. Tree Shaking - remove unused code
17. Different dev and prod bundles

# JSX

- transpiled before it reaches JS Engine by whom? => by PARCEL (does parcel does it on its own? NO) => Babel

- JSX transpiled to => ReactElement(object) => when we render this into the DOM, then it becomes HTML Element.

- Everything in react is a component.
- what is a component? There are two types of components:

  1. class based components - OLD WAY OF WRITING CODE
  2. functional components - NEW WAY

- What is React Functional Component? - It is just a normal javascript function which returns JSX Element.
- Whenever you create a functional component, name it with a capital letter otherwise you get an error. It is a react way of understanding its a component.

- Component Composition - component inside a component is called component composition.
