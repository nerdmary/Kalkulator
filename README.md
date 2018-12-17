// Kalkulator;
// Min første kalkulator, lek;

var velgMatte = prompt ("Velg mellom +, -, *, /");
var firstNumber = prompt("Hva er ditt første tall?");
var secondNumber = prompt("Hva er ditt andre tall?");

if (velgMatte == "+") { 
    console.log (parseInt(firstNumber) + parseInt(secondNumber))
}
else if (velgMatte == "-") {
    console.log (parseInt(firstNumber) - parseInt(secondNumber))
}
else if (velgMatte == "*") {
    console.log (parseInt(firstNumber) * parseInt(secondNumber))
}
else if (velgMatte == "/") {
    console.log (parseInt(firstNumber) / parseInt(secondNumber))
}
else {
    console.log ("Prøv på nytt")
};
