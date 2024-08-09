It's a type of [[Variable]] declaration. It limits the [[Variable]] to not change. Its a constant, so you cannot re-assign the [[Value]], neither the reference.

This is important. 

As you know, we have two types of variables: [[Primitive]] and [[Object]].

When you do this:
`var x = 5`

As 5 is a [[Primitive]], you are assigning that [[Value]] directly to that space.

But if you do this:
``var y = [5]``

What you are doing is this: "Ey, in this space I have defined as `y`, save the reference to the array `[5]`. 

This means that [5] has like a unique id, which is the pointer. that ID is what is being saved on ``y``.

So, when you do

`const y = [5]` instead of using `var`, you are telling the program that you cannot assign another ID (or reference), but you still can change the values of the array.

You can do ``y.push(1)`` . 

So, when you are using const with [[Object]] values, take the previous explanation in consideration.