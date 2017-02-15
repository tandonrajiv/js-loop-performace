# js-loop-performace
This is a demo show you how you can increase performance of js application. 


Writing short code is very important and well explanatory.


1) When using switch case
```javascript
let myvariable = '';
passed  = 'b';
switch ( passed ) {
    case 'a':
        myvariable = 1;
    break;
    case 'b':
        myvariable = 2;
    break;
    default:
        myvariable = 3;
    break;
}
console.log(foo);
```
2) When using if else
```javascript
let passed = '';
if ( passed === 'a' )
    myvariable = 1;
else if ( passed === 'b' )
    myvariable = 2;
else
    myvariable = 3;
```
3) For n numbers of condition ternary is not right and also confusing 


Then Solution is objectLiteral
```javascript
let myvariable = ( {
    a: 1,
    b: 2,
} )[ 'passed' ] || 3;

Or

let myvariable = {
    a: 1,
    b: 2,
};
let foo = values[ 'passed' ] || 3;
```
Performance are high to low.

a) Switch and objectLiteral around same
b) ifelse

