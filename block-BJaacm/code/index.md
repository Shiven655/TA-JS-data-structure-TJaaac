```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->
!hello.png

2. Answer the following with reason:

- `user == newUser;` // output and reason // true, 
- `user === newUser;`// output and reason // true, 
- `user.name === newUser.name;`// output and reason //true,
- `user.name == newUser.name;`// output and reason //true
- `user.sibling == newUser.sibling;`// output and reason// true
- `user.sibling === newUser.sibling;`// output and reason // true
- `user.sibling == allBrothers;`// output and reason // false, 
- `user.sibling === allBrothers;`// output and reason// false
- `brothersCopy === allBrothers;`// output and reason // false
- `brothersCopy == allBrothers;`// output and reason// false
- `brothersCopy == user.sibling;`// output and reason true,
- `brothersCopy === user.sibling;`// output and reason// true 
- `brothersCopy[0] === user.sibling[0];`// output and reason // true,premetive
- `brothersCopy[1] === user.sibling[1];`// output and reason// true, premetive
- `user.sibling[1] === newUser.sibling[1];`// output and reason// true, premetive
