# @dougkulak/substrate-abstract
Abstract classes collection.  
Typedoc: [https://dougkulak.github.io/substrate/abstract/](https://dougkulak.github.io/substrate/abstract/)

### Install
```bash
yarn add @dougkulak/substrate-abstract -D
npm add @dougkulak/substrate-abstract -D
```

### Usage
```typescript
import { AbstractError } from '@dougkulak/substrate-abstract'

class CustomError extends AbstractError {
  foo: string
  constructor(args) {
    super(...args)
    
    this.foo = 'bar'
  }
}
```
