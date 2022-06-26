---
title: Meu primeiro Post
date: "2022-06-25"
description: "Esse é meu primeiro post no blog, vamos ver se vai dar certo!"
timeRead: 5
---

```javascript
import { useState } from 'react';

export default function App() {
  let [color, setColor] = useState('red');
  return (
    <div>
      <input value={color} onChange={(e) => setColor(e.target.value)} />
      <p style={{ color }}>Hello, world!</p>
      <ExpensiveTree />
    </div>
  );
}

function ExpensiveTree() {
  let now = performance.now();
  while (performance.now() - now < 100) {
    // Artificial delay -- do nothing for 100ms
  }
  return <p>I am a very slow component tree.</p>;
}

```

`node.js` or `parseInt()` or `useState()`

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```