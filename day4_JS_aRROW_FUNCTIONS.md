// Arrow function is a consise way to write function 
// expressions good for simple functions that you 
// use only once(parameter) => some code

/* normal function
function hello() {
    console.log("hello");
}

hello(); */
const hello = () => console.log("hello"); //if you have no parameters leave the parantesis untouched
   //rember to add the "=" before the parentesis

   
const hello = (name, age) => {console.log(`hello ${name}`)
 //if you have no parameters leave the parantesis untouched, but if you have rember to add a place holder for the parameter and it should be a simgel parentesis
                            console.log(`You are ${age}yrs old and `)
                            console.log(`you  shouldn't waste your time `)};//rember to add the "=" before the parentesis
hello("James", 23); //parsing the parameter as arguement 

//setTimeout function 
setTimeout(hello, 3000); //it accepts a callback and trhe guving amout of time we are going to execute this code
 //after 3s
function hello(){
    console.log("Hello");
}

// Arrow function is a consise way to write function 
// expressions good for simple functions that you 
// use only once(parameter) => some code

setTimeout(function(){
    console.log("Hello");
}, 3000); //it accepts a callback and trhe guving amout of time we are going to execute this code
//in place of a callback i could use a function expression\
//just polace the function where the callback OUGHT TO BE
//remember we dont need a name for a funciton expression 


