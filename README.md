# Linguagem-Markdown
---

Topicos
---

- [Identação](#identação)
- [Lista numeradas](#lista-numeradas)
- [Lista demarcada](#lista-demarcada)
- [Lista de tarefas](#lista-de-tarefas)
- [Colocando Imagens](#colocando-imagens)
- [Criando tabelas](#criando-tabelas)
- [Digitando Comandos](#digitando-comandos)
- [Emojis](#emojis)
- [Manual completo markdonw](#saiba-mais)
---


## Identação

* Para usar Negrito dois (**) ou dois (__) underline no começo e no final da frase que deseja deixar em negrito e sem espaço:

__Com dois asterisco / Com dois underline__

* Para usar Itálico um (*) ou um (_) undeline no começo e no final da frase que deseja deixar em Itálico e sem espaço:

*Com 1 asterisco / Com 1 underline*

* Para riscar a palavra usar dois ( ~~ ) no começo e final da frase sem espaço:

~~Riscado~~

# Título nível 1 ( # )

## Título nível 2 ( ## )

### Título nível 3 ( ### )

***
Para usar um divisor com linha --- na linha vazia ou 3 *** e pular pra próxima
Podemos misturar configurações exemplo: __*negrito + itálico*__ ( __ * palavra * ___ )

### Lista numeradas

1. Um Número + Um ponto e a lista seguira a ordem crescente automaticamente independente se você colocar um número fora da ordem
1. Teste
   1. Podemos criar um sub item adicionando 3 espaços + um número + um ponto
   1. E assim por diante
      1. E se quiser um sub item do sub item só adicionar 3 espaços na linha de baixo do sub item + um número + um ponto.

### Lista demarcada

* A lista demarcada basta utilizar um (*) + um espaço e começar escrever normalmente na frente

* E assim por sequência
  * Para o subitem basta dar 2 espaços + um *.

* O sinal de menos ( - ) também serve para lista demarcadas.

### Lista de tarefas

-[ ] Sinal de menos + Espaço + Abre colchetes + Espaço + Fecha colchete
- [ ] Beber 4 Litros de água

- [ ] Arrumar o quarto todas as manhas ao acordar

- [X] Para preencher como feito basta voltar no markdown e no lugar do espaço entre os colchetes preencher com um x

- [X] Feito

### Colocando Imagens

Podemos colocar imagem também com markdown, basta arrastar a imagem para o espaço selecionado com "Attach files by ..." O ideal é não usar imagens muito grande, tamanho maximo 400px a 500px.

Exemplo: 400px

![constructocat2](https://github.com/gustavoguanabara/git-github/assets/92768408/fa7acab0-1ec4-4c47-a4d3-7358e13e5fee)

Podemos criar Links, para isso basta escrever entre colchetes [] e colocar o link que desejamos entre ():

[Acesse meu gitHub](https://github.com/kauarasera)

### Criando tabelas

1. 1º colocar os títulos das colunas
1. Em baixo ne cada nome vai colocar sem espaço - - - |
1. Depois é só preencher dando um espaço e colocando |

_Exemplo_
num | nome | Nota
--- | --- | ---
1 | João | 8,5
2 | José | 10,0
3 | Maria | 9,0

__*Terminou a Tabela*__

### __Digitando Comandos__

1. Para digitar um comando Basta.escreverEle Entre crases ``.
   1. Não entendo direito para que serve o comando `document.getElementById()` da linguagem JavaScrip.

1. Para digitar um trecho de um programa colocamos 3 crases no começo e 3 crases no final.
1. Cada tabulação são 3 espaços

__Olha meu trecho em JAVA__

```
Scanner leia = new Scanner(System.in);
int num = 0;

System.out.println("Digite um valor");
num = leia.nextInt();

if( num % 2 == 0) {
    System.out.println("O valor " + num + " é PAR!");
} else {
    System.out.println("O valor " + num + " é ÍMPAR!");
}    
```

Em caso de duvida em relação a um código você pode colocar uma imagem, lembrando de não deixa-la muito grande.

*Exemplo*
Galera não entendi direito esse trecho do código:
![Capturar](https://github.com/gustavoguanabara/git-github/assets/92768408/fea43424-c044-40ed-8c01-753f0b76bd84)

### Emojis

* Com  : + inicioDoNomeDoEmoji você consegue colocar emojis nos readmes, comentarios de repositórios, issue.
*  Esse repositório tem todos os emojis que você precisa [clicando aqui](https://github.com/ikatyang/emoji-cheat-sheet)

*exemplo*
__Olá, pequeno gafanhoro 🖖

Caso queira colocar um emoji no titulo de um repositório ou Issue é só acessar esse site [clicando aqui ](https://emojipedia.org/) e copiar o emoji e colar no seu repositório.

Podemos realizar citações de qualquer pessoa que possui GitHub basta colocar o @ do usuário: como diria @gustavoguanabara "é isso galera"

Para responder um comentário podemos clicar nos 3 pontinhos do comentário da outra pessoa e selecionar a opção Quote reply e escrever o que desejamos sobre o comentário.

Para criar um Quote basta colocar o sinal de maior >

*exemplo*

> Será que vai chover hoje?

## __*Saiba mais*__

* Acesse o manual completo que está no repositório do professor @gustavoguanabara 
[clicando aqui](https://github.com/gustavoguanabara/git-github/blob/master/manuais-PDF/guia-markdown.pdf)