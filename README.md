# Javascript-Default-Function-Parameters

`Default Function Parameters` serve as initialised arguments that represent default values, that can be used in case no arguments are passed when calling a function.


```
const getSum = (a = 1, b = 1) => {
  const sum = a + b;

  console.log(`The sum of ${a} and ${b} is ${sum}`);
};

getSum()
///Will print:
The sum of 1 and 1 is 2

getSum(2)
///Will print:
The sum of 2 and 1 is 3

getSum(2,5)
///Will print:
The sum of 2 and 5 is 7
```
