# project2

var single = [0,0,0,0,0,0,0,0,0,0];
var doubleaisle = [0,0,0,0,0,0,0,0,0,0];
var doublewindow = [0,0,0,0,0,0,0,0,0,0];
var customer = 30;
 


function startarray() {
    var answer;
    const readline = require('readline');
const r1 = readline.createInterface({
input: process.stdin,
output: process.stdout,
prompt: 'OHAI> '
});

    for (let i = 0; i < customer; i++) {
        r1.question("Please type 1 Single seat and Please type 2 for Double[Aisle] and Please type 3 for Double[Window].", (answer) => {
         if(answer==1) {
             
         } 
         else if (answer==2) {
             
         } else if (answer == 3) {
             
         } else {
             
         }
             
         
        }
       
        
    }
    
}
