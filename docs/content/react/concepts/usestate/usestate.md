---
Title: 'useState'
Description: 'A React Hook used to manage state in functional components.'
Subjects:
  - 'Web Development'
Tags:
  - 'React'
  - 'Hooks'
CatalogContent:
  - 'learn-react'
---

## useState

The `useState` hook is used to manage state in React.

### Syntax

```javascript
const [state, setState] = useState(initialValue);

EXAMPLE:
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <button onClick={() => setCount(count + 1)}>
      Count: {count}
    </button>
  );
}
