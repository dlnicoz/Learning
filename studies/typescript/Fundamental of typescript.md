
## Datatypes in ts and js


### In JavaScript data types are 

- number
- string
- Boolean
- null
- undefined
- object

### In TypeScript data types are

- any
- unknown
- never
- Enum
- tuple

>[!hint] when declaring variable with assigning data with it we don't need to write its type cause typescript auto detect it type and when we hover its shows its annotation 

> example
>
   let sales :number = 232333
   let course :string = "typescript course"
>
   where we don't need to write its type 
>
   let sale = 23323
   let course = "typescript course"
>
   when we try to change any variable its value typescript will eventually detects it and warn us
>
   sale = true  that's will sure give error in compile time means in development time only .


> [!tip]  When we don't declared any type and nor assigning value to it ts implicitly assign the any type to it .  
> Solution to it write it's type to any that's bad practice if you know its predictable type then use that only

