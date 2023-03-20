# P1_ComputacaoEmbarcada_2023.1

<h2>Informações Gerais</h2>

<h3>Engenharia de Computação Insper - Computação Embarcada 2023.1</h3>

<h3>Alunos:</h3>
<ul>
  <li><a href=https://www.linkedin.com/in/enrico-damiani-125527196/>Luiz Felipe Lazzaron</a></li>
  <li><a href=https://www.linkedin.com/in/marcosvinis/>Marcos Vinícius da Silva</a></li>
</ul>

<h3>Professor:</h3> 
<ul>
  <li><a href=https://www.linkedin.com/in/rodrigo-carareto-b1ab85b6/>Rodrigo Carareto</a></li>
</ul>

<h2>Informações do Projeto</h2>
<p> 
Este repositório contém o projeto de um controle remoto Bluetooth, que faz parte do escopo fechado do projeto de computação embarcada. O objetivo do projeto é passarmos por todo o ciclo de desenvolvimento de um protótipo de um dispositivo embarcado, desde a especificação até a finalização.
</p>

<p> 
O controle remoto Bluetooth foi projetado para permitir que nós controlemos remotamente um programa em um PC. Ele deve ser específico para a aplicação em questão e ter interface via Bluetooth. O controle remoto deve ser conectado ao kit de desenvolvimento SAME70-XPLD, e deve possuir um módulo externo Bluetooth HC-05.
</p>

<h3>Funcionalidades esperadas</h3>
<p>O protótipo do controle remoto Bluetooth deve ter as seguintes funcionalidades:</p>
<ul>
  <li>Pelo menos quatro entradas digitais e uma entrada analógica</li>
  <li>Pelo menos duas saídas digitais para feedback do usuário no próprio controle</li>
  <li>Interface Bluetooth para comunicação com o PC</li>
  <li>Informação de controle pareado</li>
</ul>

<h3> Ideia: Controle Remoto para Jogos</h3>
<p>
Este projeto consiste na criação de um controle remoto para jogos em PC, utilizando o kit de desenvolvimento SAME70-XPLD e um módulo externo bluetooth HC-05. O objetivo é criar um dispositivo personalizado e específico para jogos, com botões para controle de alguns recursos de jogabilidade.
</p>

<p>
O controle será desenvolvido em linguagem C, e deve ter no mínimo 4 entradas digitais e uma entrada analógica, para permitir uma ampla variedade de comandos. Além disso, ele deve fornecer feedback ao usuário através de ao menos duas saídas digitais, como luzes indicadoras ou vibração.
</p>


<h3>Usuários</h3>
<p>
Os possíveis usuários deste controle remoto para jogos seriam pessoas que gostam de jogar no PC e desejam ter um controle personalizado para melhorar a experiência de jogo. Ele pode ser utilizado por jogadores casuais que desejam mais comodidade e precisão ao jogar jogos de corrida, esportes, luta, RPG, FPS e outros gêneros de jogos. Além disso, ele pode ser utilizado por jogadores mais experientes que procuram um controle com mais funcionalidades e personalização. O projeto é voltado tanto para pessoas que gostam de jogar sozinhas como para aquelas que jogam com amigos ou em competições online.
</p>

<!-- Jornada do usuário casual -->
<h4>Jornada do usuário casual</h4>
<p><strong>Perfil:</strong> João é um estudante universitário que gosta de jogar jogos de corrida no PC nas horas vagas. Ele sempre usou o teclado para jogar, mas tem dificuldade em controlar o carro e manter a velocidade com precisão. Ele gostaria de ter um controle mais intuitivo para melhorar sua experiência de jogo.</p>
<ol>
  <li>João pesquisa na internet sobre controles para jogos de PC e encontra o projeto de Controle Remoto para Jogos no GitHub.</li>
  <li>Ele lê a descrição do projeto e percebe que é exatamente o que ele está procurando. João decide baixar os arquivos e seguir as instruções para montar o controle.</li>
  <li>Ele segue as instruções de montagem e conexão do controle, utilizando o kit de desenvolvimento SAME70-XPLD e o módulo externo bluetooth HC-05.</li>
  <li>João personaliza o design do controle para torná-lo mais ergonômico e adicionar cores e decalques que combinam com seus gostos pessoais.</li>
  <li>Após conectar o controle ao seu PC via bluetooth, ele começa a jogar seu jogo de corrida favorito. João percebe que agora consegue controlar o carro com muito mais precisão e rapidez, melhorando sua pontuação no jogo.</li>
  <li>Ele continua jogando com o controle remoto e experimenta outros jogos de corrida, assim como outros gêneros de jogos. João se diverte muito mais agora com seu novo controle remoto para jogos.</li>
</ol>

<!-- Jornada do usuário experiente -->
<h4>Jornada do usuário experiente</h4>
<p><strong>Perfil:</strong> Ana é uma jogadora experiente que joga jogos de tiro em primeira pessoa em competições online. Ela está procurando um controle personalizado que possa melhorar sua jogabilidade e lhe dar uma vantagem sobre seus oponentes.</p>
<ol>
  <li>Ana pesquisa na internet sobre controles personalizados para jogos de PC e encontra o projeto de Controle Remoto para Jogos no GitHub.</li>
  <li>Ela lê a descrição do projeto e percebe que é exatamente o que ela está procurando. Ana baixa os arquivos e segue as instruções para montar o controle.</li>
  <li>Ela utiliza seu conhecimento em programação para customizar o controle, adicionando novas funcionalidades e comandos que atendem às suas necessidades específicas de jogabilidade.</li>
  <li>Após conectar o controle ao seu PC via bluetooth, Ana testa o controle em seu jogo de tiro favorito. Ela percebe imediatamente uma melhora significativa em sua jogabilidade, conseguindo movimentar seu personagem com mais precisão e rapidez.</li>
  <li>Ana continua a jogar com o controle remoto e experimenta outros jogos de tiro e outros gêneros de jogos. Ela está muito satisfeita com o controle personalizado que criou e acredita que lhe dará uma vantagem sobre seus oponentes em competições online.</li>
</ol>

<h3>Comandos/ Feedbacks</h3>
<p>Os comandos/operações possíveis do controle serão:</p>
<ul>
  <li>Movimentação nos eixos X e Y através de dois joysticks analógicos</li>
  <li>Pressionamento de 4 botões digitais para a realização de ações diversas, como atirar, pular, etc.</li>
</ul>
<p>Os feedbacks que o controle irá fornecer ao usuário são:</p>
<ul>
  <li>Vibração nos motores presentes nos joysticks, dando uma sensação de imersão ao usuário</li>
  <li>Feedback visual através de LEDs RGB que mudam de cor de acordo com o status do jogo, como saúde do personagem, nível de munição, etc.</li>
</ul>

<h3>IN / OUT</h3>
<ul>
  <li>Movimentação nos eixos X e Y através de dois joysticks analógicos</li>
  <li>Pressionamento de 4 botões digitais para a realização de ações diversas, como atirar, pular, etc.
    <ul>
      <li>4 botões digitais</li>
    </ul>
  </li>
  <li>Vibração nos motores presentes nos joysticks, dando uma sensação de imersão ao usuário
    <ul>
      <li>2 motores de vibração</li>
    </ul>
  </li>
  <li>Feedback visual através de LEDs RGB que mudam de cor de acordo com o status do jogo, como saúde do personagem, nível de munição, etc.
    <ul>
      <li>4 LEDs RGB</li>
    </ul>
  </li>
</ul>

<h3>Design</h3>
  <p>O design do controle será pensado para proporcionar uma experiência imersiva ao usuário durante a jogabilidade. Ele terá formato ergonômico, para que o jogador possa segurá-lo confortavelmente durante longos períodos de tempo, sem sentir desconforto ou fadiga muscular.</p>
  <p>A paleta de cores será definida de acordo com a temática do jogo e dos LEDs RGB que fornecerão feedback visual ao jogador. Os botões terão tamanho adequado e estarão dispostos de forma estratégica, facilitando o acesso e minimizando a possibilidade de pressionamento acidental.</p>
  <p>Os joysticks analógicos serão de alta precisão e sensibilidade, permitindo movimentos precisos e fluídos. Os motores de vibração serão ajustados para fornecer uma experiência imersiva e realista, vibrando de acordo com as ações do jogo.</p>
  <p>No geral, o design será moderno, atrativo e funcional, visando proporcionar uma experiência de jogo única e agradável ao usuário.</p>










