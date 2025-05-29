# Functions-and-Recursion-solution

Download Here: [Functions and Recursion solution](https://jarviscodinghub.com/assignment/functions-and-recursion-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Part I: Functions
Revise assignment 3 to include a separate validation() function. The validation() function should include all statements to reset the error output messages (span tags), retrieve the user input, and call calcTotal() function when all inputs are valid. The calcTotal () function should be called only if there are no validation errors. The calcTotal () function will calculate the order total and then display the order total on the output division.
Part II: Arguments Object
Briefly explain the purpose of the following function and how it works. What is the output?
function find() {
var i, m = 0;
for (i = 0; i < arguments.length; i++) { if (arguments[i] > m) {
m = arguments[i];
}
}
return m;
}
document.getElementById(“output”).innerHTML = find(4, 400, 45, 60, 123, 211);

Part III: Recursion
Briefly explain the purpose of the following recursive function and how it works. What is the output?
function recursiveFunc(num)
{
if (num === 0) {
return 1;
}
else {
return (num * recursiveFunc(num – 1));
}
}

var result = recursiveFunc(15);
document.getElementById(“output”).innerHTML = result;

Save your answers of Part I & II in a text file named Assignment4.txt. Include the file as part of your assignment 4 submission.
