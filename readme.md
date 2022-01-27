# 7 Days of Code - Lógica de Programação com Javascript

## Dia 1

#### Exercício

Hoje iremos começar de uma forma tranquila, porém com um aprendizado bastante importante para seguirmos pros próximos dias de desafios!

Caso você ainda não tenha passado por isso, é muito comum ao utilizarmos Javascript termos problemas com os tipos de variáveis na hora de atribuirmos novos valores e os comparar

Sendo assim, você irá **reescrever o código abaixo de maneira que ele esteja imprimindo as informações de maneira correta, que faça sentido e sem erros**:

```javascript
let numeroUm = 1
let stringUm = '1'
let numeroTrinta = 30
let stringTrinta = '30'
let numeroDez = 10
let stringDez = '10'

if (numeroUm = stringUm) {
  console.log('As variáveis numeroUm e stringUm tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroUm e stringUm não tem o mesmo valor')
}

if (numeroTrinta == stringTrinta) {
  console.log('As variáveis numeroTrinta e stringTrinta tem o mesmo valor e mesmo tipo')
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não tem o mesmo tipo')
}

if (numeroDez === stringDez) {
  console.log('As variáveis numeroDez e stringDez tem o mesmo valor, mas tipos diferentes')
} else {
  console.log('As variáveis numeroDez e stringDez não tem o mesmo valor')
}
```

#### Dica

**Você pode utilizar o próprio navegador para executar o seu programa** caso ainda não tenha familiaridade com editores de código, como o Visual Studio Code
Para isso, basta você clicar com o botão direito do mouse em qualquer página, ir em `console` e digitar o seu código, bem simples

Caso queira **mudar os nomes das variáveis e valores**, sinta-se a vontade, porém jamais imprima algo que não seja verdadeiro, hein!

#### Extra

Para aprender mais sobre **operadores de comparação**, dê uma olhada [nesse artigo](https://www.alura.com.br/artigos/operadores-matematicos-em-javascript?gclid=Cj0KCQiA_8OPBhDtARIsAKQu0gYUqZqgonpXyEP1_hpUl58wYAk_P3Ze4VWrxo9ftkFW9CLYOMyjO1caAlrzEALw_wcB) da Alura

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 2

#### Exercício

Sabe quando você se cadastra em um site e logo em seguida, quando você faz o seu login, ele já te chama pelo seu próprio nome? No desafio de hoje iremos fazer isso!

Você precisará desenvolver um programinha que simulará um desses sites e **ele pedirá para a pessoa que for utilizá-lo responder 3 perguntas**:
`Qual o seu nome?`
`Quantos anos você tem?`
`Qual linguagem de programação você está estudando?`

E, claramente, a pessoa que estiver usando o programa deverá **responder cada uma delas a medida que forem sendo feitas**

No final, o programa irá **imprimir a mensagem:**

`"Olá X, você tem X anos e já está aprendendo X!"`

Em que cada `X` é uma das respostas dadas pela pessoa

#### Dica

Você poderá **adicionar quantas perguntas quiser**, inclusive adicionando as respostas da pessoa na mensagem que será impressa

Para **imprimir e receber valores**, você pode tanto usar `console.log`, `prompt` e `alert`, quanto usar HTML e CSS caso já tenha conhecimento dessas duas tecnologias

#### Extra

Para aprender mais sobre **prompt** e **alert**, dê uma olhada [nesse site](https://www.devmedia.com.br/alert-em-javascript/37208)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 3

#### Exercício

Você alguma vez já jogou algum jogo onde ele te desse mais de uma escolha e, dependendo da que você escolhesse, o destino da personagem seria totalmente diferente?

Vamos fazer um um exemplo com Javascript!

Seu desafio de hoje é **criar os destinos possíveis de um jogo**, em que a pessoa jogador consiga escolher:

1. No **início** de seus estudos, onde poderá escolher entre **seguir para área de front-end** ou **seguir para a área de back-end**

2. No **meio**, onde caso esteja na área de **front-end**, ela poderá **seguir aprendendo React** ou **seguir aprendendo Vue** e, caso esteja na área de **back-end**, poderá **seguir aprendendo C#** ou **seguir aprendendo Java**

3. No **fim**, onde, independente de suas escolhas anteriores, ela poderá escolher entre **seguir se especializando na área escolhida** ou **seguir se desenvolvendo para se tornar fullstack**

O importante é que a pessoa que jogar possa sempre **escolher qual decisão tomar** para conseguir aprender e se desenvolver na área de programação

#### Dica

Já da pra ter uma ideia de como fazer toda essa historinha acontecer né? Principalmente lembrando como utilizamos as **estruturas condicionais em Javascript**!

Caso você ainda não saiba como **imprimir e receber valores** nas páginas web com HTML e CSS, você poderá usar `console.log`, `prompt` e `alert` para desenvolver o seu jogo

Lembre-se que você pode sempre **personalizar** o jogo da forma que quiser!

#### Extra

Para aprender mais sobre **estruturas condicionais em Javascript**, dê uma olhada [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/if...else)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 4

#### Exercício

Você já brincou de tentar adivinhar o número que seu amigo ou amiga estava pensando? Pois hoje você irá jogar esse joga contra o próprio computador!

Aqui está tudo o que você precisa fazer para o desafio de hoje:

Você deve criar um programinha que **já inicialize com um valor específico entre 0-10 para o número que você irá adivinhar**
Em seguida, ele perguntará para você **qual o valor que você deseja chutar** e, caso você acerte, ele irá te **parabenizar** ou, caso erre, ele irá **te dar mais 2 tentativas**
No fim, caso você não acerte nenhuma vez, ele irá **imprimir qual era o número inicial**

#### Dica

Pense muito bem em qual **estrutura de repetição** você irá utilizar para fazer o seu programa ser executado até o momento que as 3 tentativas acabarem ou a pessoa acertar o número

Lembre-se que você pode sempre **personalizar** o seu programinha da forma que quiser!

#### Extra

Você pode até incrementar o seu programa e fazer a própria máquina escolher sozinha o número a ser adivinhado, utilizando algo chamado `Math.random()`, que você pode conferir [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Math/random)

Para aprender mais sobre **estruturas de repetição**, dê uma olhada [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Loops_and_iteration)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 5

#### Exercício

Você já foi alguma vez no supermercado e levou uma lista de compras, porém como escreveu tudo na ordem que foi lembrando, teve que buscar uma maçã na área de frutas, depois um leite na área de laticínios e depois uma pêra novamente na área de frutas e ficou nesse vai e volta pelo lugar inteiro pra completar a lista?

Depois que você resolver o desafio de hoje com certeza não fará mais isso!

O que você deverá fazer então:

Para facilitar a sua ida ao supermercado, você irá criar um programa em Javascript, onde ele **perguntará se você deseja adicionar uma comida na lista de compras** para você responder com `sim` ou `nao`. 
Em seguida **perguntará qual comida você deseja inserir** e você digitará o nome dela, como por exemplo `batata`.
Em seguida, ele deverá **perguntar em qual categoria essa comida se encaixa**, com opções já pré definidas, como `laticínios`, `congelados`, `doces` e o que mais achar interessante, assim poderá separar tudo no seu devido grupo
Por fim, caso você não queira mais adicionar nada na lista de compras e responder `nao` na primeira pergunta, ele irá **imprimir uma lista com todos os itens agrupados**, da seguinte forma:

Caso você adicione na sua lista: 
`banana`, `leite em pó`, `tomate`, `leite vegetal`, `chiclete`, `bala de ursinho`, `maçã`, `uva`, `abacate` e `leite de vaca`

O programa deverá imprimir, por exemplo:

`Lista de compras: banana, tomate, maçã, uva, abacate, leite em pó, leite vegetal, leite de vaca, chiclete e bala de ursinho`

#### Dica

Temos um objeto dentro da linguagem javascript que é usado justamente para criar listas de elementos, chamado array. Use e abuse dele!

Lembre-se que você sempre pode **estilizar** da maneira que quiser o seu programinha, inclusive utilizando outras tecnologias para isso, como HTML e CSS. Porém isso **não é obrigatório** na nossa lista de lógica de programação com Javascript, então como já mencionei nos dias anteriores, você pode usar recursos como `console.log`, `alert` e `prompt` para desenvolver seu programa

#### Extra

Para aprender mais sobre **arrays em Javascript**, dê uma olhada [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array)

Não esqueça também de concatenar as diversas listas de categorias em uma só no final, para isso você pode dar uma lida [nesse site](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/Strings)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 6

#### Exercício

Lembra de ontem, que criamos um programinha para montar a nossa própria lista de compras? Pois é, hoje nosso desafio é deixar ele ainda mais legal!

Você deverá criar a opção de **deletar algum item da lista**, que será exibida junto à pergunta de **você deseja adicionar uma comida na lista de compra?**
A partir daí, o programa irá **imprimir os elementos presentes na lista atual** e a pessoa deverá **escrever qual deles deseja retirar**
Depois disso, o programa irá **deletar o elemento da lista** e **imprimir a confirmação de que o item realmente não está mais lá**
Por fim, ele voltará para o seu ciclo de perguntas inicial

#### Dica

Lembre-se que a opção de deletar um item só deverá estar disponível **a partir do momento que existir ao menos um elemento dentro da lista de compras**

Você pode fazer a procura do elemento que a pessoa deseja apagar da forma que quiser, usando **métodos do Javascript** para isso ou escrevendo manualmente tudo o que irá acontecer

Não esqueça de sempre **personalizar** o seu programinha da maneira que achar melhor!

#### Extra

Para aprender mais sobre **métodos para arrays no Javascript**, dê uma olhada [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Global_Objects/Array)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 

## Dia 7

Essa foi uma semana e tanto né? Praticamos muita coisa sobre lógica de programação com Javascript, porém ainda falta uma coisa muito importante: **organizar o nosso código**

E sim, isso é algo obrigatório para aprender como pessoa desenvolvedora, pois uma hora ou outra na sua carreira você precisará dar manutenção no seu código criado, ou até ajeitar algo no código que outra pessoa escreveu. Imagina só se esse código estiver todo bagunçado?

Uma ótima prática é sempre separar cada trecho do seu código que realizará alguma função específica em blocos de código ainda menores, mas que poderão ser reutilizados e chamados a qualquer outro momento ao longo do seu programa. São as chamadas **funções**

#### Exercício

Você já parou para pensar como uma calculadora funciona? 

Ela pede pra você digitar um número, depois você seleciona um tipo de operação com outro número e ela faz sozinha o cálculo pra te mostrar o resultado! Incrível né?

E então nosso último desafio será criar a nossa própria calculadora, porém com um detalhe muito importante: **cada operação deverá ser uma função diferente no nosso código**

A pessoa deverá **escolher uma opção de operação impressa pelo programa na tela**, depois ela deverá **inserir os dois valores que deseja utilizar** e o programa deverá **imprimir o resultado**

As opções disponíveis deverão ser: `soma`, `multiplicação`, `divisão`, `subtração` e `sair`, e nessa última o programa deverá parar de ser executado, mostrando uma mensagem "até a próxima"

#### Dica

Cada operação deverá ser uma **função** diferente no nosso código, que receberá os valores inseridos como **parâmetros** e **retornará** o resultado da operação

Não esqueça de usar **estruturas de repetição** para fazer a calculadora imprimir a escolha de operação até que a pessoa deseje parar o programa

Lembre-se também de que além do `if` e `else` também temos o `switch`, muito interessante de se utilizar em casos como esse, de múltipla escolha

**Personalize sua calculadora** da maneira que achar mais legal!

#### Extra

Para aprender mais sobre **funções em Javascript**, dê uma olhada [nesse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Guide/Functions)

Caso ainda não tenha estudado sobre o `switch` também, confira [esse site](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript/Reference/Statements/switch)

Aproveite para também estudar Javascript nos [cursos da Alura](https://www.alura.com.br/cursos-online-front-end/javascript) 