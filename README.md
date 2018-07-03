# String Polindrome
function isPalindrome(str) {
    str = str.replace(/s/g, '').toLowerCase();
    return (str == str.split('').reverse().join(''));
}
# Number polndrome
Number(n.toString().split("").reverse().join("")) === n
# it will return an obj with  number of occurences of char in string
occurences = str1.split("").reduce((arr, cur) => { arr[cur] ? arr[cur]++ : arr[cur] = 1; return arr; }, {});


# myPracticejs
Array practiceArray.prototype.customInsert=function(val,callback){
  //your code here
  var customSort = [];
  this.push(val);
return this.sort(callback);
}

var cussort = function(a,b){
return b-a;
}
undefined
arr.customInsert(88,cussort);
(5) [88, 10, 9, 8, 7]
var cussort = function(a,b){
return a-b;
}
undefined
arr.customInsert(88,cussort);
(6) [7, 8, 9, 10, 88, 88]
Array.prototype.customInsert=function(val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  customSort = this.sort(callback);
}
ƒ (val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  customSort = this.sort(callback);
}
cussort isPrototypeOf function
VM160:1 Uncaught SyntaxError: Unexpected identifier
cussort isPrototypeOf "function"
VM161:1 Uncaught SyntaxError: Unexpected identifier
cussort isPrototypeOf Array
VM167:1 Uncaught SyntaxError: Unexpected identifier
cussort instanceof Array
false
cussort instanceof Function
true
Array.prototype.customInsert=function(val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  if(callback instanceof Function){
    customSort = this.sort(callback);  
  }else{
    customSort = this.sort();
  }
 return customSort.filter((value,index)=>customSort.indexOf(value)===index);
}
ƒ (val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  if(callback instanceof Function){
    customSort = this.sort(callback);  
  }else{
    customSort = this.sort();
  }
 ret…
arr.customInsert(88,cussort);
(5) [7, 8, 9, 10, 88]
Array.prototype.customInsert=function(val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  if(callback instanceof Function){
    customSort = this.sort(callback);  
  }else{
    customSort = this.sort();
  }
 return customSort.filter((value,index)=>customSort.indexOf(value)===customSort.lastIndexOf(value));
}
ƒ (val,callback){
  //your code here
  var customSort = [];
  this.push(val);
  if(callback instanceof Function){
    customSort = this.sort(callback);  
  }else{
    customSort = this.sort();
  }
 ret…
arr.customInsert(88,cussort);
(4) [7, 8, 9, 10]
