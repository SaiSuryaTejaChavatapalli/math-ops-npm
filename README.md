This library contains basic math operations like add, subtract ,multiply and some intermediate operations like divison,power

```
const { MathBasic, MathIntermediate } = require("math-ops-sst");
const mb = new MathBasic();
const add_2_3 = mb.add(2, 3);
const sub_7_3 = mb.sub(7, 3);
console.log(`Addition of 2 and 3 is ${add_2_3}`); //Output:Addition of 2 and 3 is 5
console.log(`Subtraction of 7 and 3 is ${sub_7_3}`); //Output:Subtraction of 7 and 3 is 4
const mi = new MathIntermediate();
const div_10_2 = mi.div(10, 2);
const pow_3_3 = mi.pow(3, 3);
console.log(`Divison of 10 and 2 is ${div_10_2}`); //Output:Divison of 10 and 2 is 5
console.log(`Power of 2 and 3 is ${pow_3_3}`); //Power of 2 and 3 is 27

```
