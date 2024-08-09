

when you are declaring a catch method, you are declaring a variable. It is a block scoped variable that contains the error.
````
try {
    someError();
}
catch (err) {
    console.log(err);
}
````
