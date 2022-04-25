# Property Access with Destructuring

- By wrapping properties of an object with curly braces we can pull whatever properties of objects and make them variables

```javascript
const user = {
  name: "Reed",
  username: "Reedbarger",
  email: "reed@gmail.com",
  details: {
    title: "Programmer"  
  }  
};

const { username, email } = user;

function displayUser() {
  console.log(`username: ${username}, email: ${email}`);  
}

displayUser()
```
