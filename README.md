// joao arthur
// aula sobre condicionais

//let condicao1 = true;
//if (condicao1){
   // console.log('Entrei no if 1!');
////}

// condicao2 = false;
//if (condicao2){
   // console.log('Entrei no if 2!');
//}


//let condicao = false 

//if (condicao){
  //  console.log('entrei no if!')
//} else {
 //   console.log('entrei no else!')
//}

//function comparaNumeros(a,b) {
    //if(a === b){
   //    return "iguais"
   // }
   // } else {
   // return "diferentes"
//}

//console.log(comparaNumeros(
//    Number(prompt('digite o primeiro numero')),
 //   Number(prompt('digite o segundo numero'))
//));

//let condicao9 = false 
//let condicao5 = true

//if (condicao9){
  //  console.log('entrei no if 9!')
//} else {
  //  if (condicao5){
       //  console.log('entrei no if 5!')
    //}
//}



//let condicao1 = false
//let condicao2 = false 
//
//if (condicao1){
  //  console.log('entrei no if 1!')
//} else if (condicao2){
  //  console.log('entrei no if 2!')
//} else {
  //  console.log('entrei no else!')
//}





//function comparaNumeros(a,b) {
   // if(a === b){
      // return "iguais"
    //} else if(a >) {
  //  return "diferentes"
//}/

//console.log(comparaNumeros(
    //Number(prompt('digite o primeiro numero')),
  //  Number(prompt('digite o segundo numero'))
//))



let paisDeOrigem
if (paisDeOrigem === 'Brasil'){
    console.log('brasileiro')
} else if (paisDeOrigem === 'EUA'){
    console.log('norte americano')
}  else if (paisDeOrigem === 'Inglaterra'){
    console.log('ingles')
} else if (paisDeOrigem === 'Franca'){
    console.log('frances')
} else if (paisDeOrigem === 'Italia'){
    console.log('italiano')
} else if (paisDeOrigem === 'canada'){
    console.log('canadence')
} else {
    console.log('nacuinalidade nao encontrada')
}


switch (paisDeOrigem){
    case 'Brasil':
        console.log('brasileiro')
        break
    case 'EUA':
        console.log('norte americano')
        break
    case 'Inglaterra':
        console.log('ingle')
        break 
    default:
        console.log('nacionalidade nao encotrada')
        break
}

let pokemonInicial = prompt("digite um pokemon")


switch (pokemonInicial){
    case 'bulbasauro':
        console.log('planta e veneno')
        break
    case 'charmander':
        console.log('fogo')
        break
    case 'squirtle':
        console.log('agua')
        break 
    default:
        console.log('nacionalidade nao encontrada')
        break
}
