#

## URH ๐ช

a small simple collections of react hooks

### ๐งช Explore

- [Doc](https://urh-react-hooks.vercel.app/)

### ๐ Prerequisite

- Latest - [React](https://reactjs.org/) ^18

### ๐ช Install

> with npm:

```bash
npm install urh-react-hooks
```

> with yarn:

```bash
yarn add urh-react-hooks
```

### ๐ Usage

```tsx

import { useOnline } from 'urh-react-hooks'

const App = () => {
  const { isOnline } = useOnline()

  return (
    <>
      <div>
        {  
          isOnline ? 
            <p>Online</p>
            :
            <p>Offile</p>
        }
      </div>
    </>
  )
}

export default App
```

### โจ Inspired By

- [vueuse](https://vueuse.org/)
- [usehooks](https://usehooks.com/)

### ๐ฅท

- Written In [TS](https://www.typescriptlang.org/)
- Documented [tsdoc](https://tsdoc.org/)

### ๐ License

[MIT License](https://github.com/vueuse/vueuse/blob/main/LICENSE) ยฉ 2022-PRESENT [Virak Khun](https://github.com/virakkhun)
