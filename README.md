Alinhar que é uma SIMULAÇÃO, que lógico que o trabalho em grupo tem muito mais código mas que a forma de resolver é a mesma e caso tenha dado algum conflito grande, chamar o time pra ajudar a resolver.

=== 1° Dia ===

Jensen: compartilha a tela 

"Vamos organizar o trello, precisamos criar:

  - Função de somar
  - Função de dividir
  - Função de multiplicar
  - Função de subtração
  - Função de potenciação

- Cria o texto com "Calculadora", commita e da push!
- Vamos só trocar o texto de dentro do App.js todos juntos e vocês dão o pull!
  
- Leticia: Cria a branch feat/add e troca o texto pra 'Calculadora mágica!!' e acrescenta a função
  add(a, b) {
    return a + b
  }

- Abre PR e coloca Jensen pra code review
- Mergeia

- Isaac abre a branch feat/divide, sem fazer o pull da main
- Cria função de divide

  divide(a, b) {
    return a / b;
  }

  - commita e dá push
    - É pra dar conflito!
  
  - Isaac fica muito bravo!
  
=== 2° Dia ===
- Jensen de Scrum Master, pede pra iniciar, chamando a Leticia
- Leticia: ontem eu fiz a função de somar, hoje vou pegar a função de multiplicar e sem impedimentos
- Isaac: ontem eu fiz a função de dividir e fiquei horas tentando resolver o conflito, tive que pesquisar no google como fazia, mandei mensagem e ninguém me respondeu. Então eu vi que tinha que dar um pull da main, na hora que dei o pull da main apareceu o conflito no vscode e eu não sabia resolver, ninguém me avisou que tinha code review pra fazer e não recebi notificação nenhuma e agora tô com esse impedimento, tô travado com isso e não sei como vou fazer, porque quando eu abri o vscode...

Jensen interrompe e diz que se ficar entrando em detalhes vai levar muito tempo e completa: "Então vamos lá, ontem você fez a função de divide, teu impedimento é que você tá conflito e hoje vai precisar de ajuda pra resolver, certo?"

- Isaac: É! Tem que tomar cuidado com isso, porque assim fica difícil...
  
- Jensen: Dá uma acalmada no Isaac e complementa: falha nossa, vamos lá, sempre notificar todas as pessoas do time pra fazer o code review, beleza? E sempre avisar quando for dado o merge e antes de dar push no código, sempre dar um pull da main. Combinado?

Leticia e Isaac: combinado!

Jensen: ontem eu organizei melhor o trello com as descrições e hoje eu vou fazer a função de subtração

Isaac: Cria a função de multiplicação na branch feat/multiply, sobe e pede Code Review da Leticia e do Jensen
- Commita com uma mensagem nada vê.
  
  multiply(a, b) {
    return a - b;
  }

Jensen reprova e pede pra fazer alterações.


=== 3° Dia ===

Leticia não aparece.

Jensen: E aí Isaac, o que você fez ontem, o que vai fazer hoje e se tem algum impedimento?

Isaac: Ontem eu fiz a função multiply, mas vi o seu code review e hoje vou resolver isso e amanhã eu inicio a de potenciação.

Jensen: Beleza! Hoje eu termino a de subtração, não consegui terminar ontem porque agarrei num bug, mas já descobri como resolver e hoje eu termino.

Isaac: A Leticia não vem hoje?

Jensen: Mandei mensagem e ela não respondeu

Isaac arruma a função de multiply, sobe e pede o review novamente.
Jensen aprova, avisa no grupo e mergeia.

Jensen termina a função de subtração e pede review do Isaac e da Leticia.

=== 4° Dia ===
Leticia aparece

Jensen: Tá tudo bem, aconteceu alguma coisa?

Leticia: Ah não, só resolvi tirar o dia de folga e fui no cinema

Jensen: fala que isso não pode acontecer, que tem que avisar, blábláblá. 
Jensen: Mas vamos lá, Isaac, o que você fez ontem, o que vai fazer hoje e se tem algum impedimento.

Isaac: ontem eu arrumei a função de multiplicação e hoje vou pegar mais uma task.

Jensen: Ontem eu terminei a função de subtração e meu impedimento é que preciso do code review pra poder pegar outra tarefa hoje.

Leticia: Desculpa pelo vacilo de ontem! Lição aprendida! Hoje eu vou fazer os review e ver quais tasks ainda tem pra fazer.

=== Encerramento === 

