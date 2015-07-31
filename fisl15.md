# FISL 15 (07 a 10/05/2014)

* Anotar palestras interessantes que não olhei e baixar videos http://papers.softwarelivre.org/papers_ng/public/new_grid

## Facilitando a vida com Raspberry Pi e Arduino
- 07/05/14 10h
- [Thiago Garcia da Silva](https://github.com/thiagogds)
  - Olhar script para ver séries (Acho que é o Zonaderede)
- Bruno Erthal de Abreu
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41a/sala41a-high-201405071001.ogv)

[Moleque de ideias](http://www.molequedeideias.net/) - Hackerspace desse pessoal

Sites de ideias
- Coursera
- Instructables
- Udacity

Olhar genéricos Arduino na China
- Starter kit
- Find deals for . me

Raspberry Pi
- Flexget - Gerencia download de seriados

## Liberte seu Android! How to regain control over your mobile device
- 07/05/14 10h
- Torsten Grote 
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/40t/sala40t-high-201405071059.ogv)


- CyanogenMod - Funciona melhor
- Replicant - 100% software livre
- F-Droid - Alternativa ao google play
- Wiki da FSFE - Instruções para celular livre
- http://freeyourandroid.org
- Fazer Android Install Fest
- DavDroid - Sincronização de devices Software Livre

## Explorando as APIs do HTML5
- 07/05/14 13h
- Raphael Amorim
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41d/sala41d-high-201405071300.ogv)

Objetos HTML5
- WebSpeech - Reconhecimento de voz (só chrome, por enquanto)
- Firefox e FirefoxOS - Vibration, Bateria, Orientação
- FullScreenAPI - Elemento requestFullScreen
- Geolocation

## 10 tips on developing and deploying large scale systems
- 07/05/14 14h
- Fernanda G Weiden
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/40t/sala40t-high-201405071400.ogv)


- Identificar projetos para usar na Infra
  - Não reinventar a roda
- Keep it simple
  - Se é muito complicado, provavelmente está errado
  - Não otimizar antes da hora
- Modular é melhor que monolítico
- Hardware **vai** falhar, mas o software tem que sobreviver
- Cuidado com as dependências
  - Combinar libs e softwares similares para simplificar a arquitetura
  - [Graceful degradation](http://en.wikipedia.org/wiki/Fault_tolerance)
  - Cuidado com excesso de features
  - Estabilidade > features
- Fazer testes (integração, carga)
- Release often, release now
  - Organizar bibliotecas
  - Remover maçã podre (código que não foi legal nos testes)
  - Não juntar muita feature na mesma release
- Deployment - implantar com segurança (em partes)
- Monitoramento
- Não vai ser sempre você
  - Transferir o conhecimento
  - Deixar sinais mais óbvios
    - Ex. (problemas no emulador siscomex java)
- Automatizar tanto quanto possível
  - Rollback, diagnóstico, logs

## O Bootstrap 3 é Mobile First
- 07/05/14 15h
- [Alexandre Magno Teles Zimerer](https://github.com/alexanmtz)
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41d/sala41d-high-201405071501.ogv)


- Olhar https://github.com/globocom
  - redimensionamento de imagens para diversas plataformas
  - [Acho que é esse](https://github.com/globocom/impim-api)
- Desenvolver primeiro no celular, depois no desktop
  - Simulador de resolução no chrome (inspector)
- Documentação é muito boa
- **Usar Icon Fonts**
- Semântico
  - Nomear componentes no HTML, definir tamanho e visualização só no CSS
- Response images (olhar)
- Tentar não depender muito do JS (Single point of failure)
- Usar jQuery mobile (eventos swipe)
  - Window, document touch
- [Modernizr](http://modernizr.com) - Lib JS que detecta funcionalidades no browser do usuário
- [Bower](http://bower.io/) - Package manager, estilo composer
- [Grunt](http://gruntjs.com/) - Task runner, agendador de tarefas
- [Sencha.io](http://www.sencha.com/learn/how-to-use-src-sencha-io/) redimensiona / diminui imagens

## Desenvolvimento de aplicativos para Firefox OS
- 07/05/14 17h
- Andre Alves Garzia
- Qaiq Alves
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41f/sala41f-high-201405071705.ogv)


- Já tem à venda - LG, Alcatel, GeeksPhone, ZTE, Huawei
- Simulador Firefox OS vem junto no Firefox, roda muito rápido
- Criar App Manifest
  - Hospedado (praticamente um site)
  - Empacotado (empacota arquivos do app)
- [Documentação oficial](https://wiki.mozilla.org/WebAPI)
- [Firefox Market Place](https://marketplace.firefox.com/)
- [Exemplo](http://ponte.amoralabs.com) - App sobre a ponte Rio Niterói

## Programando Jogos Multiplataforma - Para Leigos
- 08/05/14 12h
- [Lucas R. Martins](https://github.com/lukasrms)
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41e/sala41e-high-201405081202.ogv)


- Ideia para jogos - Fazer rápido baseado em notícias
  - Rolezinho no shopping
  - Bueiros explodindo
  - Copa, gols da Alemanha no Brasil
- Kivy - Não é para jogos, mas funciona legal
- Liclipse ou Eclipse + PyDev
  - IDE para não parar / perder fluxo na hora de testar
- Canvas - manipulação de pixel (HTML5)
- Física, método de Verlet (procurar engine)
- PySerial (Kinect)
- OpenCV (Câmeras)
- Flask (Cliente / Servidor)
- Android SDK, NDK
- Buildozer, Python for Android

## Assim na Terra como no Shell
- 08/05/14 14h
- Julio Neves
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41a/sala41a-high-201405081400.ogv)


- `sort` - ordena
- `uniq`
- `seq`
- `paste`
- `bc` - calculadora binária
- Trocar `;` por `+` - descobrir o que é
- `if` - testa se comando rodou
- `xargs` - junta stdin separados por linhas
- Olhar livro do Julio Neves
  - Papo de botequim

## PHP na Tela Escura: Aplicações Poderosas em Linha de Comando
- 09/05/14 09h
- Rafael Jaques
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41b/sala41b-high-201405090904.ogv)


- http://php-rs.org
- [Exemplos](http://www.phpit.com.br/palestras/telaescura/exemplos.tar.gz)
- [Processos longos](http://www.phpit.com.br/artigos/trabalhando-processos-longa-duracao-php.phpit)
- [Slides](http://www.slideshare.net/rafajaques/php-na-tela-escura-aplicaes-poderosas-em-linha-de-comando)

## Performance analysis at Facebook scale
- 09/05/14 10h
- Marlon Dutra
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/40t/sala40t-high-201405091001.ogv)


- `sysstat` -> Muito legal
- Fazer profiling por pouco tempo
  - Deixa lento e confunde a própria métrica
  - Linguagem de script normalmente tem profiler (PHP)
- Tentar usar gráficos para visualizar
  - Gnuplot
  - RRDTool
- Tentar guardar logs para sempre, granularidade mínima possível
- SNMP para coletar dados
- Fazer P50 ou Percentil em vez de média
- Usar todo tipo de ferramentas
  - scripts próprios
- Entender a aplicação, entender cliente

## Designing for Mobile and Surviving
- 09/05/14 11h
- Ophelia Van Campenhout
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/40t/sala40t-high-201405091103.ogv)


- Conteúdo vem primeiro
  - Legibilidade
    - Escolher o que é essencial
  - Não esconder nada
- Não usar as mesmas imagens
  - responsive images
  - [http://adaptive-images.com/ Adaptive images]
- Evitar muitas requests HTTP
  - CSS Sprites Generator
  - [FitVids JS](http://fitvidsjs.com/)
  - [FitText](http://fittextjs.com/)
  - Usar SVG - Já tem suporte em todos
- Tools
  - Foundation
  - Skeleton
  - Frameless
  - Bootstrap
  - Jetstrap
  - Easel
  - Typecast
  - Froont

## Análise de performance de jogos Android com Cocos2d-HTML5
- 09/05/14 14h
- George Silva
- Vinicius Sandrini Vecchi
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41e/sala41e-high-201405091400.ogv)


- [Naked monkey Games - last survivor](http://www.nakedmonkey.mobi/games/lastsurvivor/)
- [WebStorm](http://www.jetbrains.com/webstorm/)

## PhoneGap: porque você não precisa fazer o seu app mobile nativo
- 10/05/14 14h
- Diego Moreira Guimarães


- Podcast Mobilidade FM
- [Slides](http://www.slideshare.net/diegodukao/phonegap-campus-party-2013)
- [Kivy - Olhar também](http://www.slideshare.net/diegodukao/kivy-2013)


- Phonegap funciona como WebView com API para acessar recursos do celular
  - http://phonegap.com/app
  - Engine = Cordova
  - App Untappd


- [Genymotion - Emulador Android](http://www.genymotion.com/)
- [Weinre - debugger](http://people.apache.org/~pmuellr/weinre-docs/latest/Home.html)
- Kivy - Bom para jogos
- Sencha touch - Framework mobile

## NGiNX, o motor da sua aplicação web
- 10/05/14 15h
- Ernani Azevedo


- PHP-FPM, WSGI (Python, etc)
- Balanceia carga como IPVS
  - Dá para usar memcache p/ guardar sessões
- Zabbix - monitora requisições
- http://www.intellinews.com.br/

## MAME/MESS: Engenharia Reversa e Emulação de Dispositivos Digitais
- 10/05/14 16h
- Felipe Corrêa da Silva Sanches
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41d/sala41d-high-201405101601.ogv)


- Olhar jogo Gyruss
- Código do Mame tem drivers das placas da época

## Real-time APIs com Web Sockets em PHP
- 10/05/14 17h
- Ricardo Coelho
- [Gravação](http://hemingway.softwarelivre.org/fisl15/high/41d/sala41d-high-201405101700.ogv)


- [Slides](https://speakerdeck.com/ramcoelho/)
- Tipo TCP para Browser (Texto e binário)
- Framework Ratchet
  - PHP non-blocking (estilo node)

- Olhar AbraPHP (Associação Profissionais PHP)

## Observações

- **Write code every single day**
  - [Challenge](http://ejohn.org/blog/write-code-every-day/)
  - [Raphamorim](http://raphamorim.com/code-every-day/)


- **Blender cycles - Engine de jogos para Blender**

- **Node.js**
  - NPM
  - Gulp
  - Grunt


- Integração contínua
  - [Olhar SnapCI](https://snap-ci.com/)
