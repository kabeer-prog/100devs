# 100devs
Compilation of 100devs projects, Assignment,class practices 


let num1 = 8
let num2 = 2



document.getElementById("num1-el").textContent = num1
document.getElementById("num2-el").textContent = num2



function add(){
  
// num1 + num2 = document.getElementbyId("sum-el").textContent
 
 let sumEl = document.getElementById("sum-el");
  sumEl.textContent = "sum is " + (num1 + num2);
}

