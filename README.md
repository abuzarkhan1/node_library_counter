# Introduction

Counter Is JavaScript Library For Counting

# Installation

```
npm install counter-abuza
```

# Usage

```js
import { useCounter } from "counter-abuzar"
```

# Then

```js
import { useCounter } from "counter-abuzar"
const App = () => {
  const {count,increment,decrement} = useCounter();
  return (
    <div>
      <button onClick={increment}>+</button>
      <h3>{count}</h3>
      <button onClick={decrement}>-</button>
    </div>
  )
}
export default App
```

# Contribute

if you would like to contribute, you are welcome, Clone repo and open pull request.