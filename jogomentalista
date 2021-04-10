//cria variavel que vai guardar o numero secreto
//usa a função math.random() pra gerar um número randomico e multiplica ele por 10, para que diminuam as casas após a virgula
//parseint para o número se tornar inteiro
var numeroSecreto = parseInt(Math.random() * 10)
//determina que o numero de tentativas do jogador serão 3
var numTentativas = 3

//cria um laço de repetição para contar as tentativas do usuário e ir rodando enquanto ele tiver chances
while (numTentativas){
  //variavel para pedir ao usuario que digite um número
  var chuteUsuario = parseInt(prompt("Digite um número entre 0 e 10: "))
  
  //verificação se o numero digitado é o mesmo que o numero secreto e mensagem de acerto com o break pra sair do loop
  if (chuteUsuario == numeroSecreto){
    alert("Você acertou!")
    break
  } else if (chuteUsuario > numeroSecreto){
    alert("O número secreto é menor.")
    //a cada vez que o usuário cai na condição, uma tentativa é reduzida e o laço continua até zerar
    numTentativas = numTentativas - 1
  } else if (chuteUsuario < numeroSecreto){
    alert("O número secreto é maior.")
    numTentativas = numTentativas - 1
    } 
}

//msg ao usuário quando acabarem as tentativas e ele não acertar o número
if (chuteUsuario != numeroSecreto){
  alert("Suas tentativas acabaram. O número secreto era " + numeroSecreto)
}
