It's a type of [[Variable]] in [[Javascript]]. 

It differs from var in the Block Scope. 
When you declare a [[Variable]] using let, the scope of that [[Variable]] will be the closest closure.


For example:
```

if (adult){
var name = "Maria"
let lastname = "Yeyu"
}


console.log(name) //Maria

console.log(lastname) //Error!

```

As you can see, the let declaration is inside the if statement, so it doesn't exists outside of it.

**Considerations:**
- If you use var or let inside a function and then you call that function, if you try to access those variables from outside the function, it will not work, as the scope of that function affects also to var. 

