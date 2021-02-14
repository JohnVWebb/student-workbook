#Daily Journal

##https://github.com/JohnVWebb/js-tests-loops-and-arrays

###Functions

1.What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

    Function declaration
    function name (parameter){
        statements
    }

    Function expression - does not start with function keyword and naming is optional
    let name = function (parameter){
        statements
    }

    Generator function - can be stopped mid execution and called back
    function * name(parameter){

    }

2.What is the difference between Parameters and Arguments?

    parameter is a variable difined in function declaration while arguments are values of that variable being passed into the function.

3.What are higher order functions? Can you provide an example?

    it is a function that takes another function as an argument or returns a function.