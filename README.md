# Dom_oppgave-2

oppgave-1
document.getElementById('skrivUt').addEventListener('click', function() {

const celsiusToFahrenheit = celsius => celsius * 9/5 + 32;

const fahrenheitToCelsius = fahrenheit => (fahrenheit - 32) * 5/9;


celsiusToFahrenheit(15);    // 59
fahrenheitToCelsius(59);    // 15
});
oppgave-2
document.getElementById('skrivUt').addEventListener('click', function() {
    let tallet1 = document.getElementById("tall1").value;
    let tallet2 = document.getElementById("tall2").value;
     const num = Math.ceil(Math.random() *  let tallet1, let tallet2  );
     console.log(num);
    if (tallet1 < tallet2) {
        document.getElementById("result").innerHTML = "tallet 1 er mindre enn tallet 2"
    }  if else (tallet1 > tallet2) {
        document.getElementById("result").innerHTML = "tallet 1 er større enn tallet 2"
    } else {
        document.getElementById("result").innerHTML = "De er like"
    }
     if (gnum == num)
   console.log('Matched');
  else
   console.log('Not matched, the number was '+gnum);
});

oppgave-3


function checkPalindrome(str) {

   
    const arrayValues = string.split('');


    const reverseArrayValues = arrayValues.reverse();


    const reverseString = reverseArrayValues.join('');

    if(string == reverseString) {
        console.log('It is a palindrome');
    }
    else {
        console.log('It is not a palindrome');
    }
}


const string = prompt('Enter a string: ');

checkPalindrome(string);
