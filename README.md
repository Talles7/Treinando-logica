# Treinando-lógica de programação
# Desafios 3 - while()

Mais uma vez tendo que recorrer ao básico inicio da logica de programação, fortalecendo os fundamentos que se esvaiu da minha mente, mas como um bom combatente venho renovar minhas habilidades e ficar apto ao mercado tão concorrido.

// 1. Crie um contador que comece em 1 e vá até 10 usando um loop while. 
//    Mostre cada número. 
```
let numero = 0;  
while (numero <= 10){
    alert(numero);
    numero++
}
```

//2. Crie um contador que começa em 10 e vá até 0 usando um loop while.
//   Mostre cada número.  
``` 
let numero = 10;  

while (numero >= 0){
    alert(numero);
    numero--
}
```

// 3. Crie um programa de contagem regressiva. Peça um número e conte deste número até 0,
//    usando um loop while no console do navegador.  
```
let numero = prompt('Digite um número para iniciar a contagem regressiva:');

while (numero >= 0){
    alert(numero);
    numero--
}
```

// 4. Crie um programa de contagem progressiva. Peça um número e conte de 0 até esse número,
//    usando um loop while no console do navegador.
```
let numeroLimite = prompt('Digite um numero que deseja a contagem:');
let numero = 0; 

while (numero <= numeroLimite){
    alert(numero);
    numero++
}
```
