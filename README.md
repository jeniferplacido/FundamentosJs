### JavaScript**

##### **JavaScript** (frequentemente abreviado como **JS**) é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem dinâmica e multi-paradigma (protótipos, orientado a objeto, imperativo e funcional). Juntamente com HTML e CSS, o JavaScript é uma das três principais tecnologias da World Wide Web.

![img](https://lh5.googleusercontent.com/gplxdYQH9arY6Q8_eYuJbkR_OqxbI_tLgY5gcs5bHlpZI8utFDFjy0iXkxT2u4suvviDBmLCTTOmRHBz2R67rwtS7ulmNOw0NTVyo1YHMkNFKfG6ETqSHK8Hr3OYcdyf4KLkII5mwGrN2Q)

O **JavaScript** permite páginas da Web interativas e, portanto, é uma parte essencial dos aplicativos da web. A grande maioria dos sites usam e todos os principais navegadores têm um mecanismo JavaScript dedicado para executá-lo.

![img](https://lh5.googleusercontent.com/cOaqQz04N0D5VBqaDCH-NJAXEPfBZEAvfHIefGad3a6Qy08BY13_vrSid7YCvh7Mp6FaSflpoFfSMqcBmOYE5hT348aulfdQxoQTVHXmJMAmtrUdkIUWH39_SsEH-9qpr0_4jRktrPA8sA)



Segundo o livro "**Estrutura de dados e algoritmos com javascript**", de Loiane Groner: "**Javascript** é uma das linguagens de programação mais populares atualmente, é conhecida como a linguagem da internet porque os navegadores a entendem de modo nativo, sem a instalação de qualquer plugin."Além disso, a linguagem **Javascript** evoluiu muito e aparecem até em aplicativos mobile(com React Native), Softwares de interface gráfica para Desktop(electron) e até games, robótica e inteligência artificial. Além disso, tem o backend também utilizando o nodejs.

| Pontos Positivos                                             | Pontos Negativos                                             |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Uma ótima linguagem para um primeiro contato com a programação e, por consequência, para se estudar lógica de programação.** | Pode conter brechas para a execução de ações maliciosas      |
| **Sintaxe acessível**                                        | Pode ser renderizada de maneiras diferentes pelos dispositivos compatíveis, causando problemas de desempenho. |
| **Grande comunidade ao redor do mundo fazendo a ferramenta evoluir** | Atualizações nem sempre compatíveis com todos os navegadores e sistemas existentes. |

Algumas linguagens como Java, c#, entre outras, precisam de um software externo para compilar seu código e transformá-lo em algo que seu computador entenda.O javascript não precisa ser compilado, mas precisa ser interpretado, resumindo, o javascript precisa que alguém o entenda para ele funcionar.Um motor interpretador de javascript é o v8, criado e mantido por nada mais, nada menos que o google.

![V8 Google](https://cdn.slidesharecdn.com/ss_thumbnails/v8js-151006130151-lva1-app6891-thumbnail-4.jpg?cb=1444136542)

Variáveis:

#### Variáveis:

"Variáveis armazenam dados que podem ser definidos, atualizados e recuperados sempre que necessário".

Mas como declarar váriaveis no JavaScript?

A gente precisa usar uma palavra reservada do Javascript e um identificador. Além disso, a gente pode atribuir valores para essas variáveis.

É mais ou menos assim:

A palavra reservada: var Identificador: meuNome Atribuindo valor: "Jenifer"

Declarando uma variavel: var meuNome Atribuindo valor: meuNome = Jenifer 

Aqui vão algumas dicas pra você ficar muito expert em declarar variaveis com Javascript

- **O que pode?** Podem começar com letra, $ ou _ É possível usar acento, símbolos e números
- **O que não pode?** Não pode começar com número Não pode conter espaço Não podem ser palavras reservadas
- **Qual o ideal?** Ter atenção, pois é case sensitive Use nomes coerentes

Além disso, é também importante saber que a linguagem Javascript evolui a cada ano. E desde 2015, tem havido uma nova versão lançada a cada ano que chamamos de ECMAScript. Então não se assuste se você esbarrar com frenquencia nesse conceito por aí. ECMA é uma organização que padroniza informações, e o JavaScript foi submetido à ECMA para que fosse padronizado daí nasceu o ECMAScript, o novo padrão da linguagem.

A mudança mais significativa na linguagem ocorreu em 2015 e é conhecida com ECMAScript 6 ou ES6, ela surgiu pra linguagem ficar mais flexivel no uso com o paradigma orientado a objeto. E aqui nas variáveis surgiram as palavras reservadas let e const.

Então agora você pode declarar variaveis das seguintes formas:

let linguagem = "Javascript"
const linguagem = "Java"

**Diferenças entre let, const e var:**

- **var** são declarações de escopo global ou de escopo de funções, enquanto let e const são de escopo bloqueado;

- **var** podem ser atualizadas ou reatribuídas nestes escopos;

-  **let** podem ser atualizadas, mas **const** não podem ser atualizadas ou reatribuídas;

- **var** sofrem hoisting de escopo.

  Escopo se refere ao local em que podemos acessar a variavel no algoritmo ou em uma função. E as variáveis podem ser locais ou globais.

  Atividade em aula:

  1- Abra o seu VS Code, crie um arquivo HTML com o nome de index.html

  2- Crie um arquivo meuScript.js 

  3- Dentro do arquivo html coloque o padrão 

  ```
  <!DOCTYPE html>
  <html lang="pt-br">
      <head>
          <meta charset="UTF-8">
          <script src="meuScript.js"></script>
          <title>Aula Js</title>
              </head>
  
  </html>
  ```

  Use a sua criatividade para mostrar uma mensagem, soma ou texto na caixa de alert do navegador.

