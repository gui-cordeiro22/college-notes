**Redes de computadores**

Atualmente, independente do dispositivo, dificilmente vemos algum deles que funcione somente com os dados contidos neles, provavelmente ele irá acessar algum dado que está hospedado em alguma rede de servidores usando a internet como caminho para isso.

Olhando por essa perspectiva, já conseguimos começar a entender a importância das redes, ela é quem permite que o dispositivo e o servidor troquem essas informações.

Quais são os parâmetros pelos quais podemos avaliar uma rede? Como podemos dizer que uma rede é boa ou ruim? Até o momento estamos falando isso da perspectiva do usuário, agora como desenvolvedor de aplicações precisamos ter um conhecimento ainda mais profundo acerca disso para sabermos os requisitos que nossa aplicação precisa cumprir para rodar em determinada rede e coisas similares à essas, até mesmo para informarmos aos clientes.

Um ponto super importante é conhecer a arquitetura de camadas, para nos ajudar a entender como as redes funcionam, assim como também precisamos entender como a internet evoluiu ao longo dos anos e entender todos os seus aspectos.

**O que são redes de computadores?**

Precisamos antes de qualquer coisa diferenciar o que são redes de computadores e o que é a internet em si.

Redes servem basicamente para compartilharmos recursos e também para compartilharmos informações. Na imagem abaixo, temos o exemplo de uma rede:

A primeira coisa importante de se notar nessa imagem é: temos um nó transmissor e um nó receptor, eles estão interligados por um sistema de comunicação – o objetivo desejado por nós com essa rede é que o ponto saia do transmissor e chegue até o receptor.

Basicamente uma rede de computadores são os nós interligados através de um meio de comunicação.

O exemplo anterior, é extremamente básico, logo é muito difícil que uma rede de computadores esteja disposta dessa forma, o que é mais comum é existirem redes de interconexão, como segue a imagem:

Nessa imagem de exemplo, nós vemos o mesmo nó transmissor e o mesmo nó receptor, porém, não existe um meio de comunicação ligando-os diretamente como visto na imagem anterior.

Temos então uma rede de interconexão, quando falamos dela, estamos falando de vários meios de transmissão com elementos intermediários que vão permitir que o dado saia do transmissor e chegue até receptor, mas, obviamente essa rede de interconexão irá permitir que existam outros dispositivos interconectados para haver a comunicação entre os outros elementos.

Quando falamos a respeito da rede de interconexão, chegamos próximos da definição que podemos dar à internet.

**O que é a internet?**

A internet é um conjunto de redes e dispositivos, podemos classificar a internet de diversas formas, mas basicamente dizemos que: “a internet é uma rede formada de outras redes” – são várias redes que são interconectadas permitindo que você possa trocar informações.

Abaixo, temos uma imagem que pode ilustrar bem a ideia de redes interligadas:

Podemos ver vários exemplos como rede móvel, rede doméstica etc, que estão conectadas a vários provedores, que na imagem estão com a sigla ISP (Internet Service Provider), na imagem temos servidores regionais e até mesmo globais que farão com que essas redes sejam interconectadas, o próprio provedor também é uma rede.

Com essa estrutura garantimos o funcionamento desse tipo de serviço, que ao pegar o seu celular você consiga buscar dados de um servidor, que você consiga enviar mensagens para outras pessoas e etc.

Agora vamos olhar a internet fragmentando-a em três grandes partes: 

1. Borda da rede – ela que também é conhecida como sistemas finais, são efetivamente onde nós iremos executar algum tipo de aplicação, algum tipo de serviço, é o que normalmente os usuários de fato irão utilizar (ex.: celular, notebook/desktop, smart TV…), todos esses dispositivos são conhecidos como borda da rede, onde eu vou executar algo de fato para que eu possa utilizar – onde principalmente as pessoas que irão trabalhar com desenvolvimento irão trabalhar, mas por quê? Porque estaremos desenvolvendo aplicações que irão rodar nessa categoria de dispositivos.

2. Núcleo da rede – Os elementos intermediários são as redes de interconexão que irão permitir que você possa fazer com que os dados fluam entre as outras diversas redes e os outros dispositivos finais.

3. Redes de acesso – Rede responsável por permitir que os dispositivos finais possam se interconectar com o núcleo da rede, elas são responsáveis por permitir que os dispositivos de borda possam conectar-se aos provedores e fazer as trocas de dados e informações.

**Internet | Uma infraestrutura de serviço**

Quando falamos sobre essa infraestrutura, podemos usar duas abordagens, sendo elas:

1. Pensarmos que a internet é uma rede de redes que nos oferece algum tipo de serviço, logo nós que somos usuários conseguimos usar um aplicativo de troca de mensagem, consigo usar serviços de streaming como por exemplo a netflix, o spotify, consigo acessar páginas web para fazer buscas, cadastros, compras etc, ou seja, àquela rede está me oferecendo serviços.

2. O outro lado, é justamente para quem vai trabalhar como desenvolvedor, para que você tenha essa comunicação funcionando você preciosa que alguns serviços sejam executados, por exemplo, eu preciso encontrar a máquina de destino, preciso definir um caminho, um endereço, preciso corrigir erros que podem surgir provenientes dessa comunicação – porém, a rede nos dá todo o suporte para encontrarmos a máquina, para saber que a comunicação ocorreu como deveria e não ouve erro, ela nos oferece esse serviço.

Caso não existisse essa infraestrutura da rede, no desenvolvimento de uma aplicação que rodará nos elementos de borda, seria necessário fazer todo esse controle de erros, controle de fluxo, controle de congestionamento, roteamento, endereçamento, o que atualmente não precisamos nos preocupar, nos preocupamos basicamente com a nossa aplicação e com o desenvolvimento da aplicação, depois disso entregamos para a infraestrutura de serviços e ela vai se encarregar de fazer a entrega.

**Borda da rede**

Como já falamos anteriormente, são os dispositivos finais em que os usuários usarão para interagir com a rede, onde rodam os serviços que são consumidos pelos usuários.

Um exemplo disso que também já foi citado anteriormente, é o envio de mensagens, quando pegamos o nosso celular para enviar uma mensagem para alguém, ali temos uma aplicação que enviará ou receberá dados com outro elemento da borda da rede (celular, notebook…).

Nesse outro dispositivo de borda também terá uma aplicação rodando e será utilizado um protocolo que garantirá a comunicação entre esses dois dispositivos, nessa aplicação existirá uma arquitetura/modelo chamado de modelo cliente/servidor, é uma das arquiteturas mais comuns que existe, onde temos o cliente e o lado do servidor.

Mas o que é o lado do cliente? O lado do cliente será onde normalmente você irá fazer algum tipo de requisição, uma consulta;

E o lado do servidor? Ele estará servindo para o cliente alguma coisa.

Para facilitar o entendimento, vamos imaginar que precisamos pegar um arquivo, então eu como cliente peço esse arquivo ao servidor e ele é enviado para mim como retorno. (Analogia do garçom).

Para garantir essa comunicação obviamente utilizaremos de tópicos que já mencionamos anteriormente como: as redes de acesso, os núcleos da rede, tudo isso para garantir essa comunicação.

Os dispositivos de borda da rede também estão nessa posição porque neles estamos utilizando todos os outros elementos da rede.

> Clientes: São os desktops, notebooks, smartphones e tablets, dispositivos que, normalmente, estão de posse de algum usuário.

> Servidores: São as máquinas mais poderosas, que armazenam e distribuem páginas web, vídeo em tempo real, retransmissão de e-mails etc.

Ainda sobre os servidores, é comum chamarmos de máquinas grandes e poderosas, mas, o que torna faz de uma máquina um servidor não é o seu tamanho ou quão poderosos são seus hardwares, mas sim o software que é executado por ela, como o próprio nome já diz ele será um dispositivo que estará servindo alguma coisa, algum serviço ao cliente que faz um pedido por meio de uma requisição.

**Núcleo da rede**

O núcleo da rede é o coração, nele estão presentes o conjunto de roteadores, switches, enlaces e diversos equipamentos que vão permitir com que dois sistemas finais, ou seja, dois dispositivos de borda da rede estejam distantes, por exemplo casas diferentes, cidades diferentes, países diferentes, e mesmo assim nos possibilitar determinar caminhos e permitir que os dados fluam pela rede até chegar no destino, se necessário, lá fazer algum processamento e depois recebermos um retorno.

Normalmente, os núcleos de rede são organizados por meio de ISP’s (Internet Service Providers) ou provedores de acesso à internet, e como eles estão estruturados?

Os ISP’s são estruturados em diversos níveis, por exemplo, nós temos provedores: regionais, nacionais, de trânsito, eles criam toda essa estrutura de enlace (conexão física ou lógica entre dois dispositivos que permite a comunicação e a troca de dados) para permitir que você possa montar essa malha de dados e então estabelecer caminhos.

Temos como falamos anteriormente os provedores de trânsito, que normalmente são criados por meio dos cabos submarinos, o que são esses cabos? São um conjunto de cabos de fibra ótica que são lançados pelo oceano, assim, permitindo fazer a interligação de países, locais remotos com uma conexão de alta velocidade.

Sabemos que tem diversos níveis de provedores, na cidade onde moramos ou até mesmo no bairro existem diversos provedores, que se conectam a outros provedores e fazem toda a interconexão, no local onde chegam vários clientes, normalmente, chamamos de ponto de presença (PoP) - temos vários usuários, todos eles conectados a um determinado ponto.

Nesses pontos de presença, o provedor responsável por fornecer a internet, também precisa estar conectado a outro provedor, nessas relações existem alguns provedores que fazem acordos de tráfego, contratam outros provedores para para proverem para ele o acesso à internet e outra coisa que vem crescendo cada vez mais também são os pontos de troca de tráfego (IX).

Os IX são pontos onde os provedores ao chegarem nesse local, fazem acordos de trocas de tráfego, aqui no Brasil temos o [IX.br](http://ix.br) - onde podemos ver os diferentes pontos de troca de tráfego espalhados por todo o nosso país, todos eles têm esse sistema de troca de tráfego, e daí os provedores organizados por meio de uma coisa chamado sistema autônomo se conectam aos equipamentos do IX e a partir dali ele estará interconectado a vários outros provedores.

**Rede como serviço**

Sabemos que a rede como um todo oferece serviços, sejam eles para os usuários, aqueles que consumiram um serviço final, como por exemplo: uma pesquisa, um vídeo, o envio de uma mensagem no Whatsapp…

Mas, além disso, precisamos pensar também como a rede pode ajudar nos ajudar como desenvolvedores, a infraestrutura de rede que nós temos hoje vai nos permitir nos preocuparmos em desenvolver a aplicação, o negócio, a lógica para que consigamos fazer as nossas aplicações da borda da rede trocarem dados, criamos o cliente, criamos também o servidor, desenvolvemos algum tipo de protocolo se for necessário e dessa forma permitimos a comunicação. Não precisamos nos preocupar com nada relacionado ao fluxo de dados, por quê? Porque a rede nos oferece toda essa infraestrutura.

Quando se fala dessa infraestrutura, normalmente falamos sobre API’s, ela é um ponto de acesso que nos permite acessar um determinado serviço.

A API que está sendo falada neste momento, não é a mesma que costumamos utilizar em desenvolvimento de aplicações web, ela é uma API de mais baixo nível, que nos permite acessar a infraestrutura de redes.  
  
Nessa linha de API’s, temos uma muito importante e famosa chamada Socket, ele nos permite acessar essa infraestrutura de serviços, então quando formos desenvolver o nosso cliente será necessário desenvolver uma lógica para que ele seja capaz de acessar essa interface socket e do lado do servidor, será necessário fazer a mesma coisa - em tese, no servidor deverá ser um programa que esteja sempre rodando para que o cliente possa acessar e consumir os dados necessários.

O Socket do cliente entrará em contato com o Socket do servidor, buscará os dados necessários e retornará pelo mesmo Socket por onde ele foi.

Esse processo acontece por trás das cortinas no próprio navegador, ele é o responsável por fazer toda essa comunicação.

Em alguns momentos já ouvimos falar sobre portas, por exemplo: localhost:3000 - nesse caso a porta é a 3000, essa porta é justamente o Socket que estamos trabalhando.

(Continuar em parâmetros de avaliação)