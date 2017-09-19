# Udacity-ES6-Programming-Quiz-Destructuring-Arrays-1-3-
/*
 * Programming Quiz: Destructuring Arrays (1-3)
 *
 * Use destructuring to initialize the variables `one`, `two`, and `three`
 * with the colors from the `things` array.
 */

const things = ['red', 'basketball', 'paperclip', 'green', 'computer', 'earth', 'udacity', 'blue', 'dogs'];
let [a,,,b,,,,c]=things;
const one = a;
const two = b;
const three = c;

const colors = `List of Colors
1. ${one}
2. ${two}
3. ${three}`;


console.log(colors);
