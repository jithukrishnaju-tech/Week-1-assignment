## Counter without setInterval

Without using setInterval, try to code a counter in Javascript. There is a hint at the bottom of the file if you get stuck.

let counter=1;
let callcounter=()=>{
if(count<100){
console.log(count);
setTimeout(callcounter,1000);
}
}
callcounter();




































































(Hint: setTimeout)
