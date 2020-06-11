
## Uma guia basica a pedido de amigos que querem estudar programação.
## Linguagens

- JAVASCRIPT Até se sentir confirtável.
JS=(strutura pelo google imagens)
JS=(synchronous vs asynchronous)
JS=(object vs arrays)

- Basico CSS
- HTML
- Missão criar algo pequena loja.

## Ferramentas
- API REST,
- Basico CSS
- HTML
- Framework
- Missão criar algo com isto
- HTTP, vs HTTPS vs FTP vs SOAP

## Entendimentos
-  Materiais
-  Antes de ir para as linguagens tentar em imagem no google, entender a strutura dessas técnologias, isso da uma visão ampla.
-  A ideia é entender como as coisas funciona, sempre mais além delas. Exemplo, se existe buracos negros, o que pode existir do outro lado. 

## Me lembrar para eu falar sobre os bits e sobre protocolos, como HTTP funciona de verdade 

## Entendimentos
- Diferença rest para webservice
- Entender o que são socket packet 
- O que são bytes


## Explicação
SOCKET E PACKET é a maneira de enviar e receber arquivos, socket é uma abertura, coloca em google images. 
e packet é como nome diz o pacote. Exemplo, em todos os protocolos  HTTP, vs HTTPS vs FTP vs SOAP faz este serviço entrega e recebimento de dados. Alguns utilizando camada TCP e outro UDP. Segundo o que eu li o UDP é mais rápido, porem ele perde dados na entrega.
Provavelmente não tenho certeza o FTP utiliza esta camada UDP e por isto ao dar upload de arquivos ele pode perder e não entregar.
Só que HTTP é feito em cima do TCP, porem tem regras a ser seguidas. 
Lembra do POST, GET poise quando você envia um post pelo HTML ele interpreta essa regra no lado do servidor de que você quer enviar um post, no caso post é envio escondido. Get geralmente usado para pegar tudo aquilo do front end que não tenha problemas de ficar visivél aos olhos dos usuários. Então o server HTTP responde tudo isto. Lembra do Header do HTML várias regras como o char utf8 que é a linguagem de simbulos como ç ã, por isto recomendei estudar sobre bytes e bits.
Por de baixo dos panos na memoria da maquina existe diferença entre a=00000000000 para ã=1111111111 algumas linguas não precisa deste caracter então o interpretador (motor do navegador) ou compilador precisa converter isto para linguagem nativa do usuário. Entendendo sobre estruturas MVC que no caso é frameworks, ficara mais claro.

## Math
Como eu entendo matematica, se eu estiver errado em alguns destas lição me corrija porfavor. 

{([2 * a^2 + b * 2 / 2 + -2])}
{ } maior que () maior que []

{

[] Usado em parametros, o que é parametro?

Escopo para obter dados (idade,nome,altura) parameter1 Type numero,parameter2 Type caracters,parameter3 Type numeros inteiros negativos ou positivos flutuantes ou não flutuantes!
Nessa formúla a baixo terá apenás um parametro, dois parametros ficariam assim, e por ai vai.

{([(2 * a^2) + b * 2 / 2 + -2]+[(2 * a^2) + b * 2 / 2 + -2])}

() Usado para precedência
{} Escopo da precedência.

} > Maior que Exporênte. Fim de assunto precedências!

a = 5;
b = 10;
{([(2 * a^2) + b * 2 / 2 + -2])}
{([(2 * 25) + b * 2 / 2 + -2])}
{([ 50 + (b * 2) / 2 + -2])}
{([ 50 + (20 / 2) + -2])}
{([ (50 + 10) + - 2])}
{([ 60 + - 2])}
{([ 60 - 2])}
{([ 58 ])}

Opa, sem jogo de sinais, fiz esta!

2 * a^2 + b * 2 / 2 + 1 -2
50 + b * 2 / 2 + 1 -2
50 + 20 / 2 + 1 -2
(((50 + 10) + 1) -2)
50 + 10 = 60 + 1->61 -2 = 59

Alguém quer conferir se minha formúla esta correta?
Pode ser simplificado da seguinte maneira como descrito abaixo!

{([ (((((2 * a^2) + b) * 2) / 2) + -2)])}

O que faltou para mim ser um FullStack no assunto! Font:
https://www.youtube.com/watch?v=dAgfnK528RA&t=204s

Próximo, o que é raiz quadrada?
Sabe aquele piso de casa onde é um guadrado sendo 4/16 = 64, qual é a raiz guadrada de 64? 8 então de uma ponta de um piso até a outra tem um valor 8 que pode ser frácionado por digamos 1 milimetro cada blocozinho.

Oi eu sou o 4 de 4/16 eu sou 4 partes de 16 valores ou melhor entre 0a16.

Oi eu 8 eu sou 8^2=64 praque serve esse 2 que ninguem sabe explicar? Duas dimenssão tio naelson explica. Altura e largura de um piso. Terà oito para lagura e 8 para altura formando um quadrado.

O piso tem 64 metros guadrado um perimetro de 4/16 e uma raiz que é o "contéudo" do ponto A pode ser a ponta do piso mesmo, ao B que são 8 frações, a fração pode escalar o piso, digamos que contaremos em centimetros

[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]
[1c][1c][1c][1c][1c][1c][1c][1c]

Se caso decidir frácionar isso para uma fração menor, digmos, exemplo: milimetros.
1 centimetro - 1 milimetro = 9m obs: não é mais centimetros.

[1c - 9][1c - 9][1c - 9][1c - 9][1c - 9][1c - 9][1c - 9][1c - 9]

Resultado!

[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]
[1m][1m][1m][1m][1m][1m][1m][1m]

Digamos que isso acima é um piso de uma casa.
visualmente ele será menor, houve uma escala perdendo 9 milimetros.

Pra isso que serve raiz guadrada.
Agora veja quantos quadrados tem na terra para calcular ou criar? Muito útil.

Matemática é fácil, o tamanho do processo que torna complicado.
Bom final de semana para todos!
 
