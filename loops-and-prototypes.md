## For-of loop

The for-of loop is a new loop introduced in JavaScript. It is not supported in Internet explorer and works well in other modern browsers. The for-of loop has a clean syntax and is used for iterating over arrays and strings.

The for-of loop is a great way to iterate over arrays or objects but if you need to iterate over an array while also keeping in mind the index of the values then the regular for loop is what you require

```js
let fruitsBasket =["apple","banana","orange","mango","pineapple"]
for(let fruit of fruitsBasket){ console.log(fruit); }
```

## For-in loop

The for-in loop is used to iterate over the properties or keys in an object.

The main difference between the for-of and the for-in loop is that the for-of loop iterates over the actual value of the array or object that it's being iterated over and the for-in loop only iterates over the keys of the array or object.

```js
const users = {
bob : 22,
sally: 25,
jake: 33 }
for(let user in users){
console.log(user);
console.log(users[user]); }
```

## Prototypes

According to the MDN docs: 

> Prototypes are the mechanism by which JavaScript objects inherit features from on another.

Each object can have a prototype which acts as a template. Certain objects like arrays don't have methods like pop or push. These methods are stored in the __proto__ property that references all the methods from the arrays prototype.
