# **Tema escolhido:** Plataforma de Registro de Obras Literárias Lidas

Trabalho de Experiencia do Usuário (UX) apresentado ao Centro Universitário [FEI](https://portal.fei.edu.br/), como parte dos requisitos necessários para aprovação na disciplina de Experiência do Usuário e Front-End (CCP310) do curso de Ciencia da Computação, orientado pelo Prof. Dr. [Fagner de Assis Moura Pimentel](https://github.com/fagnerpimentel).

## Componentes do Grupo

- Yuri da Silva Shimoki
- Marcelo Boalento do Nascimento

## Resumo

Plataforma que busca auxiliar os usuários na organização das obras literárias já lidas.

## Introdução

- Contextualização: Leitores ávidos podem facilmente perder noção do que já leram ou não após anos de leitura. Isso pode ser problemático de algumas formas, como o leitor pode não intencionalmente comprar um livro já lido ou esquecer o nome de uma obra que ele gostou. Esta plataforma é necessária para resolver esses tipos de problemas que leitores frequentemente enfrentam e que só piora com o passar do tempo.
- Linha de resumo: Auxiliar o usuário no registro de livros lidos.
- Experiência que deve proporcionar: Uma experiência sem dificuldades e direta, tendo em vista a simplicidade da aplicação.

## Publico Alvo

- Público alvo: Leitores de 16 ou mais anos de idade buscando organizar suas leituras.

### Personas

- Quais informações sobre o usuário o serviço ou poduto deve guardar?

- Persona Primária: Leitor Ávido
  - Perfil: Adulto (25–45 anos), leitor frequente. Costuma ler vários livros por mês.
  - Contexto social: Participa de clubes de leitura, fóruns online e redes sociais literárias.
  - Contexto econômico: Classe média ou média-alta, com acesso a dispositivos móveis e internet de qualidade.
  - Contexto cultural: Alto interesse por literatura nacional e internacional, acompanha lançamentos editoriais e eventos literários.

- Persona Secundária: Leitor Casual
  - Perfil: Jovem adulto ou adulto (18–35 anos). Lê esporadicamente, motivado por indicações ou modas literárias.
  - Contexto social: Usa redes sociais para descobrir livros, segue influenciadores literários.
  - Contexto econômico: Classe média, acesso a smartphone e internet, mas não investe muito em livros físicos (prefere e-books ou bibliotecas).
  - Contexto cultural: Interesse variado, lê para lazer ou estudo, mas sem rotina fixa

 - Persona negativa: Desinteressado em Livros
   - Perfil: Prefere consumir conteúdo audiovisual (filmes, séries, vídeos curtos) e raramente lê livros.
   - Contexto econômico: Classe baixa ou média. Possui acesso a dispositivos e internet de alta velocidade, mas não investe em livros ou e-readers.
  - Contexto cultural: Não acompanha lançamentos literários, não participa de clubes de leitura e não tem interesse em registrar ou organizar leituras.

O serviço deve armazenas as seguintes informações sobre o usuário:
- Nome ou apelido
- Senha
- Lista de livros
  - A marcação de cada livro: lido, lendo e desejado.
  - Nota e/ou comentário em cada livro.

### Mapa de empatia

![Mapa de empatia](empatia.png)

- Persona Primária:
  - O que vê:
    - Conteúdo dos livros e livros disponíveis para compra
    - Bibliotecas e lojas de livro
    - Redes sociais literárias
    - Lançamentos editoriais e eventos literários
  - O que ouve:
    - Resenhas sobre livros
    - Discussões sobre o desenvolvimento de uma trama
    - Comparações entre obras
    - Recomendações de amigos, clubes de leitura e influenciadores
    - Notícias sobre prêmios literários e adaptações cinematográficas
  - O que fala e faz:
    - Participa ativamente de grupos de leitura
    - Compartilha resenhas e notas sobre livros
    - Compra livros físicos e digitais com frequência
    - Lê livros com frequência
  - O que pensa e sente:
    - Preocupação em manter um registro organizado de tudo que já leu
    - Desejo de compartilhar opiniões e recomendações com outros leitores
    - Sente frustração ao esquecer detalhes de livros ou reler algo sem perceber
  - Dores:
    - Dificuldade em lembrar todos os livros já lidos
    - Perde tempo procurando anotações antigas
    - Repete compras de livros já lidos
    - Plataformas pouco práticas para registro rápido
  - Ganhos:
    - Tempo salvo em uma tarefa que iria requerir muito mais esforço manual e tempo do que o desejado.
    - Registro simples e rápido de leituras
    - Histórico confiável e acessível em qualquer dispositivo
    - Possibilidade de adicionar notas e comentários

- Persona Secundária:
  - O que vê:
    - Postagens ocasionais de influenciadores literários nas redes sociais
    - Promoções de e-books e livros físicos
    - Tendências literárias momentâneas
    - Aplicativos com excesso de recursos que não usa
  - O que ouve:
    - Indicações de amigos e familiares
    - Comentários sobre livros populares ou adaptados para filmes/séries
    - Sugestões de leitura em podcasts e vídeos curtos.
  - O que fala e faz:
    - Compartilha ocasionalmente o que está lendo nas redes sociais
    - Compra livros por impulso, muitas vezes motivado por modas
    - Alterna períodos de leitura intensa com longos intervalos sem ler
  - O que pensa e sente:
    - Quer registrar leituras de forma prática, sem gastar muito tempo
    - Busca inspiração para próximas leituras
    - Sente satisfação ao concluir um livro, mas não tem hábito de anotar detalhes
    - Não quer lidar com plataformas complexas
  - Dores:
    - Esquece o nome de livros que gostou
    - Não ter um histórico organizado de leituras
    - Falta de motivação para manter registros manuais
    - Plataformas que exigem muito tempo para atualizar
  - Ganhos:
    - Registro rápido e intuitivo
    - Interface simples e visualmente agradável
    - Possibilidade de marcar livros como “desejados” para lembrar depois

## Contexto de uso

- Ambiente de utilização: O serviço será utilizado principalmente através de navegadores via dispositivos móveis (smartphones e tablets) e computadores. O usuário em si pode se encontrar em sua própria casa, em uma biblioteca, livrarias, tempos de deslocamento (carro, transporte público) ou cafés e espaços de leitura. O ambiente é informal e flexível.
- Contexto social: Usuários podem estar conectados a comunidades literárias, clubes de leitura e redes sociais.
- Contexto econômico: Público com acesso a dispositivos móveis e internet estável. Pode incluir tanto leitores que compram livros físicos regularmente quanto aqueles que preferem e-books ou bibliotecas públicas. Usuários geralmente de classe média.
- Contexto cultural: Valorização da leitura como hábito e forma de lazer ou estudo. Interesse por literatura nacional e internacional. Influência de tendências literárias, adaptações para cinema/TV e indicações de influenciadores.
- Informações guardadas antes da interação: usuário atual (nome e senha). 
- Ambiente quando o usuário interage:
  - Finalizou um livro
  - Começou um livro ou vai começar
  - Está tentando referenciar um livro que já leu (pesquisa pelo histórico)
  - Deseja atualizar a lista

## Jornada do usuário

- Criar uma narrativa para o o seu serviço ou poduto com o usuário.
- Determine o que o usuário realiza desde a primeira até o última interação com o serviço ou poduto.
  - Descreva o que acontece ou pode acontecer passo a passo
  - Como a tarefa começa? Como a tarefa se desenvolve? Como a tarefa termina?

 Narrativa:

Assim que descobre o aplicativo, o usuário sente curiosidade. Talvez tenha visto uma recomendação em uma rede social literária ou tenha se lembrado de um episódio recente em que comprou um livro que já havia lido. Ele baixa o app e, ao abri-lo pela primeira vez, é recebido por uma tela simples e convidativa, que explica em poucas palavras a proposta: ajudar a registrar e organizar todas as leituras de forma prática. Sem enrolação, ele cria sua conta usando um nome e uma senha e já está pronto para começar.

A primeira ação é buscar um livro que acabou de ler. Ele digita o título na barra de pesquisa e, em segundos, vê a capa e as informações correspondentes. Com um toque, adiciona o livro à sua lista e marca como “lido”. O aplicativo sugere que ele dê uma nota e escreva um breve comentário, e ele aproveita para registrar suas impressões enquanto ainda estão frescas. Ao salvar, sente a satisfação de ver o título aparecer no seu histórico, inaugurando sua biblioteca pessoal dentro da plataforma.

Nos dias seguintes, o uso se torna natural. Quando está no transporte público lendo um novo romance, abre o app para atualizar o status para “lendo” e anotar uma frase que o marcou. Ao visitar uma livraria, pega um livro que chamou sua atenção e, antes de decidir comprá-lo, escaneia o código de barras pelo aplicativo. A resposta é imediata: o título já está na sua lista de desejados, adicionado semanas atrás quando um amigo o recomendou. Ele sorri, feliz por não deixar essa informação escapar.

Com o tempo, o histórico cresce. O usuário passa a consultar o aplicativo não apenas para registrar, mas também para relembrar leituras passadas, buscar por autor ou gênero, e até para revisitar comentários antigos. Ao final de cada mês, recebe um resumo das leituras concluídas, o que o motiva a continuar alimentando sua lista. A experiência é sempre rápida e sem fricção, adaptando-se ao momento: seja para uma atualização de poucos segundos, seja para uma consulta mais detalhada.

A tarefa começa sempre com um gatilho simples — terminar um livro, encontrar um título novo ou lembrar de algo que leu — e se desenvolve de forma intuitiva, com o usuário navegando por buscas, marcações e anotações sem esforço. Ela termina com a sensação de controle e organização, sabendo que sua trajetória literária está registrada de forma segura e acessível. E, assim, cada interação reforça o hábito, transformando o aplicativo em um companheiro constante de leitura.

## Análise de concorrência

- Pesquise serviços ou podutos existentes atualmente que possam realizar o objetivo deste projeto.
- Selecione pelo menos 3 serviços ou podutos diferentes.
- Em relação aos concorrentes, respondam as seguintes perguntas?
  - Existe plataforma similar que atende o mesmo mercado e funcionalidades? Se sim: Quais os pontos positivos? Quais os pontos negativos?
  - Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

https://forms.gle/9UxkLfUVRwu7GDcJ6

Pergunta 1: Com que frequência você lê livros?
- Alguns livros por ano
- Raramente ou nunca
- Vários livros por mês
- Um livro por mês

Pergunta 2: Qual é o seu principal motivo para registrar os livros que lê?
- Acompanhar metas de leitura
- Organizar e lembrar o que já li
- Não costumo registrar minhas leituras
- Compartilhas opiniões com outros leitores

Pergunta 3: Como você costuma descobrir novos livros para ler?
- Promoções e tendências literárias
- Recomendações de clubes de leitura e influenciadores
- Não costumo buscar novos livros
- Sugestões de amigos e redes sociais

Pergunta 4: Você costuma fazer anotações ou comentários sobre os livros que lê?
- Raramente faço anotações
- Nunca faço esse tipo de registro
- Às vezes, quando o livro me marca
- Sim, sempre registro minhas impressões

Pergunta 5: Qual tipo de interface você prefere em um aplicativo de leitura?
- Completa, com muitas funcionalidades
- Simples e direta, sem distrações
- Não uso aplicativos de leitura
- Visualmente agradável, com recursos básicos

## Modelo de tarefas

## Design

- Pense nas características de Affordances do seu serviço ou poduto. 
    - Que tipo de acessibilidades devem ser consideradas dentro do seu projeto?
- Discuta o papel das expectativas do usuário no projeto deste serviço ou poduto. Qual a importância e pontos a serem considerados se você quiser vender esse serviço ou poduto?

### Prototipação em baixo nível (papel)
#### Avaliação heurística

### Prtotipação em médio nível (Figma)
#### Avaliação heurística

### Prtotipação em alto nível (React)
#### Avaliação heurística

[^1]: Fonte: Adaptado de <https://hazeshift.com.br/mapa-de-empatia/>

<!-- TODOs:
- Add exemplos
 -->




