1. Rendering is creating the element the component is responsible for creating,
mounting is the process of appending that element to the DOM.
2. Props are attributes that the component possesses, little custom bits of data that
are passed down to it from a parent component that it is responsible for
3. They receive props when they are passed down from a parent component
4. It's not possible to change props once they are set
5. When one wants to set a prop for a component, and have that prop be subject to
changes.
6. The render method
7. The JSX that will render the element that the component is responsible for creating
8i. If a component is being created by another component, it is a child. If it
creates a component in its render method, it is a parent. It can be both.
8ii. It does not.
9. this.setState()
10. A change in the component's this.state attribute, specifically in the key
that is called upon in the setState method
11. A controlled form is both set and updated by a compoenent. An uncontrolled form
must receive info the from DOM, then send any changes back to the DOM.
12. Like 2 and a half
