# JavaScript Course In One Video
## _by Shalaby Code Lab_

# Course Content

- DataType
- Variables
- Comments
- ArithmeticOperations
- LogicalOperators
- IfConditions
- NestedIF
- SwitchStatement
- Arrays
- ForLoop
- WhileLoop
- DoWhileLoop
- Function
- ArrowFunction
- Object

## What is javascript
    JavaScript is a client-side programming language used to create dynamic interactions in app,
    game and web development. Commonly represented as JS, this language is considered one of the
    core technologies of the web in conjunction with HTML and CSS.
    Developers use JavaScript to bring a webpage to life, as it transforms
    an otherwise static page into one that responds to user engagement,
    livens up the page with motion, and displays real-time, variable,
    and personalized content.
    
## Uses Of JavaScript
- Mobile Apps
- Interactive maps
- Web
- Virtual reality
- Booking systems
- Games
- Animations
- And More More More 

# How Is JavaScript Work

>>  Browser => How JavaScript Work In HTML Files
>> NodeJs => How JavaScript Work In NodeJs Server Local

# Basics JavaScript

##  DataType

```javascript
                // Numbers:
                let length = 16;
                let weight = 7.5;

                // Strings:
                let color = "Yellow";
                let lastName = "Johnson";

                // Booleans
                let x = true;
                let y = false;

                // Object:
                const person = {firstName:"John", lastName:"Doe"};

                // Array object:
                const cars = ["Saab", "Volvo", "BMW"];

                // Date object:
                const date = new Date("2022-03-25");
```

## Variables

```javascript
            var x = 5;
            let y = 6;
            const z = x + y;
```

## Comments

```javascript
            //this is Comments
            /*
            This Multibli comment
            */
```

## ArithmeticOperations

```javascript
            /*
                +	Addition
                -	Subtraction
                *	Multiplication
                **	Exponentiation (ES2016)
                /	Division
                %	Modulus (Remainder)
                ++	Increment
                --	Decrement
            */
            //The two numbers can be literals:
                let x = 100 + 50;
            //or variables:
                let x = a + b;
            //or expressions:
                let x = (100 + 50) * a;

            //Adding
                let x = 5;
                let y = 2;
                let z = x + y;

            //Subtracting
                let x = 5;
                let y = 2;
                let z = x - y;

            //Multiplying
                let x = 5;
                let y = 2;
                let z = x * y;

            //Dividing
                let x = 5;
                let y = 2;
                let z = x / y;

            //Remainder
                let x = 5;
                let y = 2;
                let z = x % y;

            //Incrementing
                let x = 5;
                x++;
                let z = x;

            //Decrementing
                let x = 5;
                x--;
                let z = x;

            //Exponentiation
                let x = 5;
                let z = x ** 2;
```

## LogicalOperators

```javascript
            //Comparison Operators
            /*
                Given that x = 5, the table below explains the comparison operators:

                    ==	equal to	x == 8	false
                    x == 5	true
                    x == "5"	true
                    ===	equal value and equal type	x === 5	true
                    x === "5"	false
                    !=	not equal	x != 8	true
                    !==	not equal value or not equal type	x !== 5	false
                    x !== "5"	true
                    x !== 8	true
                    >	greater than	x > 8	false
                    <	less than	x < 8	true
                    >=	greater than or equal to	x >= 8	false
                    <=	less than or equal to	x <= 8	true
            */
             //How Can it be Used
                if (age < 18) text = "Too young to buy alcohol";

            /*
                Logical Operators

                Given that x = 6 and y = 3, the table below explains the logical operators:

                &&	and	(x < 10 && y > 1) is true	
                ||	or	(x == 5 || y == 5) is false	
                !	not	!(x == y) is true
            */
 ```

 ## IfConditions

```javascript
            /*
                Use if to specify a block of code to be executed, if a specified condition is true
                Use else to specify a block of code to be executed, if the same condition is false
                Use else if to specify a new condition to test, if the first condition is false
            */
            if (condition) {
                //  block of code to be executed if the condition is true
            }
            const hour = 15;
            if (hour < 18) {
                console.log('Good Day');
            }
            if (condition) {
            //  block of code to be executed if the condition is true
            } else {
            //  block of code to be executed if the condition is false
            }
            if (hour < 18) {
            console.log('Good Day');
            } else {
            console.log('Good evening')
            }
            if (condition1) {
            //  block of code to be executed if condition1 is true
            } else if (condition2) {
            //  block of code to be executed if the condition1 is false and condition2 is true
            } else {
            //  block of code to be executed if the condition1 is false and condition2 is false
            }
            if (time < 10) {
           console.log('Good Day');
            } else if (time < 20) {
            console.log('Good Day2');
            } else {
            console.log('Good Day3');
            }
```

## NestedIF

```javascript
            if condition1 {
            // code to be executed if condition1 is true
            if condition2 {
                // code to be executed if both condition1 and condition2 are true
            }
            }
```

## SwitchStatement

```javascript

            switch(expression) {
            case x:
                // code block
                break;
            case y:
                // code block
                break;
            default:
                // code block
            }

            let x = "0";
                switch (x) {
                case 0:
                    text = "Off";
                    break;
                case 1:
                    text = "On";
                    break;
                default:
                    text = "No value found";
                }
```

## Arrays

```javascript

            const cars = ["Saab", "Volvo", "BMW"];

            const cars = [];
            cars[0]= "Saab";
            cars[1]= "Volvo";
            cars[2]= "BMW";

            const cars = ["Saab", "Volvo", "BMW"];
            let car = cars[0];

            console.log(cars[0])
```

## ForLoop

```javascript
            for (expression 1; expression 2; expression 3) {
            // code block to be executed
            }

            for (let i = 0; i < 5; i++) {
            text += "The number is " + i + "<br>";
            }

            text += cars[0] + "<br>";
            text += cars[1] + "<br>";
            text += cars[2] + "<br>";
            text += cars[3] + "<br>";
            text += cars[4] + "<br>";
            text += cars[5] + "<br>";

            for (let i = 0; i < cars.length; i++) {
            text += cars[i] + "<br>";
            }

            let i = 2;
            let len = cars.length;
            let text = "";
            for (; i < len; i++) {
            text += cars[i] + "<br>";
            }
```

## WhileLoop

```JavaScript
            while (condition) {
            // code block to be executed
            }

            while (i < 10) {
            text += "The number is " + i;
            i++;
            }
```

## DoWhileLoop

```javascript
            do {
            // code block to be executed
            }
            while (condition);

            do {
            text += "The number is " + i;
            i++;
            }
            while (i < 10);
```

## Function

```javascript
            // Function to compute the product of p1 and p2
                function myFunction(p1, p2) {
                return p1 * p2;
                }

            function name(parameter1, parameter2, parameter3) {
            // code to be executed
            }
```

## ArrowFunction

```javascript
            const myFunc = (p1,p2)=>{
                return p1*p2
            }
```

## Object

```javascript
            const car = {type:"Fiat", model:"500", color:"white"};

            const person = {
                firstName: "John",
                lastName: "Doe",
                age: 50,
                eyeColor: "blue"
            };

            // accessing
                //objectName.propertyName

            console.log(person.age);
```
