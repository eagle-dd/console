# console
1
1
"hello"
"hello"
var debug = 0
undefined
debug
0
if(3>5){
console.log("true")
}else{
    console.log("false")
}
VM328:4 false
undefined
for(var i=0;i<=9;i=i+1){
console.log(i)
}
VM495:2 0
VM495:2 1
VM495:2 2
VM495:2 3
VM495:2 4
VM495:2 5
VM495:2 6
VM495:2 7
VM495:2 8
VM495:2 9
undefined
for(var i=1;i<=25;i=i+2)
console.log(i)
}
VM648:3 Uncaught SyntaxError: Unexpected token '}'
for(var i=1;i<=25;i=i+2){
console.log(i)
}
VM657:2 1
VM657:2 3
VM657:2 5
VM657:2 7
VM657:2 9
VM657:2 11
VM657:2 13
VM657:2 15
VM657:2 17
VM657:2 19
VM657:2 21
VM657:2 23
VM657:2 25
undefined
var name="divyanshu"
switch(name){
    case "Divyanshu":console.log("1st case")
       break
    case "DIVYANSHU":console.log("2nd case")
break
    default:console.log("default case")
break}
VM1208:7 default case
undefined
var name="divyanshu"
switch(name){
    case "divyanshu":console.log("1st case")
       break
    case "DIVYANSHU":console.log("2nd case")
break
    default:console.log("default case")
break}
VM1217:3 1st case
undefined
function perimeter(s){
var p=4*s
return p
}
undefined
perimeter(2)
8
var name="divyanshu"

undefined
name.toUpperCase
ƒ toUpperCase() { [native code] }
name.toUpperCase()
"DIVYANSHU"
var array=["name",1,true]
array.length
3
console.log(array[2])
VM1712:1 true
undefined
array.push(false)
4
array
(4) ["name", 1, true, false]
array.pop()
false
array
(3) ["name", 1, true]
array.pop(1)
true
var variable=new Object()
variable.width=3
function = showWidth(){
VM2136:3 Uncaught SyntaxError: Unexpected token '='
var variable=new Object()
variable.width=3
function = showWidth(){
console.log(variable.width)
}
VM2304:3 Uncaught SyntaxError: Unexpected token '='
var variable=new Object()
variable.width=3
function  showWidth()={
console.log(variable.width)
}
VM2317:3 Uncaught SyntaxError: Unexpected token '='
var variable=new Object()
variable.width=3
variable.showWidth=function(){
console.log(variable.width)
}
ƒ (){
console.log(variable.width)
}
variable.showWidth
ƒ (){
console.log(variable.width)
}
variable.showWidth()
VM2379:4 3
undefined
