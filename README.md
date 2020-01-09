# **Random integer**

### Generate a random integer in Javascript (ES6), within a given range. 
This package is based on [an example from the W3Schools Javascript Random page](https://www.w3schools.com./js/js_random.asp "W3Schools JavaScript Random").

## **Installation**
> `npm install random-int --save`    

or  

> `yarn add random-int`  

---
## **Syntax**

> **`randomInt(low, high);`**

### **Parameters**
  - `low`:   
  Optional minimum value (included). This is defaults to `1`.
  - `high`:   
  Optional maximum value (included). This is defaults to `100`.


### **Return value**  
  - `randomInt` will return a randomly generated Integer within and including the low/high limits. 
---
## **Usage**

**Import the `randomInt` function**

```
import randomInt from "random-int";
```
or
```
const randomInt = require("random-int")
```
**Sample implementations**
```  
// Returns a random integer between default limits of 1 and 100, inclusive.
const myRandomInteger = randomInt();

// Returns a random integer between 1 and 10, inclusive.
const myRandomInteger = randomInt(1, 10);
```
---
## **References**  
 - [W3Schools Javascript Random](https://www.w3schools.com/js/js_random.asp "W3Schools Javascript Random")
 - [MDN Math.random](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random "MDN Math.random")
 - [MDN Math.floor](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/floor "MDN Math.floor")