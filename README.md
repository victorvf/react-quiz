<h1 align="center">
    <img alt="react" src=".github/react.png" width="300px" />
</h1>

<p align="center">
  <a href="#bulb-sobre">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-perguntas">Perguntas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#book-referências">Referências</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-contribuição">Contribuição</a>
</p>

#### :bulb: Sobre:
- Este repositório tem como intuito reunir as principais perguntas sobre React para levar conhecimento a todos e agora também com uma lista das principais tags do [HTML](https://github.com/victorvf/react-quiz/blob/master/HTML.md)!

#### :memo: Perguntas:

1. **O que é React ?**
    - É uma biblioteca Javascript de código aberto com foco em criar interfaces de usuário em páginas web.

2. **Porque utilizar React ?**
    - Rápido e escalável
    - Simples entendimento e de fácil aprendizado
    - Serve também como base para a construção de aplicativos mobile

3. **O que é DOM virtual no React ?**
    - É um conceito de programação onde uma representação ideal, ou "virtual", da interface do usuário é mantida em memória e sincronizada com o DOM "real" por uma biblioteca como o ReactDOM. Esse processo é chamado de reconciliação.

4. **O que é JSX ?**
    - Em resumo, JSX é uma sintaxe semelhante ao XML, onde você consegue escrever e compreender de uma melhor forma, como será montado o seu component na UI.

5. **O que são Componentes no React ?**
    - São como funções Javascript. Eles aceitam entradas arbitrárias (chamadas "props") e retornam elementos React que descrevem o que deve aparecer na tela, em outras palavras, são partes independentes da UI, reutilizáveis e que cada parte pode ser pensada isoladamente.

6. **Quais são os estágios do ciclo de vida de um Componente ?**
    - Inicialização (Componente inserido na DOM)
    - Atualização de estados (Quando setamos os valores dos estados)
    - Destruição (Componente é removida da DOM)

7. **Os navegadores web podem ler JSX ?**
    - Não, os navegadores só conseguem ler objetos javascript, então o React fica responsável por fazer toda a tratativa do JSX e retornar somente o que o Navegador entenda.

8. **Qual a diferença entre React e React Native ?**
    - React como mencionado acima, é uma biblioteca Javascript com foco em criar interfaces de usuário em páginas web e o React Native é um framework baseado no React, porém reune todos os recursos necessários para a construção de aplicativos mobile, com seus componentes nativos, em vez de componentes web.

9. **O que é Flux ?**
    - é a arquitetura de aplicativos que o Facebook utiliza para criar aplicativos da Web no client-side. Ele complementa os componentes em exibição, utilizando um fluxo de dados unidirecional.

10. **Como o React faz o uso de "Keys" ?**
    - O React utiliza as keys para identificar quais itens sofreram alterações, foram adicionados ou removidos. Dando assim uma identidade estável aos elementos.

11. **Diferença entre Componente de container (container component) e Componente de apresentação (presentational component) ?**
    - Componente de container é o pai, o component "inteligente", é ele quem carrega os dados, manipula os *States* e entrega tudo para o Componente de apresentação, que só tem o trabalho de receber as *props* e fazer o *render* de tudo.

12. **Para que o "setState" é utilizado ?**
    - Para fazer a tratativa do estado atual, caso você queira atualizar uma informação, ou adicionar um informação ao estado atual, basta chama-lo e ele irá mesclar o que foi passado ao estado atual, sendo a interface do usuário atualizada com o novo estado.

13. **O que faz o "render()" ?**
    - Renderiza um elemento do React no DOM.

14. **O que são os "synthetic events" ?**
    - São basicamente os mesmo eventos de um navegador, porém com a diferença de que eles utilizam um código que pode ser aplicado através de vários navegadores diferente, enquanto os eventos normais só têm como alvo um único navegador.

15. **O que é um "state" ?**
    - Basicamente um objeto que contêm dados. Onde os dados contidos neles podem ser alterados durante o tempo de vida de um Componente, utilizando o já mencionado *setState*.

16. **O que são "props" ?**
    - É um objeto que pode ser passado a um Componente, contendo atributos JSX e componentes filhos.

17. **O que são "erros boundaries" ?**
    - São componentes React que capturam erros de Javascript em qualquer lugar na sua árvore de componentes filhos, registram esses erros e mostram um UI alternativa em vez da árvore de componentes que quebrou.

18. **O que é redux ?**
    - basicamente uma biblioteca JavaScript que gerencia estados globais que segue os princípios da arquitetura flux.

#### :book: Referências:

- https://br.bitdegree.org/tutoriais/react-js/#Introducao
- https://pt-br.reactjs.org/docs/getting-started.html
- https://medium.com/reactbrasil/jsx-de6f43b06f41#:~:text=O%20que%20%C3%A9%20JSX%3F,o%20seu%20component%20na%20UI.
- https://reactnative.dev/docs/tutorial
- https://facebook.github.io/flux/
- https://www.mundojs.com.br/2019/08/01/diferencas-entre-react-native-e-react-js/#page-content
- https://www.webdevdrops.com/react-tipos-de-componentes-container-e-apresentacao/

#### :computer: Contribuição:

- Sinta-se a vontade para contribuir com este projeto. Basta você fazer um **fork** do projeto, abri uma **Pull Request** e seguir alguns padrões descritos abaixo, bem simpĺes!

- :warning: **Padrões a ser seguidos:**
    1. As perguntas devem conter as referências de suas respectivas respostas, caso ela não esteja contida na seção de [Referências](#book-referências).
    2. *Commits:* Gostaria que os commits seguissem este padrão:
        - "chore(numero da questão ou local de modificação): mensagem" -> quando for feita modificação em uma questão ou seção já existente.
        - "feat: mensagem" -> quando for adicionada alguma questão ou seção nova.
    3. Caso um *Seção* nova seja adicionada com fotos, as fotos devem ficar na pasta **.github**

#### Obrigado pela contribuição! :two_hearts: :two_hearts: :two_hearts: