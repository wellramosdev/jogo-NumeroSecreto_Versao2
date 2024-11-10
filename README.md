# jogo-NumeroSecreto_Versao2

alert ("Seja bem vindo ao jogo do Número Secreto");
let numeroSecreto = 5 ;
let chute;
console.log (numeroSecreto);


let tentativas = 1; 

//enquanto o chute não for iguak ao número secreto 

while (chute != numeroSecreto) { 
    chute = prompt (" Escolha um número entre 1 e 30");
    if (numeroSecreto == chute) {
        alert (`Isso aí! Você acertou o número secreto ${numeroSecreto} com ${tentativas} tentativas`);
    }
    
    else {
       if (chute > numeroSecreto) {
        alert (`O numero secreto é menor que ${chute}`);
    } else {
        alert (`O número secreto é maior que ${chute}`);
    }
    }
    //tentativa = tentativas + 1;
    tentativas ++;
}
