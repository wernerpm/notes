# Curso IOS

- Olhar grupo de usuários GU Mobile RS


- Jetbrains AppCode - Alternativa xCode
- xCode - AppStore


- **Referências**
  - Podcast hora do mac
  - http://cimgf.com/
  - http://cocoadevcentral.com/
  - http://tryobjectivec.codeschool.com/
  - http://developer.apple.com/
    - Tem projetos de exemplo
  - stack overflow
  - http://iswift.com.br/
  - Cocoa Controls - templates apps, bibliotecas, gerenciador de dependências
  - Cocoa pods.org
  - Chupamobile - apps prontos
  - Parse chat (chat com lib de push)
  - Urban airship
  - Android dev bytes


- **Cloud**
  - Digital ocean
  - Heroku


- **Ver style guide**
  - github / nytimes / objective-c style guide
  - Organizer - gerencia projeto / devices do app


- **Ícones**
  - http://www.flaticon.com/
  - Freebie iPhone icons
  - Find icons
  - http://iconfinder.com/
  - Graphic River


- Push server (push notification)
  - Usar node de preferência
  - Tem que homologar servidor com a apple
- Olhar Chrome inspector - Tem simulador de device mobile
- Xamarin Studio - desenvolvimento mobile híbrido
- Exercício OlaObjectiveC - Exemplos objective C
  - Método começa com - => Dinâmico (de objeto)
  - Método começa com + => Estático (de classe)
- @protocol ≃ Interface
- @interface ≃ Classe
- @interface Carro : NSObject <CombustivelFlex>
  == class Carro extends NSObject implements CombustivelFlex
- OpenSocial => oAuth genérico
- popapp.in => Prototipagem App no papel
- NSString (readonly) ; NSMutableString (rw)
  - NSArray; NSMutableArray
    - NSMutableArray não é atômica (thread-safe)
    - ArrayCopy ou MutableCopy = copia primeiro nível
    - Deep Copy = copia árvore
      - Exercício 14 - CoreDataViewController
  - NSDictionary; NSMutableDicionary
  - String Builder (formatação string com sintaxe printf)
- Olhar github Felipe Kellerman
- Olhar estilo Drawer (painel escondido)
- Olhar master/detail para device deitado
  - Dá para ter 2 views no ViewController
    - Portrait / Landscape (Storyboard)
- Olhar aplicativo guaraná antarctica (Parece estilo iBeer)
- Lucio Maciel - Animações para desenvolvedores
  - (Video)
  - Github luciofm - animese / if I can
- Capptivate - Animações iOS
- lafosca.cat - Smooth custom animations in iOS
- Botar sempre NSLog nos eventos do AppDelegate
- Pragma Mark - Atalho para parte do código (Regions)
- ARC ≃ Garbage collection (reference counter)
- Pixel Mator = Editor de imagem (Photoshop)
- ViewController.h
  - IBAction - Métodos ação de botão (eventos da UI) tem que ser anotados como IBAction no ViewController
  - IBOutlet - Placeholder para objetos do storyboard (Marcar atributo como IBOutlet para poder referenciar objeto do storyboard)
  - Assistente (botão tuxedo) storyboard faz isso automático
    - Abrir .h e storyboard e arrastar com botão direito
- Underscore serve para referenciar variável do objeto this (self)
- String sempre inicia com @
- NSDictionary = Chave/Valor
- NSArray = Índice/Valor
- Ao criar componentes pelo código, tem que envolver eles num frame (retângulo)
  - CGRectMake
- Shell scripts (command line) são macros pro xCode
  - Olhar no dev.apple
  - Facilitadores, ex. botar número da versão do app = Número da Revisão do git
- Olhar links exercício 9 (AppDelegate.h e FirstViewController.m)
- Para passar propriedades de uma tela para outras, marcar como Strong , Nonatomic
  - Ou usar observer (olhar como)
- ViewController no storyboard pode ter Identify -> StorybardId
  - Exercício9 - ThirdViewController - l. 124
- Property weak: escopo da tela
  - strong: pode existir fora
- Não perder certificado original do dev center
  - Se não, certo que perdeu o app
- Modal customizada = xib que fica fora do storyboard
  - Fora do fluxo de navegação
  - Exercício 5
- Segue = transição de telas pelo storyboard
  - Segue push é só com nav. controller (breadcrumbs)
  - Se não é modal ou custom
- Olhar autoLayout (componentes preenchem tela independente da resolução)
- no Storyboard, apontar classe para o file's owner da tela (xib)
  - Assim, classe (ViewController) fica responsável por aquela tela
- Fazer cabeçalho de sessão (table) com sticky (snap)
  - Animação de movimentação da tabela fica mais legal
- AppAnnie - Analytics do app bem legal
- CGRectMake não usa ponteiro pq retorna struct (objeto c) do OS, não cria, aloca (init) - é do C
- É mais comum usar dispatch (thread) (Exercício 11) do que usar Assíncrono automático (Exercício 10)
- Para dar reload na API, usar WebSocket ou Observer (ex. paginação)
- Olhar NSHipster - notification center
- Usar pList para configuração
- Ajax
  - Olhar biblioteca PostMessage - Ajax cross domain
  - HTML5Rocks - CORS - Ajax cross domain
- Tutsplus - Gabriel Theododoropulos
- Criar observer para ver se está no Wifi ou 3G
- GDataXmlDocument - Lib Google para parse de XML
- Cydia - Store de apps com jailbreak
- http://www.datapoa.com.br/
- http://www.poatransporte.com.br/
- Ray Wenderlich
- dispatch_async ≃ Callback da thread
  - Função anônima, handler por parâmetro (chamam de blocks, identifica com acento ^)
- CoreData = Armazenamento simples
  - FMDB é bem mais legal que SQLite direto
    - github / ccgus / fmdb
  - http://www.victorbaro.com/
  - JsonModel - Tem no CocoaPods
- Rubymotion - Programar iOS e OSX com Ruby
- Olhar mac magazine - economia de bateria
- Empty View, Master / detail, já vem com CoreData
- Projeto -> Edit Scheme: Passa argumentos para run
  - com.apple.coredata.sqldebug = 1
  - Debuga SQL
