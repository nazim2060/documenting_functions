# Documenting JavaScript Functions Like a PRO

## Assign function description
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 */
function add(num1, num2) {
    return num1 + num2;
}
``` 
## Assign parameter name only
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 * @param num1
 * @param num2
 */
function add(num1, num2) {
    return num1 + num2;
}
``` 
## Assign parameter name and type
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 * @param {number} num1
 * @param {number} num2
 */
function add(num1, num2) {
    return num1 + num2;
}
```
## Assign parameter name, type & description with a hyphen before the description
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 * @param {number} num1 - Value 1
 * @param {number} num2 - Value 2
 */
function add(num1, num2) {
    return num1 + num2;
}
``` 
>**Note:** When using hyphen, make sure there is one space before and after the hyphen
## An optional parameter and default value
```javascript
/**
 * Returns greetings for the passed parameter
 * @param {string} [somebody=John Doe] - Somebody's name.
 */
function sayHello(somebody) {
    if (!somebody) {
        somebody = 'John Doe';
    }
    return ('Hello ' + somebody);
}
``` 
## Return value with a type
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 * @param {number} num1 - Value 1
 * @param {number} num2 - Value 2
 * @returns {number}
 */
function add(num1, num2) {
    return num1 + num2;
}
``` 
## Return value with a type and description
```javascript
/**
 * Returns the sum of two numbers passed to the function.
 * @param {number} num1 - Value 1
 * @param {number} num2 - Value 2
 * @returns {number} - Sum of num1 and num2
 */
function add(num1, num2) {
    return num1 + num2;
}
```
>### Website References (to learn more about documentation, please visit the following links)
| Particulars       | Website                        |
| ----------------- | ------------------------------ |
| `@params`         | [Website](https://jsdoc.app/tags-param.html)                    |
| `@returns`        | [Website](https://jsdoc.app/tags-returns.html)                    |

### Visit [My Blog](https://blog.nazmulalam.com) for more.
