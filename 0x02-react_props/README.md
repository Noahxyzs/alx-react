In React, `props` are inputs that you pass into components³. They are similar to function arguments in JavaScript and attributes in HTML². Every parent component can pass some information to its child components by giving them props¹. You can pass any JavaScript value through them, including objects, arrays, and functions¹.

Here's an example of how to use props:

```jsx
function Avatar({ person, size }) {
  return (
    <img className = "avatar"
         src = {getImageUrl(person)}
         alt = {person.name}
         width = {size}
         height = {size} />
  );
}

export default function Profile() {
  return (
    <div>
      <Avatar size = {100} person = {{ name: 'Katsuko Saruhashi', imageId: 'YfeOqp2' }} />
      <Avatar size = {80} person = {{ name: 'Aklilu Lemma', imageId: 'OKS67lh' }} />
      <Avatar size = {50} person = {{ name: 'Lin Lanying', imageId: '1bX5QH6' }} />
    </div>
  );
}
```

In this code, the `Profile` component is passing `person` and `size` props to its child component, `Avatar`. The `Avatar` component then uses these props for rendering¹..

Source: Conversation with Bing, 30/10/2023
(1) How to Use Props in React.js - freeCodeCamp.org. https://www.freecodecamp.org/news/how-to-use-props-in-reactjs/.
(2) React Props - W3Schools. https://www.w3schools.com/react/react_props.asp.
(3) Passing Props to a Component – React. https://react.dev/learn/passing-props-to-a-component.
(4) undefined. https://i.imgur.com/1bX5QH6.jpg.
(5) github.com. https://github.com/reactjs/reactjs.org/tree/196edb3022e093ce435f5fc70d1b7eafbc03ad76/beta%2Fsrc%2Fpages%2Flearn%2Fpassing-props-to-a-component.md.
(6) en.wikipedia.org. https://en.wikipedia.org/wiki/React_(software).
