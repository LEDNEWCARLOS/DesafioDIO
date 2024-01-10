let nomeDoheroi = "hercules"
let xpDoHeroi = 7500;

//Estrutura de decisão
if (xpDoHeroi < 1000){
    console.log( nomeDoheroi + " está no nível Ferro ")
}else if(xpDoHeroi =>1001 && xpDoHeroi<=2000){
    console.log(nomeDoheroi + " está no nível Bronze ")
}else if(xpDoHeroi =>2001 && xpDoHeroi <= 5000){
    console.log(nomeDoheroi + " está no nível Prata ")
}else if(xpDoHeroi => 5001 && xpDoHeroi <= 7000){
    console.log(nomeDoheroi + " está no nível Ouro ")
}else if(xpDoHeroi => 7001 && xpDoHeroi <= 800){
    console.log(nomeDoheroi + " está no nível Platina ")
}else if(xpDoHeroi => 8001 && xpDoHeroi <= 9000){
    console.log(nomeDoheroi + " está no nível Ascendente ")
}else if(xpDoHeroi => 9001 && xpDoHeroi <= 10000){
    console.log(nomeDoheroi + " está no nível Imortal ")
}else if (xpDoHeroi >= 10001){
    console.log(nomeDoheroi + " está no nível Radiante ")
}
//saída
console.log("O heroi de nome: " + nomeDoheroi + " está no nível de: " +  xpDoHeroi)
