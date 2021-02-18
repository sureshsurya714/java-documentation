# java-documentation

### Functions

### Functions without parameters
```javascript 
function addition(){
    var a=5
    var b=6
    return a+b;
}

addition()
```

### Functions with parameters
```javascript
function addition(a,b){
    return (a+b) 
}

addition(1,2)
3
```

### Function with no name/ anonymous function

```javascript
var sub=function(a,b){
    return (a-b) 
}

sub(1,2)
```

var mul=function(a,b){
    return (a*b)
}

mul(2,3)

6

### Higher order functions (HOF)
*A function accepts another function as a argument.*

```javascript
arr.map((item,index)=>{
    console.log(item+"is having index of :"+index)
})
```
