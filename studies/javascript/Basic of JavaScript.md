
### JavaScript is used to develop web, mobile application and even used in machine learning and Ai too.

Let's learn first its data types there are primitive datatypes.

- Strings
- Number
- Boolean
- Null
- Undefined
- Symbol

1. In string any text between same symbols are string like - 'hello'  ,  "hello " , `hello there , this is dheeraj ` like that even can use backtick.
2. In number there are integers and floating number negative , zero and positive - -2 ,0 ,1 ,-2.3, 0.0, 2,3 like that.
3. In Boolean it's simply true or false.
4. In undefined if we don't assign value to variable then it's set to be undefined, In function's if it does not return anything then its return undefined.
5. Null in JavaScript means an empty value.

## Checking data types 

```javascript
console.log(typeof 'Asabeneh') // string
console.log(typeof 5) // number
console.log(typeof true) // boolean
console.log(typeof null) // object type
console.log(typeof undefined) // undefined
```


## Variables

> Variables are _containers_ of data. Variables are used to _store_ data in a memory location. When a variable is declared, a memory location is reserved. When a variable is assigned to a value (data), the memory space will be filled with that data. To declare a variable, we use _var_, _let_, or _const_ keywords.

- valid names are as follows
 
```javascript
firstName
lastName
country
city
capitalCity
age
isMarried

first_name
last_name
is_married
capital_city

num1
num_1
_num_1
$num1
year2020
year_2020
```

### Let's assign variables value

```javascript
let name = "dheeraj"
let age = 22
const birthyear = 2000
let hobby = "riding bike" , goal = "developer"
console.log(name , age , birthyear , hobby , goal)
```
