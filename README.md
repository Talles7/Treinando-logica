# Treinando-Lógica de Programação
# Desafios 2 - if{}

Tentando corrigir o erro por não ter usado o github quando comecei o curso de Ciencia da Computação.

// 1. Pergunte ao usuário qual é o dia da semana.
```
let fimDeSemana = prompt("Olá, hoje é qual dia?").toLowerCase();
let sabado = 'sabado';
let domingo = 'domingo';

if (fimDeSemana === sabado || fimDeSemana === domingo ){
    alert('Bom fim de semana!');
}else {
    alert('Boa semana!');
}
```

// 2. Verifique se um número digitado pelo usuário é positivo ou negativo.
```
alert('Para saber se o numero é positivo ou negativo digite a seguir.');
let numero = prompt('Digite um numero:');

if (numero < 0 ){
    alert('O numero '+numero+' é negativo.');
}else{
    alert('O numero '+numero+' é positivo.');
}
```


// 3. Crie um sistema de pontuação para um jogo.
```
alert('Para continuarmos, informe a sua pontuação a seguir.');
let pontos = prompt('Pontuação:');

if(pontos >= 100){
    alert('Parabéns, você venceu!');
}else{
    alert('Tente novamente para ganhar.');
}
```

// 4. Crie uma mensagem que informa o usuário sobre o saldo da conta.
```
alert('Para realizar o saldo na conta clique em "Ok".');
let saldo = 'R$ 2,50 reais'
alert('Seu saldo na conta é '+saldo)
```


// 5. Peça ao usuário para inserir seu nome usando prompt.
```
let nome = prompt('Para continuar informe seu nome:');
alert('Bem vindo '+nome+', estamos felizes em telo aqui com nosco!');
```
