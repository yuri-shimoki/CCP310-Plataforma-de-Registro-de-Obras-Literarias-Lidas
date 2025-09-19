[TODO]:
- Prototipação de baixo nível.

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

- Persona Primária: Mariana, a leitora ávida 
  - Idade e perfil: Mariana tem 32 anos, é professora de literatura em uma escola particular de São Paulo. Lê em média quatro livros por mês, variando entre clássicos, romances contemporâneos e não-ficção.
  - Contexto social: Participa de um clube do livro quinzenal com amigos e mantém um perfil ativo no Instagram, onde compartilha resenhas e trechos favoritos. Também frequenta feiras literárias e eventos culturais.
  - Contexto econômico: Classe média-alta. Tem uma estante cheia de livros físicos, mas também usa um Kindle para leituras mais práticas. Viaja anualmente para participar de eventos literários.
  - Contexto cultural: Grande admiradora da literatura nacional, acompanha lançamentos editoriais e lê também em inglês e espanhol. Considera a leitura não apenas um lazer, mas parte central de sua identidade.
  - Objetivos com a plataforma: Manter um histórico confiável das leituras, evitar comprar livros repetidos e registrar suas impressões para futuras discussões em sala de aula ou nos clubes de leitura.

- Persona Secundária: Lucas, o leitor casual
  - Idade e perfil: Lucas tem 24 anos, está no último ano da faculdade de Administração. Costuma ler de forma irregular, geralmente motivado por recomendações de amigos ou por livros que estão em alta nas redes sociais.
  - Contexto social: Passa boa parte do tempo no TikTok e no Instagram, onde segue influenciadores literários. Quando lê, compartilha stories mostrando o progresso, mas sem se aprofundar em resenhas.
  - Contexto econômico: Classe média. Tem um celular moderno e usa aplicativos diariamente, mas não costuma comprar muitos livros físicos. Ele prefere aproveitar promoções de e-books ou pegar emprestado em bibliotecas digitais.
  - Contexto cultural: Lê para relaxar entre períodos de estudo e trabalho. Gosta de romances de fantasia, thrillers e best-sellers. Não tem rotina de leitura fixa e pode passar meses sem abrir um livro.
  - Objetivos com a plataforma: Quer um espaço rápido e prático para anotar o que já leu e o que deseja ler. Não tem paciência para sistemas complexos — precisa de algo simples, direto e visualmente atraente.

- Persona Negativa: Rogério, o fã de séries
  - Idade e perfil: Rogério tem 28 anos, trabalha como entregador de aplicativo e dedica quase todo o tempo livre a maratonar séries e assistir vídeos no YouTube. Não tem o hábito de ler livros.
  - Contexto social: Conversa sobre filmes e séries com amigos e participa de grupos de WhatsApp que discutem cultura pop. Não tem contato com clubes de leitura ou eventos literários.
  - Contexto econômico: Classe média-baixa. Tem um smartphone com bom acesso à internet, mas não compra livros nem investe em dispositivos de leitura.
  - Contexto cultural: Prefere consumir conteúdo audiovisual e se informa sobre cultura através de streamings e redes sociais. Não acompanha lançamentos editoriais nem sente necessidade de organizar leituras.
  - Objetivos com a plataforma: Nenhum. Rogério não usaria a aplicação, pois não enxerga valor em registrar leituras que praticamente não existem no seu cotidiano.

O serviço deve armazenar as seguintes informações sobre o usuário:
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

### Persona primária
Mariana descobre a plataforma através de uma recomendação em um grupo de leitura no WhatsApp. Uma amiga comenta que agora consegue organizar todas as leituras sem se perder em planilhas ou anotações soltas. Curiosa, Mariana baixa o aplicativo no celular.

No primeiro acesso, ela é recebida por uma interface limpa e intuitiva. Cria sua conta rapidamente com nome e senha, e logo vê a opção de começar a registrar suas leituras. O primeiro livro que adiciona é o romance que acabou de terminar no fim de semana. Ela digita o título, encontra a capa e registra como “lido”, atribuindo uma nota e um breve comentário — algo que poderá usar depois em sala de aula com seus alunos.

Nos dias seguintes, o hábito se integra à sua rotina. Quando está no transporte público, atualiza o status de um novo livro para “lendo”. Em reuniões do clube do livro, consulta o aplicativo para lembrar de anotações que fez semanas antes. Em uma visita à livraria, escaneia o código de barras de uma obra recém-lançada e a adiciona à lista de “desejados”.

Com o tempo, sua biblioteca digital cresce e se torna um registro pessoal confiável. Ao final do mês, Mariana recebe um resumo de tudo o que leu — algo que a deixa motivada e orgulhosa de manter a disciplina. A tarefa sempre começa de forma simples, seja ao finalizar ou iniciar um livro, e termina com a sensação de segurança e organização. Para Mariana, a plataforma não é apenas um apoio, mas um companheiro que valoriza sua trajetória como leitora.

### Persona Secundária
Lucas descobre a plataforma de forma diferente: navegando pelo Instagram, vê um influenciador literário que ele segue mostrando como organiza suas leituras no app. Sem pensar muito, baixa o aplicativo mais pela curiosidade do que pela necessidade.

Ao abri-lo pela primeira vez, Lucas aprecia a simplicidade. Em menos de dois minutos, cria sua conta e já adiciona o livro que começou a ler recentemente, um best-seller de fantasia que viu recomendado no TikTok. Marca como “lendo” e deixa a aplicação de lado.

Dias depois, quando termina o livro durante um fim de semana, lembra-se da plataforma. Abre novamente, altera o status para “lido” e, com rapidez, dá uma nota sem escrever comentários longos. Semanalmente, ao ver promoções de e-books ou indicações em vídeos curtos, ele adiciona títulos à lista de “desejados” para não esquecer.

A interação é prática e sem esforço. Lucas não busca criar um grande histórico detalhado, mas gosta de ter um lugar simples para lembrar o que já leu e o que ainda pretende ler. A jornada dele é marcada por picos de engajamento: começa sempre com um estímulo externo (um livro da moda, uma recomendação de amigo ou uma promoção) e termina com poucos cliques, sem fricção. Para Lucas, a plataforma funciona como um lembrete visual e descomplicado, que evita que ele se perca em leituras ocasionais.

## Análise de concorrência

- Serviços concorrentes:
  - Skoob
  - Goodreads
  - Basmo

Os serviços concorrents atendem ao mesmo mercado e mesma funcionalidade.

Pontos positivos da concorrência:
- Pesquisa com filtro
- Pesquisa de livro por identificadores alternativos ao título (ISBN, autor, gênero, etc)
- Cada livro possui uma página própria com nota média, sinopse, capa, entre outras informações
- Expandem a ideia inicial para uma rede social literária, criando não apenas uma ferramente para o usuário, mas um espaço de socialização para pessoas com um interesse em comum (livros)

Pontos negativos da concorrência:
- Interface não muito agradável visualmente
- Interface não tão simples (conteúdo em excesso)
-

Plataformas diferentes quanto ao serviço que atendem ao mesmo mercado:
- Excel
- Bloco de notas
- Existe plataforma diferente quanto ao serviço, mas que atenda esse mercado? Se sim: Quais os pontos positivos? Quais os pontos negativos?

## Coleta de dados

### Questionário
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

### Roteiro de Entrevista
- Objetivo: Descobrir as motivações, dificuldades e expectativas dos usuários em relação ao registro de leituras.
- Como realizar
  - Seleção de participantes: Entre 4 e 8 pessoas.
  - Misturar perfis: leitores ávidos (ex.: professores, estudantes de Letras) e leitores casuais (ex.: jovens adultos que leem por modas ou recomendações).
  - Formato: Pode ser online (Google Meet, Zoom) ou presencial.
  - Duração: entre 20 e 30 minutos por participante.
  - Gravar (com permissão) para análise posterior.
- Roteiro:
  - Hábito de leitura:
    - Quantos livros você costuma ler por mês/ano?
    - Você tem uma rotina de leitura ou lê quando sobra tempo?
  - Registro:
    - Você costuma registrar os livros que lê? Como faz isso?
    - O que te motiva ou desmotiva a manter esse registro?
  - Problemas enfrentados:
    - Já aconteceu de comprar ou pegar um livro repetido porque esqueceu que já tinha lido?
    - Você sente dificuldade em lembrar detalhes de livros que leu?
  - Tecnologia:
    - Já usou algum app para organizar suas leituras? Como foi a experiência?
    - O que seria indispensável para você em uma aplicação desse tipo?
  - Desejos:
    - Se pudesse mudar algo na forma como organiza suas leituras, o que seria?
- Resultados esperados
  - Relatos que mostrem dores reais (ex.: “anoto no caderno mas sempre esqueço onde coloquei”).
  - Expectativas claras de funcionalidades (ex.: “queria algo rápido, sem muitos botões”).

### Observação Pura, Sem Interação do Observador com Os Participantes
- Seleção de participantes
  - Convidar usuários com perfis diferentes (um leitor ávido, um casual).
  - Pedir permissão para acompanhar em um momento real de leitura ou organização.
- Formato
  - Pode ser presencial (acompanhar alguém em casa, na biblioteca ou café) ou remoto (o usuário compartilha tela ou grava um vídeo mostrando seu processo).
  - O pesquisador não interfere: apenas observa e anota.
- O que observar
  - Ambiente: onde a leitura/organização acontece (ex.: celular, caderno, planilha no PC).
  - Ações concretas:
    - Como ele registra ou deixa de registrar a leitura.
    - Quais passos executa (ex.: abrir notas no celular, procurar livro em app, escrever em agenda).
  - Dificuldades visíveis:
    - Demora para encontrar um título.
    - Bagunça em anotações.
    - Confusão com status (lido, desejado, em leitura).
  - Atalhos criativos:
    - Uso de marcações improvisadas.
    - Registro em redes sociais como substituto de um app.
- Resultados esperados
  - Identificação de barreiras práticas (ex.: “demorou 3 minutos para achar o livro na planilha”).
  - Entendimento de comportamentos reais, que muitas vezes diferem do que a pessoa diz em entrevistas.

## Modelo de tarefas

## Tarefas Principais

**Tarefa 1:** Criar Conta e Acessar a Plataforma
- **Objetivo:** Permitir que o usuário crie uma conta e acesse a plataforma.
- **Operadores:**
  - Digitar informações (ex: nome/apelido e senha)
  - Selecionar botões (ex.: "Criar conta" e "Entrar")
- **Métodos:**
  - **Criar conta**
    - Abrir a aplicação
    - Selecionar "Criar conta"
    - Inserir nome/apelido
    - Inserir senha
    - Clicar em "Registrar"
  - **Fazer login**
    - Abrir a aplicação
    - Inserir nome/apelido
    - Inserir senha
    - Clicar em "Entrar"
    - Acessar tela inicial da plataforma
  - **Regras de Seleção**
    - Se o usuário não tem conta, segue o método Criar conta.
    - Se o usuário já tem conta, segue o método Fazer login.

**Tarefa 2:** Registrar e Gerenciar Livros
- **Objetivo:** Permitir que o usuário registre livros (lidos, lendo, desejados), adicione notas/comentários e consulte seu histórico.
- **Operadores:**
  - Digitar título do livro
  - Selecionar status (lido, lendo, desejado)
  - Inserir nota/comentário
  - Confirmar registro
  - Pesquisar no histórico
  - Editar ou remover registros
- **Métodos:**
  - **Adicionar novo livro**
    - Acessar tela "Adicionar livro"
    - Digitar título ou escanear código de barras
    - Selecionar status (lido, lendo, desejado)
    - (Opcional) Inserir nota/comentário
    - Clicar em "Salvar"
  - **Atualizar status de um livro**
    - Acessar lista de livros
    - Selecionar livro desejado
    - Alterar status (ex.: de "lendo" para "lido")
    - (Opcional) Inserir nota/comentário adicional
    - Confirmar atualização
  - **Consultar histórico**
    - Acessar tela "Minha lista"
    - Pesquisar por título ou filtrar por status
    - Visualizar detalhes (notas, comentários, datas)

- **Regras de Seleção:**
  - Se o livro ainda não está registrado, usar o método Adicionar novo livro.
  - Se o livro já está registrado, usar o método Atualizar status.
  - Se o usuário quer apenas consultar, usar o método Consultar histórico.

## Tecnologias
**Front-end:**
- HTML
- CSS
- JavaScript

**Back-end:**
- Node.js
  - Express
- MongoDB

**Prototipação:**
- Canva

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














