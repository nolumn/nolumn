# Hello! 👋
Welcome to my github account.

```js

const cool = true;

const print = (txt) => {
    console.log(txt ?? 'failed to print')
}

switch (cool) {
    case false:
        console.log('Not cool!')
        break
    case true:
        console.log('Very cool!')
        break    
}

const greet = (name = 'a stranger') => {
  return `Hey! I am ${name != 'a stranger' && (name.slice(0, 1)).toUpperCase() + name.slice(1) || name}, and I am ${cool && `cool` || `not cool`}`
}

(print || console.log)(greet('nolumn'))

```
