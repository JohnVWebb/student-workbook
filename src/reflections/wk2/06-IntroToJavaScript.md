#daily Journal

##https://github.com/JohnVWebb/js-test-basics

###Intro To Javascript

1.What is Scope ?

    Scope refers to where certain variables may be available to use within your code.

2.What is Hoisting ?

    variables and functions that are declared later in the code are moved to the top of their respective scopes and executed in that order.

3.In what cases might you use let vs const vs var?

    const - will be used in the event you need a variable that will never change.

    let - is the current standard for javascript variables because they have a local scope instead of global you don't run into issues of variables updating across scopes when not intended.

    var - is the original method of declaring variables in javascript. var has a global scope outside of a function and local within functions. this can cause issues with variables you intend to be local interacting with global variables.