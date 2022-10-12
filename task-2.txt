console.log("1st attempt");
let a = -100;
let b = 33;

const defineMin = function(x,y){
    console.log(Math.min(x,y));
}

defineMin(a,b);

console.log("");
console.log("2nd attempt");

let min = function(m,n){
    if(m <= n){
        console.log(m);
    }
    else {
        console.log(n);
    }
}

min(a,b);
