# project2

const readline = require('readline')
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
})

var seats;
const single = [1,4,7,10,13,16,19,22,25,28];
const doubleaisle = [2,5,8,11,14,17,20,23,26,29];
const doublewindow = [3,6,9,12,15,18,21,24,27,30];
var customer = 30;

//const single = [{ number: 1, number: 4, number: 7, number: 10, number: 13, number: 16, number: 19, number: 22, number: 25, number: 28}];
const doubleaisle = [{ number: 2, number: 5, number: 8, number: 11, number: 14, number: 17, number: 20, number: 23, number: 26, number: 29}]; 
const doublewindow = [{ number: 3, number: 6, number: 9, number: 12, number: 15, number: 18, number: 21, number: 24, number: 27, number: 30}]; 


// (function(){
    
// }())


console.log('Attention!! Press Ctrl + \'C\' to exit at any time')

    rl.question('Please enter 1 for (Single Seat) , 2 for (Double[Aisle] Seat) and 3 for (Double[Window] Seat) : ', (answer) => {
        seats = parseInt(answer)
        if (answer==1){
            console.log("----------BOARDING PASS----------");
            console.log("Type of seats : Single");


        }else if(answer==2){
            console.log("----------BOARDING PASS----------");
            console.log("Type of seats : Double (Aisle)");

        }else if(answer==3){
            console.log("----------BOARDING PASS----------");
            console.log("Type of seats : Double (Window)");

        }else{
            console.log('Your input was not recognized as a number. Please try again.')

        }
        rl.close();
    })
    
  //function booking() {
    var found = single.some(customer => customer.number === selectedseat);
    single.push({number: 0});


    if (!found){
        console.log("This seat is unavailable. Please select a different seat.");
        <TextInput>enter seat number etc etc </TextInput>
    }
    return single;
}  



