// exo_rattrapage

// exo 1
/*
function repeter (string,multiple){    

    return string.repeat(multiple);
}

let newText = repeter ('Abigail et Olivia. ', 5);

console.log(newText);
*/

// exo 2
/*
function inverser (string) {
    return string.split('').reverse().join('');
}

let myNewText = inverser ('Sandrine');
console.log(myNewText);
*/

/* exo 3
creer une fonction remove
1 argument texte
retourner le texte (ne pas inverser les 'lettres') en enlevant le 1er et le dernier caractère*/

/*
function remove (string) {
    return string.slice((1),(0,-1));

}

let myNewText = remove ('Sandrine');
console.log(myNewText);
*/

/* exo 4
creer une fonction removeSpace
recoit un argument texte (1 phrase)
retourne le texte sans espace;*/

/*
function removeSpace (string){
    
    return string.split(" ").join("");
}


let newString = removeSpace("Bonjour, comment allez vous aujourd'hui ?");
console.log(newString);
*/

/* exo 5
creer une fonction switchName
qui recoit en argument de type string(une phrase)
et retourne l'inverse
ex: "bob dupont"  --> "dupont bob"*/

/*
function inverser(string) {
    return string.split(' ').reverse().join(' ');    
}
const myName = inverser ('Sandrine Proença');
console.log(myName);
*/

/* exo 6
creer une fonction counter
qui recoit une phrase
et retourne le nombre de mots*/

/*
function counter(string) {
return string.split(/\b\w+\b/).length-1;
}

let nbMots = counter ("je viens de m'inscrire à la monomitik");
console.log(nbMots);
*/

/* exo 7
creer une fonction pairOuImpair
recoit un nombre
retourne "pair" ou "impair"*/

/*
function pairImpair(value) {
    if (value%2 == 0){
    return "nombre pair";
    }
    else
    return "nombre impaire";
    }
let myNumber = pairImpair(5454846452);
console.log(myNumber);
*/

// Creer une fonction moyenne qui recoit un array 
//contenant plusieurs nombres et renvoie la valeur moyenne
/*
function ArrayAvg(myArray) {
    var i = 0, summ = 0, ArrayLen = myArray.length;
    while (i < ArrayLen) {
        summ = summ + myArray[i++];
}
    return summ / ArrayLen;
}
var myArray = [1, 15, 12, 3, 17];
var a = ArrayAvg(myArray);
console.log(a);
*/
