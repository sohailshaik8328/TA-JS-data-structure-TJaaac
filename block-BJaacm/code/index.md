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
![memory_representation_screenshot](./hello.jpg)

2. Answer the following with reason:

- `user == newUser;` // true because both the  and user is assigned with newUser
- `user === newUser;` // true because both the  and user is assigned with newUser
- `user.name === newUser.name;` // true because both the  and user is assigned with newUser
- `user.name == newUser.name;` // true because both the  and user is assigned with newUser
- `user.sibling == newUser.sibling;` // true because both the  and user is assigned with newUser
- `user.sibling === newUser.sibling;` // true because both the  and user is assigned with newUser
- `user.sibling == allBrothers;` // false because user is an non-primitive and they are different like on is an object and another one is an array
- `user.sibling === allBrothers;` // false because user is an non-primitive and they are different like on is an object and another one is an array
- `brothersCopy === allBrothers;` // false because user is an non-primitive and they are different like on is an object and another one is an array
- `brothersCopy == allBrothers;` // false because user is an non-primitive and they are different like on is an object and another one is an array
- `brothersCopy == user.sibling;` // true because user.sibling is stored in a variable called brothersCopy
- `brothersCopy === user.sibling;` // true because user.sibling is stored in a variable called brothersCopy
- `brothersCopy[0] === user.sibling[0];` // true because user.sibling is stored in a variable called brothersCopy
- `brothersCopy[1] === user.sibling[1];` // true because user.sibling is stored in a variable called brothersCopy
- `user.sibling[1] === newUser.sibling[1];` // true because user.sibling is stored in a variable called brothersCopy
