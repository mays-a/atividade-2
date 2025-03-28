# atividade-2

//Exercício1

const meninos = ['Eduardo','Danilo', 'João']
const meninas = ['Camila', 'Alice', 'Jasmin']
function concatene() {
    const todos = meninos.concat(meninas)
    console.log(todos)
}
concatene()

//----------------------------------------------------
//Exercício2

const numeros = ['1','2','3','4','5','6','7','8','9','10']
const parteNumeros =numeros.slice(3,8) 
console.log(parteNumeros)

//----------------------------------------------------
//Exercício3

const frutas = ['Maçã','Banana','Laranja','Limão','Abacaxi']
frutas.splice(2,2,'Kiwi','Pêssego')
console.log(frutas)

//----------------------------------------------------
//Exercício4

const menuPrincipal = ['Macarronada','Strogonoff', 'Feijoada','Frango a Milanesa','Croissant']
const menuDeSobremesas = ['Pudim', 'Sorvete', 'Pavê', 'Gelatina', 'Mousse de Limão']
const menuCompleto = menuPrincipal.concat(menuDeSobremesas)
console.log(menuCompleto)
