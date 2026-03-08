// Declarar as variáveis
let entDDD
let DDD
let Cidade
// Entrada de dados
entDDD = prompt(`Digite o seu DDD:`)

//Convertendo em parseint
DDD = parseInt(entDDD)
// Atribuição de local ao DDD
switch (DDD) {
 case 61:
     Cidade = `Brasília`;
     break;
 case 71:
     Cidade = `Salvador`;
     break;
 case 11:
     Cidade = `São Paulo`;
     break;
 case 21:
      Cidade = `Rio de Janeiro`;
      break;
 case 32:
      Cidade = `Juíz de Fora`;
     break;
 case 19:
     Cidade = `Campinas`;
     break;
 case 27:
     Cidade = `Vitória`;
     break;
 case 31:
      Cidade = `Belo Horizonte`;
      break;
      default:
      Cidade = `DDD não cadastrado`

}
//Saída de dados
console.log (Cidade)
