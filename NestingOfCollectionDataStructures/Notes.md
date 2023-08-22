```JavaScript
//Define an array of objects
const users = [
  {
    id: 1,
    name: "John",
    age: 25,
    hobbies: ["reading", "painting"],
    address: {
      street: "123 Main St",
      city: "New York",
      country: "USA"
    }
  },
  {
    id: 2,
    name: "Jane",
    age: 30,
    hobbies: ["gardening", "cooking"],
    address: {
      street: "456 Elm St",
      city: "Los Angeles",
      country: "USA"
    }
  }
];
```
note that:
- the key `address` is a nested object.
- we can access this property using dot notation or square bracket notation (e.g., `users[i].address`;)