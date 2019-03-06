# useshake

**Installation**

```
npm install --save useshake
```

**Usage**

```js
import { useShake } from 'useshake'

function Home() {
  const shake = useShake({
    threshold: 15,
    timeout: 1000,
    restartDelay: 2000
  })

  const shook = shake ? 'Shook!' : 'Shake it'

  return <p>{shook}</p>
}

export default Home
```
