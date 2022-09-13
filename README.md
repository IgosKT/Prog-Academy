# Prog-Academy

let bitcoinPrice = parseFloat(prompt("введіть курс Bitcoin до доллара"));

let howMuch$ = parseFloat(prompt("введіть суму доларів, що хоче поміняти на Bitcoin"));

while (bitcoinPrice <= 0 || howMuch$ <= 0) {

    bitcoinPrice = parseFloat(prompt("введіть курс Bitcoin більше 0"));
    
    howMuch$ = parseFloat(prompt("введіть суму доларів більше 0"));
    
};

alert(`Ви отримаєте ${howMuch$/bitcoinPrice}`);
