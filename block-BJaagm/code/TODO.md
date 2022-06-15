1. What does thread of execution means in JavaScript? // first the global execution context get created and then as and when reqiures function execution context get created to execute piece of code once done get deleted.

2. Where the JavaScript code gets executed? // Global Execution Context

3. What does context means in Global Execution Context? //It is memory and execution place.

4. When do you create a global execution context. //Every time when we execute JS code.

5. Execution context consists of what all things? //Memory and FEC.

6. What are the different types of execution context? //GEC, FEC.

7. When global and function execution context gets created? // whenever there is need to execute a function.

8. Function execution gets created during function execution or while declaring a function. //while executing


9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.



```js
var user = "Arya";

function sayHello(){
  return `Hello ${user}`;
}

var userMsg = sayHello(user); //first GEC get created, values get saved in memory, FEC will call secondly. asaign the value of var.
```

<!-- Put your image here -->

![](./img/image-name.jpg)



```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount){
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here //first GEC get created, values get saved in memory, FEC will call secondly.then value assignment in memory section

![](./img/image-name.jpg) -->



```js
var age = 21;

function customeMessage(userAge){
  if(userAge > 18){
    return `You are an adult`;
  }else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here --> 

<!-- ![](./img/image-name.jpg) //first GEC get created, values get saved in memory, FEC will call secondly.then value assignment in memory section -->