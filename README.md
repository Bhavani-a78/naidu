# naidu

### functions
functions without parameters
```javascript
function addition(){
     var a=10;
     var b=20;
     return a+b;
}

   addition()                                                 
30
```
functions with parameters
```javasript
function addition(a,b){
        return(a+b);
}
   addition(2,3)                                                 
5
```
function with paremeters
```javascript
function subtraction(a,b){
        return(a-b);
}

   subtraction(2,3)                                                 
-1
```
 anonymous functions
```javascript
var subtraction=function(a,b){
    return (a,b)
}
undefined
subtraction(4,5)
5
```
  arrow function
  
  ```javascript
  var mul=(a,b)=>{
    return (a*b)
}

mul(2,3)
6
```


var arr=["ganesh","naidu","bhavani"]
undefined
arr.map(function(i){
     console.log(i)
})
 ganesh
 naidu
 bhavani
(3) [undefined, undefined, undefined]
```
 higher order function(HOF)
 A Function accepts another function as an argument
 
 arr.map((item,index)=>{
      console.log(item+"is having index of : "+index)
})
