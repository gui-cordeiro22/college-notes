**Base computacional**

Quando começamos a estudar alguma linguagem de programação, ouvimos que programar é abstrair completamente o hardware, o que em alguns casos faz sentido, se fizermos um código em Java o seu executável poderá ser levado para outros dispositivos e executado, um código desenvolvido em Python também tem a possibilidade de ser interpretado em outros dispositivos, mas, a grande pergunta é será que dá realmente para sempre abstrairmos às questões do hardware? E a reposta é **não**! Existem vários momentos em que precisamos ter conhecimento do hardware, ou seja, da máquina que está por trás daquela aplicação para extrair o máximo dela, exemplo disso são as pesquisas de computação de alto desempenho.

Para isso precisamos voltar um pouco no tempo, o mundo estava em Guerra, a Alemanha possuía uma máquina de criptografia chamada "enigma" - obviamente para os aliados seria muito bom poder decodificar esses textos alemães, foi assim que então Alan Turing, um dos precursores na área da computação, desenvolveu uma máquina capaz de resolver esse problema decodificando as mensagens (recomendação de filme: O jogo da imitação), essas foram as primeiras gerações de computadores mecânicos, depois eletrônicos a válvulas, depois eletrônicos a transistores, circuito integrado, depois com o projeto apolo surgiu a necessidade de reduzir o tamanho e o peso do computador para que ele pudesse caber em uma capsula espacial, até o ponto que chegamos na atualidade.

**Por que estudar o assunto? Qual a importância?**

Estudar esse assunto vai me tornar um profissional melhor? A resposta é sim, veja alguns benefícios:

- Conhecendo sobre esse tema você conseguirá programar melhor;
- Especificar melhor equipamentos;
- Comprar melhores equipamentos, que supram de fato às necessidades;
- Tomar decisões melhores e mais assertivas.

**Desenvolvimento do computador em quatro gerações**

1ª Geração: Válvulas termiônicas => Ainda no período da segunda guerra mundial, após o feito de Alan Turing, o Estados Unidos desenvolveu o primeiro computador eletrônico da história, batizado como ENIAC, mas, ele era muito espaçoso, ocupava uma sala de 150 m², na imagem a seguir podemos ver algumas características desse computador:

![[Pasted image 20250820170440.png]]

Para evoluirmos foi preciso abrir mão das válvulas, afinal, elas eram muito grandes e pesadas, com isso damos início a próxima geração.

2ª Geração: Transistores => Foram os transistores que possibilitaram o abandono das antigas válvulas, após sua criação, dando início a era da microeletrônica.

Os primeiros transistores ocupavam apenas alguns milímetros, assim precisando de bem menos energia que as válvulas, dessa forma foi possível reduzir o tamanho de rádios, equipamentos eletrônicos em geral e também dos computadores.

3ª Geração: Circuitos integrados => Na década de 1960, o próximo salto de evolução foi dado com a criação dos circuitos integrados (CI): pastilhas de silício que contêm um circuito eletrônico miniatura. É o que, de forma comum, chamamos de chip de computador.

Com o uso dos circuitos integrados, os computadores ficaram menores e cada vez mais baratos, por volta de 1970 houve o surgimento dos computadores pessoais (denominados PCs, sigla em inglês para Personal Computers).

Nessa mesma época houve o surgimento de duas grandes empresas do ramo, sendo elas a Microsoft Corporation, fundada em 1975 e a Apple Inc. que em 1976 vendeu 200 unidades do seu primeiro PC, o Apple I.

4ª  Geração: Microprocessadores => A década de 1980 presenciou o aumento de computadores cada vez mais potentes, baratos e conectados por meio do surgimento das redes locais de computadores e da internet: rede mundial.

Além disso, um novo personagem aparecia nos lares: o *videogame*, que é um tipo de computador especializado para programas que são jogos eletrônicos com ênfase em gráficos e na interação com os usuários.

Com o final do século XX, os computadores já eram tão pequenos e potentes que se encontravam embarcados em diversos equipamentos cotidianos, como automóveis, aviões e videogames, além da popularização do laptop (computadores portáteis), não demorou muito também para que essas integrações fossem feitas à televisões e celulares, em 2010 essa integração começou a ser feita por intermédio de smartphones e smart tv's.

**Computação no cotidiano**

Atualmente a maioria dos celulares já são de fato computadores portáteis, conectados o tempo todo por meio da rede.

Nossa dependência desses aparelhos é tão grande que nem percebemos quando como usamos, pelo contrário, sentimos falta caso ele não faça parte do nosso dia. Mas por que disso? Basicamente nós usamos o celular para nos comunicar (Whatsapp), para fazer transações bancárias (Pix), podemos usar para ter acesso a meios de transporte e mais diversas outras finalidades. 

Atualmente, até o dinheiro não é guardado mais em cofres, os saldos bancários são armazenados digitalmente nos servidores dos bancos. 

Se todos os correntistas de um banco solicitassem retirar inteiramente o dinheiro guardado nele, não haveria cédulas suficientes no cofre para atendê-los.

**Sistema computacional**

Os computadores são feitos com um conjunto de componentes dividido em dois grandes grupos: Hardwares e Softwares.

- Hardware => Componentes físicos, ou seja, que podem ser vistos e tocados (ex.: placa mãe, placa de vídeo, memória ram, processador...)
- Software => Programas executados no computador (ex.: Word, Excel, VSCode, jogos...)

Na imagem abaixo, poderemos ver uma alusão de peças de hardware, sendo exemplificadas em um carro:

![[Pasted image 20250820175014.png]]

As peças do carro são equivalentes ao hardware do computador, por mais que o carro já tenha todas as suas funções descritas, não sabemos como o usuário o utilizará, sendo assim, a sua função final será dependerá do motorista ou então do usuário olhando para o ponto de vista da computação.

**Principais componentes de hardware dos computadores**

Como falamos de um computador temos itens que são periféricos e os que fazem de fato parte do "coração do computador", que fazem com que tudo tenha vida.

- **Periféricos** => No grupo do periféricos, nós temos: Monitores, teclado, mouse...

Agora no segundo grupo, temos as peças que ficam dentro do gabinete do computador, que de fato dão vida a ele, sendo as seguintes:

- **Processador** => O processador é conhecido como cérebro do computador, ele é o responsável por executador todos os comandos lógicos e matemáticos, ele depende de um impulso chamado "clock" - esse impulso é o responsável por ditar a velocidade que as operações ou instruções são carregadas e executadas dentro do processador, ainda falando sobre esse impulso, temos uma técnica conhecida como "overclock" - o que aumenta a velocidade desse impulso para uma superior, o que pode sim aumentar a velocidade de processamento, já que aumenta a velocidade com que as informações são processadas, mas precisa ser feito de forma cautelosa, porque pode acabar prejudicando a vida útil do processador por estar usando um impulso acima do esperado por ele. Além disso, com o passar do tempo foi considerado a capacidade do computador, no desenvolvimento inicial dos processadores, eles aumentavam o clock uma vez após a outra, mas, depois de um tempo as limitações físicas não permitiram mais o aumento do clock, a partir desse momento as indústrias desenvolveram um outro processo, uma forma de colocar vários núcleos de processamento dentro de um único circuito integrado (CI), o que chamamos de multi-core, podemos ter por exemplo o dual core com dois núcleos de processamento ou então o quad core com quatro núcleos de processamento. Por fim, o último componente importante do processador é a memória cache, ela funciona como um pequeno espaço de memória dentro do próprio circuito integrado do computador, ele normalmente é muito mais rápida que o acesso de escrita e leitura à memória principal, o que torna o computador mais performático, sendo assim o tamanho da memória cache é mais um fator importante na hora de escolher um processador.

- **Memória principal** => A memória principal do computador, também conhecida como memória RAM, é muito importante porque nela são carregados os programas que serão executados no processador, além disso, ela também serve para guardar os dados que são usados durante o processamento. Essa memória funciona como se fossem pequenas caixas, ou como de fato são conhecidas: células, que contem 1 byte de informação cada uma, elas funcionam como uma caixa de correio, porém, só podemos inserir uma carta por vez, para colocar uma nova é necessário descartar a anterior (mesmo conceito de variáveis usado em linguagens de programação), essas células podem ser acessadas por meio do seu endereço, qualquer pessoa que tiver o seu endereço pode acessá-la, não precisa ser sequencialmente, sendo assim chamamos ela de: Memória de Acesso Aleatório ou em inglês Random Access Memory, daí a nomenclatura memória RAM. Importante dizer que a memória RAM é volátil, ou seja, quando tiramos a energia do computador as informações contidas nela são perdidas, então para isso usamos uma memória secundária que mantém as informações entre as suas execuções. As duas principais características quando se vai procurar por uma memória é: a sua capacidade de armazenamento, resumidamente o que cabe dentro dela, e a sua taxa de transferência de arquivos, a velocidade que ela consegue transmitir informações para o resto do computador.

- **Placa mãe** => É um circuito eletrônico impresso, nela são encaixados os demais componentes, como exemplo o processador, a memória RAM e diversos periféricos, daí vem o nome mãe, porque ela recebe todos esses componentes em si. A função principal da placa mãe é conectar os componentes entre si, à essa conexão damos o nome de barramento (hoje a principal tecnologia usada é o SATA2, sendo capaz de permitir taxas de transmissão de 3Gb p/ segundo), além dessa conexão a placa mãe é responsável por levar energia a tudo que é conectado nela. Com a evolução e miniaturização de elementos, alguns componentes que antes eram conectados à placa mãe, hoje passaram a ser integrados diretamente nela como um chip, a esse processo damos o nome de onboarding. Com essa tecnologia, podemos criar placas-mãe cada vez mais complexas, tendo diversos elementos integrados, exemplo disso são os notebooks em grande parte e também os celulares.

**Software**

Com as possibilidades criadas pela presença dos hardware nos computadores, se tornou necessário a execução de um conjunto de programas, assim, trazendo as suas funcionalidades a tona, o que define um software. Os softwares podem ser divididos em dois tipos: Finalísticos/de aplicação ou softwares de sistemas.

- **Softwares finalísticos ou de aplicação** => Normalmente são rodados de forma consciente nos computadores, entregando uma funcionalidade específica ao usuário, por exemplo: Navegadores da internet, programas de Office e similares, jogos...

- **Software de sistema** => Permitem que as aplicações rodem em muitas máquinas com diferentes hardwares, esses software incluem drivers dos dispositivos instalados no computador, os drivers são programas que controlam como se acessa e comanda um determinado periférico, o principal software de sistema é conhecido como **sistema operacional**, exemplos de sistemas operacionais: Windows, MacOS, distribuições Linux (Debbian, ZorinOS, Ubuntu, LinuxMint...).

**Sistema operacional**

Como já vimos anteriormente, o sistema operacional é o principal software de sistema, ele conhece o hardware (seus componentes e periféricos) do computador, para que os seus programas possam executar sem a necessidade de conhecer cada um deles.

Outra função do sistema operacional é guardar e distribuir corretamente o espaço da memória principal (RAM) para os programas e seus dados.

A terceira função do sistema operacional é dar acesso ao processador aos diversos processos ou programas que querem acessá-lo, hoje em dia, os computadores rodam vários programas simultaneamente, todos eles querem acesso ao processador, porque essa é a única forma de executar as suas instruções.

Por último, temos o escalonador, que é responsável por temporizar e determinar que um processo deve abandonar o processador, assim, dando espaço para novos processos que estão na fila, ele mantém essa fila e determina quando um deverá ser encerrado e outro iniciado, existem também vários tipos de prioridades que podem ser utilizadas nessa fila.


**Histórico**

Os primeiros sistemas operacionais começaram a ser desenvolvidos junto com os computadores na década de 1960, inicialmente eles eram só uma interface visual que comunicava o hardware com os programas que tinham ali.

Já na década 1970 surgiu um dos principais sistemas operacionais conhecidos, o Unix, esse que é a base dos sistemas operacionais Linux que usamos hoje em dia, ele foi desenvolvido na academia americana e foi distribuído por todos os centros acadêmicos dos EUA, assim tornando-os bem populares.

Na década de 1980, a Microsoft desenvolveu o seu sistema operacional MSDOS, ficou conhecido no Brasil como DOS, esse sistema se tornou muito popular porque vinha incluso nos computadores da época.

Além disso, a Microsoft ainda na década de 1980 desenvolveu o sistema operacional Windows, que futuramente seria ainda mais popular que o DOS, esse sistema operacional trazia uma novidade, que eram as janelas que se projetavam por cima da área de trabalho, podiam ser movidas, redimensionadas por meio de cliques do mouse.

O Windows chegou a ocupar 90% do mercado de sistemas operacionais, nessa mesma época a concorrente da Microsoft, a Apple, surgia com o seu sistema operacional que trazia o sistema de ícones que representavam programas e também possuía uma interface gráfica com janelas.

No século XX, o desenvolvimento de sistemas operacionais progrediu para sistemas operacionais embarcados, exemplos disso são os que nós usamos em nossos celulares e tablets.

Essa disputa contava basicamente com três competidores:

- Apple => Com seu sistema próprio (IOS) somente para dispositivos da marca;
- Google => Com o sistema Android, usado em diversos celulares de diversas marcas diferentes;
- Microsoft => Tentativa de desenvolver um Windows para versão mobile, o Windows Phone, mas, acabou abandonando esse mercado cedendo espaço para as outras duas.

**A origem da internet**

Ela surgiu na década de 70, os computadores já eram uma realidade visando que começaram a serem desenvolvidos na década de 60, então o departamento de defesa americano decidiu conectar diversos computadores de centros acadêmicos nos EUA, essa primeira rede de computadores foi chamada de ARPANET.

Durante a década de 70, além da ARPANET, diversas outras redes foram surgindo, quando todas essas redes se conectaram entre si, surgiu o que conhecemos hoje como internet, a rede das redes, recebendo esse nome em 1986.

Mas o que fez/faz a internet ter tamanho sucesso? A resposta: são suas funcionalidades, dentre elas a principal é a disponibilidade de páginas em servidores online, conhecida como World Wide Web (WWW), esse conjunto de páginas formam o que as pessoas conhecem como internet.

Mas a internet também traz outras funcionalidades, como mecanismos de buscas sendo o principal deles o Google, além disso, a troca de e-mail substituiu todo um sistema de correios que era utilizado com papel.

Outra funcionalidade importante que surgiu conforme as pessoas começaram a passar mais tempo conectadas à internet foi a troca de mensagens instantâneas ou chats.

O principal objetivo da ARPANET era permitir o trabalho de pesquisa em conjunto por pessoas nas duas costas dos Estados Unidos.

Mas é necessário comentar também que conectar computadores não era fácil, foi necessário:

- **Comunicação entre computadores** => Lançar meios de comunicação (como fios de cobre ou enlaces de rádio) entre os dois computadores;
- **Protocolos de comunicação** => Criar protocolos para que ambos pudessem entender como falar entre si, pois eles precisam de um hardware para enviar e receber dados em rede.

**Internet discada**

Por uma questão de simplicidade, as empresas de telefonia assumiram o papel de prover conexão à internet para os usuários. Surgia, assim, o _modem_ **de internet discada**, que se conectava como se estivéssemos fazendo um telefonema.

**Endereço IP e Roteador**

Um dos empecilhos para conectar tantas máquinas foi a forma de endereçamento, como identificar de maneira única o computador com o qual se deseja falar? A solução para isso foi dar um endereço, trata-se de um processo denominado endereço IP, abreviação para Internet Protocol. Mas o que era esse endereço IP? Ele consistia em uma sequência de 4 números entre 0 a 255 (representados em 8 bits). 

Em posse do endereço de destino, um pacote é enviado através das diversas redes existentes entre o remetente e o destino. Nas fronteiras delas, existem os **roteadores**, que funcionam como agências de correio e escolhem a rota que o pacote seguirá para chegar a seu objetivo final. Dessa forma, passando de roteador em roteador, o pacote de dados consegue alcançá-lo com a sua mensagem.

**Banda larga**

Na época da internet discada, as conexões chegavam à taxas de transmissão de apenas alguns Kb por segundos, com o avanço da tecnologia, principalmente com o surgimento das fibras óticas, o acesso à internet passou a se dar de forma muito mais rápida, com conexões nas taxas de Megabits por segundo, o que passou a ser chamada de banda larga.

Com esse acesso em suas casas, novas aplicações puderam ser desenvolvidas, dentre elas podemos citar uma das maiores hoje em dia que é o streaming de vídeos, que vem gradativamente substituindo a televisão, para os celulares, um desenvolvimento similar aconteceu com a tecnologia de transmissão, com o 3g e 4g, passamos a ter acesso à banda larga em nossos celulares.

