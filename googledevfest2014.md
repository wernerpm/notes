# GDG DevFest Sul 2014 (23/08/2014)

## The Webcomponents Ecosystem
- [Rob Dodson](http://github.com/robdodson)


- Web com look & feel de Apps
  - Material design para Web
- Ex. paper-tabs (tab-control)
- [Polymer](http://polymer-project.org/) = Lib para todos os browsers
- Também dá para estender elementos DOM comuns
- Olhar templates
- Shadow DOM = Componente CSS e HTML com escopo fechado (protected)
- Template Polymer = shadow DOM encapsulado
- HTML Imports - Importa uma coisa só em vez dé vários (diminui requests)
- Usar `bower` como gerenciador de pacotes
- Algo semelhante: [Mozilla Brick](http://brick.mozilla.io/)
- Referências
  - [webcomponents.org](http://webcomponents.org/)
  - [customelements.io](http://customelements.io/)


## Se eu posso, você também pode - Animações para Desenvolvedores
- [Lucio Maciel](http://twitter.com/luciofm)
- [Slides](http://github.com/luciofm/ifican)
  - Usar GenyMotion como tablet


- Não fazer transições bruscas, de preferência **nunca**
- **Sempre** animar transições
- Aproveitar tempo da animação para processar (json, internet, etc)
- Chamar a atenção
- Dar feedback
- `android:animateLayoutChanges`
- animation-list = Animator Drawable
- ObjectAnimator
- ViewPropertyAnimator
- Em vez de animar cor (transição) Botar cor final e animar o alpha
- Olhar morphing button (muito legal)
- TransitionManager
  - TransitionsBackPort
- Android L => WindowTransition
- Dá para animar SVG (Canvas)


## Desenvolvimento Fácil com AngularJS
- [Saulo Venancio](http://github.com/saulovenancio)
- [Slides](http://github.com/saulovenancio/AngularJS-Apresentacao)


- Existe data binding (2 vias)
- Classes dinâmicas (CSS)
- Repetidores
- Validação (legal)
- Filtro (auto complete)
- Olhar performance (benchmark) vs jQuery
- Escopo muda todo o conceito (nada a ver com jQuery)
- Angular observa aplicação e faz mágica para atualizar componentes
  - Se você mexe no DOM por fora do Angular, mágica não funciona
- Tentar não aumentar muito o controller
  - Tem Factory, Service, etc para ajudar
  - Service = Classe Singleton na verdade
- Diretivas (HTML)
- body ng-app = Bootstrap do App
- Tem injeção de dependência
- Teste integrado = [Protractor](http://angular.github.io/protractor/)
- Teste unitário [KarmaRunner](http://karma-runner.github.io)
- Frameworks UI
  - [AngularUI](http://angular-ui.github.io/)
  - [Ionic Framework](http://ionicframework.com/)
- Treinamento, cursos
  - [ngConf](http://www.ng-conf.org/)
  - [egghead.io](http://egghead.io/)
  - [PluralSight](http://pluralsight.com/)


## Unit Testing Android Apps
- [Felipe Lima](http://github.com/felipecsl)
- [We ♥ It](http://weheartit.com)


- [Three sins of Software Development](http://blog.ionelmc.ro/2014/08/14/the-three-sins-of-software-development/)
- Débito técnico = Entropia (Evitar ao máximo - usando testes)
- Olhar livro [Clean Code](http://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)
- Cinco princípios do TDD: [**SOLID**](http://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29)
  - **S** - Single responsibility principle
    - Uma classe deve ter somente uma responsabilidade. Somente uma mudança potencial na especificação do software deve poder mudar a especificação da classe
  - **O** - Open/closed principle
    - Entidades devem ser abertas para extensão, mas fechadas para modificação
  - **L** - Liskov substitution principle
    - Objetos devem ser substituíveis por instâncias de seus subtipos sem alterar a afinação do programa. [design by contract](http://en.wikipedia.org/wiki/Design_by_contract)
  - **I** - Interface segregation principle
    - Várias interfaces específicas de cliente são melhor que uma interface de propósito geral.
  - **D** - Dependency inversion principle
    - Deve-se depender de abstrações ao invés de objetos concretos
- [Is TDD Dead?](http://martinfowler.com/articles/is-tdd-dead/)
- Em geral se usa ferramentas normais de teste Java
  - [JUnit](http://junit.org/)
  - [Hamcrest](http://hamcrest.org/)
  - [Mockito](http://mockito.org/)
  - [AssertJ](http://joel-costigliola.github.io/assertj/)
    - [For Android](http://github.com/square/assertj-android)
  - [Roboletric](http://robolectric.org/)
- Testes aumentam velocidade da iteração de desenvolvimento
- [Why you don't get mocks](http://gmoeck.github.io/presentations/laruby-why-you-dont-get-mocks/)
  - Mock serve para testar mensagens entre objetos, não estado
- Dá para rodar testes pelo gradle
  - Pode testar somente uma classe, não tudo
- Teste funcional
  - [Calabash](http://calaba.sh/)
  - [Espresso](http://code.google.com/p/android-test-kit/wiki/Espresso)
  - [TestCloud](http://www.testcloud.io/) (testa vários devices na nuvem)
- Integração Contínua
  - [Jenkins](http://jenkins-ci.org/)
  - [Travis](http://travis-ci.org/)
  - [TeamCity](http://www.jetbrains.com/teamcity/)
- Xamarin também tem ferramentas de teste


## Internet of Things com Node.js
- [Vitor Leal](http://twitter.com/vitorleal)
- [Site](http://iot.telefonicabeta.com/)


- Vários projetos desse tipo no site da Campus Party
- Dá para usar Angular.js p/interface Web node.js
- Olhar kit-iot-4g e vivo telefonica iot sdk
- Node.js serialport
- [Github telefonicadigital](http://github.com/telefonicadigital)
- [Pi GPIO](http://www.npmjs.com/package/pi-gpio)
- [Johnny Five](http://github.com/rwaldron/johnny-five)
- Placas do mesmo estilo
  - Beagle Board
  - Banana Pi
  - Intel Galileo
  - [Tessel.io](http://tessel.io/) - Placa legal para trabalhar com node
    - Tem Wi-fi
    - É modular
- Existem planos da vivo M2M (machine 2 machine)
  - Transação de dados IOT
  - Smart center
  - Zigbee - Protocolo wifi


## Gradle com Android Studio
- [Lucas Montano](http://github.com/lucasmontano)
- [Slides](http://pt.slideshare.net/LucasMontano/devfestsul-2014-gradle)


- Product flavors = Ajuda no lance de ter versão paga / free do app
- Build Type = Ajuda no staging / release
- Dá para colocar assinaturas, chaves
- Gerenciamento de dependências
- Testes
- Integração Jenkins
- Docs
- Changelogs
- [Gradle Please](http://gradleplease.appspot.com/)
