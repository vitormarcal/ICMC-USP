<p align="center">
  "<strong>Everyone should learn how to program a computer, because it teaches you how to think."</strong><br><br> - Steve Jobs
    <br>
  </p>

<br><br>

## English

- [Mairo Vergara](http://www.mairovergara.com/)
- [Anki](https://apps.ankiweb.net/)
- [Grammarly](https://www.grammarly.com/)

## Roadmap Software Engineering

- [Teach Yourself Programming in Ten Years - Peter Norvig](http://norvig.com/21-days.html)
- [Coding Interview University](https://github.com/jwasham/coding-interview-university)
- [Teach Yourself CS](https://teachyourselfcs.com/)
- [CS50 Harvard](https://www.youtube.com/user/cs50tv/videos)
- [wiki.icmc.usp.br](http://wiki.icmc.usp.br/index.php/P%C3%A1gina_principal_CoteiaWIKI)
- [edx.org/computer-science](https://www.edx.org/course/subject/computer-science)
- [coursera.org/algorithms](https://pt.coursera.org/courses?query=algorithms)
- [Electrical Engineering and Computer Science - MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/)

## Useful Tools

 - [StackOverFlow](https://stackoverflow.com/)
    - [Insights StackOverFlow](https://insights.stackoverflow.com/)
    - [Trends StackOverFlow](https://insights.stackoverflow.com/trends?tags=r%2Cstatistics)
 - [LastPass](https://www.lastpass.com/pt)
    - Software to save, create and remember all your passwords 
 - [cheatsheet do git-flow](https://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html)
 - Ruby on Rails
    - $ sudo apt update
    - $ sudo apt install ruby-full
    - $ ruby --version
    - $ gem install rails
    - $ rails --version
    - [$ rails new blog](https://guides.rubyonrails.org/getting_started.html)
    - $ cd blog
    - $ bin/rails server

## Algorithms and Data Structs

 - YouTube
    - [Linguagem C Programação Descomplicada](https://www.youtube.com/user/progdescomplicada/videos) :skull:
 - Sites
    - [GeeksForGeeks](https://www.geeksforgeeks.org/)
    - [AssemblyProgressivo.net](https://www.assemblyprogressivo.net/)
- Code Training
    - [Project Euler](https://projecteuler.net/)
    - [HackerRank](https://www.hackerrank.com/)
    - [Edabit](https://edabit.com)
    - [URI Online Judge](https://www.urionlinejudge.com.br/judge/en/login)
- KhanAcademy
   - [Computer Science](https://www.khanacademy.org/computing/computer-science)
   - [Notação assintótica](https://pt.khanacademy.org/computing/computer-science/algorithms/asymptotic-notation/a/asymptotic-notation)
- Recursion :skull:
   - [O que é recursão? Teste de Mesa com Fatorial - Softblue](https://www.youtube.com/watch?v=V60g61dhKmg)
- Data Structs Visualization
   - [VisualGo](https://visualgo.net/en)
   - [University of San Francisco - CS](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)
- Work Hard, Make Things, Have Fun & Make History :smile: :baby: :heart: 
   - [RaspberryPi](https://www.raspberrypi.org/homepage-9df4b/)
      - [Noobs - Beginners should start with NOOBS – New Out Of the Box Software](https://www.raspberrypi.org/downloads/noobs/)
      - [Lakka](https://www.lakka.tv/)
      - [RetroPie](https://retropie.org.uk/)
   - [Embarcados](https://www.embarcados.com.br/)
   - [Arduino](https://www.arduino.cc/)
      - [Manual Maker | Manual do Mundo - YouTube PlayList](https://www.youtube.com/watch?v=gcBN4NLqz_U&list=PLYjrJH3e_wDNLUTN32WittrpBxeleEqNp)
      - [ArduinoCreate Online](https://create.arduino.cc/)
      - [Brasilino](https://otacilion.github.io/Brasilino/)
         - Uma biblioteca que permite programar em linguagem Arduino utilizando comandos facilitados em PT-BR.
   - [MIT Scratch](https://scratch.mit.edu/projects/editor/)
   - [Pico8](https://www.lexaloffle.com/pico-8.php)
      - [NerdyTeachers](https://nerdyteachers.com/)
      - [NerdTeachers YouTube](https://www.youtube.com/channel/UCbMjF_cWciuBUZjILNL1fyA)
   - [CodeCombat](https://codecombat.com/) 
   - [Code.org](https://code.org/)
   - [CodeMonkey](https://www.playcodemonkey.com/)
   - Cartoons
      - [MonkeyUser](https://www.monkeyuser.com/)
      - [VidaDeProgramador](https://vidadeprogramador.com.br/)
      - [VidaDeHipster](https://www.vidadehipster.com.br/)
   - <strong>Onde Comprar?</strong>
      - [FilipeFlop](https://www.filipeflop.com) 
- Big O
   - [A beginner's guide to Big O notation](https://rob-bell.net/2009/06/a-beginners-guide-to-big-o-notation/)
   - [A coffee-break introduction to time complexity of algorithms](https://dev.to/vickylai/a-coffee-break-introduction-to-time-complexity-of-algorithms-160m?utm_source=digest_mailer&utm_medium=email&utm_campaign=digest_email)
   - O(1) Constant Time
      - Best Case Possible
      - If an algorithm has a constant time, it means that it always takes the same amount time to produce the output.
      - Example: array.pop()
   - Logarithms O(log n)
      - Preferible in most of times
      - Logarithms are the inverse of exponentiation.
      - Example: Classic Binary search algorithm -> divide-to-conquer
      - <img src="ologn.png" alt="ologn">
   - Linear time O(n)
      - Preferible in most of times
      - If an algorithm has a linear time, it means that the running time of an algorithm grows as the input size grows.
      - Example: array.forEach() sum all values
   - Linear Logarithms O(n log n)
      - Acceptable
      ```
      x = n
      while ( x > 0 ) {
        y = x
        while ( y > 0 ) {
           y = y / 2
        }
        x -= 1
      }
      ```
      - Examples: classic Quicksort, Mergesort and Heapsort  -> divide-to-conquer
   - Quadratic time O(n²) :skull:
      - Nice To Avoid
      - The running time of an algorithm is directly proportional to the square of the size of the input.
      - Example: Sum of matrizes
      ```
      for (var outer = 0; outer < elements.Count; outer++){
        for (var inner = 0; inner < elements.Count; inner++){
          ...
        }
      }
      ```
   - Exponential Time O(2^n) :skull: :skull:
      - Worst Case Possible, always try to avoid
      - Denotes an algorithm whose growth doubles with each additon to the input data set. The growth curve of an O(2N) function is exponential - starting off very shallow, then rising meteorically
      - Example: recursive calculation of Fibonacci numbers
      ```
      int Fibonacci(int number){
          if (number <= 1) return number;
          return Fibonacci(number - 2) + Fibonacci(number - 1);
      }
      ```
   - <strong>Resume</strong>
      - <img src="big-o-names.jpeg" alt="Big(O) Names">
      - <img src="big-o-graphic.jpeg" alt="Big(O) Graphic">

## [Unix](https://pt.wikipedia.org/wiki/Unix)

 - [Linux](https://www.linuxfoundation.org/)
    - Sites
       - [Guia Foca](http://www.guiafoca.org/?page_id=51)
       - [SS64 - Commands CLI References](https://ss64.com/)
       - [Kernel.org](https://www.kernel.org/)
    - Funny Commands
       - $ fortune 
          - If you are demotivated, maybe this command can be useful :smile:
       - $ sl  
          - Sheldon Cooper sure likes this command :smile:
       - $ cmatrix
          - man, I'm a hacker, wait, Neo it's you? :smile:
       - $ cowsay "I'm Awesome!"
          - Wait, what is a cow doing here? :smile:
       - $ xcowsay "I'm More Awesome!"
          - Holy shit, this cow is more awesome. :smile:
       - $ espeak "phrase here"
          - I'm making contact with aliens man! :smile:
    - Apps for Learn Linux CLI Commands
       - [Linux Command Library](https://play.google.com/store/apps/details?id=com.inspiredandroid.linuxcommandbibliotheca&hl=en&rdid=com.inspiredandroid.linuxcommandbibliotheca)
    - YoTube
       - [Diolinux](https://www.youtube.com/user/Diolinux)
       - [Toca do Tux](https://www.youtube.com/channel/UCkATW9o8m4pnXAAmac2o63Q)
       - [Curso de Linux Básico / Certificação LPIC1 - Bóson Treinamentos](https://www.youtube.com/watch?v=u16ZDPcf8Rc&list=PLucm8g_ezqNp92MmkF9p_cj4yhT-fCTl7)
    - Tools
       - [AnyDesk](https://anydesk.com)
       - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
       - [Etcher - Flash OS images to SD cards & USB drives](https://etcher.io/)
       - [Rufus.ie for Windows](https://rufus.ie)
       - [WineHQ](https://www.winehq.org/)
       - [Vim Para Noobs](https://woliveiras.com.br/vimparanoobs/)
    - Games
       - [Lutris.net :video_game:](https://lutris.net/)
       - [$ sudo apt install zsnes :video_game:](http://www.zsnes.com/)
       - [$ sudo apt install playonlinux :video_game:](https://www.playonlinux.com/en/)
    - Operation System
       - [<strong>Lubuntu 18.04 LTS (Bionic Beaver) -> OS I currently Use and Recommend (It's better than windows at least)</strong>](https://lubuntu.net/)
 - FreeBSD
    - Sites
       - [Documentation PT-BR](https://www.freebsd.org/doc/pt_BR.ISO8859-1/)
    - Books
       - [FreeBSD: O Poder dos Servidores em Suas Mãos - 2 Edição](https://www.amazon.com.br/FreeBSD-Poder-Servidores-Suas-M%C3%A3os-ebook/dp/B00FFZOE8Y)

## Windows

 - Serious? Start using Linux please, much better
 - Sites
    - [Baboo](https://www.baboo.com.br/)
    - [Baboo Cursos](https://www.baboocursos.com.br/)
 - Tools
    - [Cmder](http://cmder.net/)

## Hardware

 - Sites
    - [ClubeDoHardware]()
 - Books
    - [Hardware Curso Completo - Gabriel Torres](https://www.clubedohardware.com.br/livros/esgotados/hardware-curso-completo-4%C2%AA-edi%C3%A7%C3%A3o-2001-r10/)

## Security 

 - Sites
    - [OWASP](https://www.owasp.org/index.php/Main_Page)
    - [EUGDPR.org](https://eugdpr.org/)
    - [LGPD - Lei Geral de Proteção de Dados Pessoais](http://www.planalto.gov.br/ccivil_03/_Ato2015-2018/2018/Lei/L13709.htm)
    - [Livro - Fundamentos de Engenharia Reversa - Mente Binária](https://mentebinaria.gitbook.io/engenharia-reversa/antes-de-comecar)
    - [Forum CaveiraTech](https://caveiratech.com/forum/)
 - YouTube
    - [Gabriel Pato](https://www.youtube.com/channel/UC70YG2WHVxlOJRng4v-CIFQ)
    - [CaveiraTech](https://www.youtube.com/user/caveiratech2/playlists)
    - [Curso de Engenharia Reversa Online - Papo Binário](https://www.youtube.com/watch?v=IkUfXfnnKH4&list=PLIfZMtpPYFP6zLKlnyAeWY1I85VpyshAA)
 - Courses 
    - [Fundamentos de Ethical Hacking - Udemy](https://www.udemy.com/fundamentos-de-ethical-hacking/learn/v4/)
    - [Solyd](https://solyd.com.br)
    - [Técnicas de Invasão](https://tecnicasdeinvasao.com/)
    - [Desenvolimento de Software Seguro - Curso Online Gratuito - ICA Instituto ](https://desenvolvimentoseguro.icainstituto.com.br/)
 - [DAT Protocol](https://www.datprotocol.com/)
    - [DatProject.org](https://datproject.org)
    - [Try Dat](https://try-dat.com/)
 - Database
    - World's fastest password cracker
       - [HashCat](https://hashcat.net/hashcat/)
    - Recommended Data Encryption
       - [Argon2](https://github.com/P-H-C/phc-winner-argon2)
       - [PBKDF2](https://en.wikipedia.org/wiki/PBKDF2)
       - [Scrypt](https://en.wikipedia.org/wiki/Scrypt)
       - [BCrypt](https://en.wikipedia.org/wiki/Bcrypt)
    - NOT RECOMMENDED
       - [MD5](https://pt.wikipedia.org/wiki/MD5)
       - [SHA1 | SHA2 | SHA256](https://www.thesslstore.com/blog/difference-sha-1-sha-2-sha-256-hash-algorithms/)
 - Tools
    - Operation Systems
       - [Kali Linux](https://www.kali.org/)
       - [Tails Linux](https://tails.boum.org/index.pt.html)
    - Virtual Machines for Pentest
       - [PentesterLab](https://www.pentesterlab.com/exercises/)
       - [PentestBox](pentestbox.org)
          - [tools.pentestbox.org](https://tools.pentestbox.org/)
    - Transport Layer Security/Secure Sockets Layer
       - [Let's Encrypt](https://letsencrypt.org/)
    - Softwares
       - [WireShark](https://www.wireshark.org/)
       - [metasploit](https://www.metasploit.com/)
	   - DataBases
	      - [Exploit-DB](https://www.exploit-db.com/)
	      - [SQLMap](http://sqlmap.org/)
	   - Useful CLI Commands
	      - [$ nmap site_url](https://nmap.org/)
	      - [$ traceroute site_url](https://www.lifewire.com/traceroute-linux-command-4092586)
	      - [$ curl site_url](https://curl.haxx.se/)
	      - [$ whafw00f site_url](https://github.com/EnableSecurity/wafw00f)
	      - [$ ping site_url](https://www.wikiwand.com/en/Ping)
	      - [$ host site_url](https://www.computerhope.com/unix/host.htm)
	      - [$ whois site_url](https://who.is/)
	   - Browsers
	      - [DuckDuckGo](https://duckduckgo.com)
	      - [Bernes Lee Solid](https://solid.mit.edu/)
	      - [Beaker Browser](https://beakerbrowser.com)
	      - [TorProject](https://www.torproject.org/)
	         - [TheHiddenWiki](https://thehiddenwiki.org/)
          
## Functional Programming

- [Aprender Haskell será um grande bem para você](http://haskell.tailorfontela.com.br/)

## Open Source
 
 - Sites
    - [OpenSource.org](https://opensource.org/)
    - [OpenSource.Guide](https://opensource.guide/)
    - [Creative Commons](https://creativecommons.org/)
    - [Scrum Poker Online](https://scrumpoker.online/)

## Online Courses

- [Udemy - Courses I'm enrolled](https://www.udemy.com/user/alex-galhardo-vieira/)
- [Coursera - Learning How to Learn: Powerful Mental Tools to Help You Master Tough Subjects](https://www.coursera.org/learn/learning-how-to-learn)

## Blogs

- [Medium :muscle:](https://medium.com/)
- [Quora :muscle:](https://quora.com/)
- [Akita on Rails :muscle:](http://www.akitaonrails.com/)
- [Reddit :muscle:](https://www.reddit.com)
- [Rafael Falcon](https://rafaelfalcon.com.br/)
- [Hacker News](https://news.ycombinator.com/)
- [Stalt](https://staltz.com/)
- [JornadaPeloConhecimento](https://medium.com/petrobras)
- [Joel Spolsky OnSoftware](https://www.joelonsoftware.com/)
- [WaitButWhy](https://waitbutwhy.com/)
- [ThinkWithGoogle](https://www.thinkwithgoogle.com/)
- [Hacks Mozilla](https://hacks.mozilla.org/)
- [Willian Justen](https://willianjusten.com.br/)
- [Felipe Fialho](https://www.felipefialho.com/)
- [Luiz Tools](http://www.luiztools.com.br/)
- [Henrique Bastos](https://henriquebastos.net)
- [RockSeat](https://rocketseat.com.br/) 
- [Umbler Blog](https://blog.umbler.com)
- [InfoQ](https://www.infoq.com/)
- [WBruno](http://wbruno.com.br/)
- [Nateliason](https://www.nateliason.com)
- [RamonSilva](http://ramonsilva.net/)
- [O Futuro Das Coisas](https://ofuturodascoisas.com/)
- [Filipe Deschamps](https://www.filipedeschamps.com.br/)
- [BugginhoAcademy](https://bugginhoacademy.com.br/blog/)
- [Gabs Ferreira](http://gabsferreira.com/)
- [Jaydson Gomes](https://jaydson.com/)
- [Phil Calcado](http://philcalcado.com/)
- [VidaDeSuporte](https://vidadesuporte.com.br/)
- [TiagoGouvea](https://www.tiagogouvea.com.br/)
- [VidaDeProgramador](https://vidadeprogramador.com.br/)
- [ProfissionaisTI](https://www.profissionaisti.com.br/)

## Nice Articles

 - [Getting Real - the smarter, faster, easy way to build a sucesfull web application - BaseCamp](https://basecamp.com/books/getting-real)
 - [O que é propósito de vida - Mopora](https://mopora.com/artigos/o-que-e-proposito-de-vida/)
 - [The Invented History of 'The Factory Model of Education'](http://hackeducation.com/2015/04/25/factory-model)
 - [The Humble Programmer by Edsger W. Dijkstra](https://www.cs.utexas.edu/~EWD/transcriptions/EWD03xx/EWD340.html)
 - [Educação Clássica e Homeschooling](https://www.youtube.com/watch?v=LjJlus8oC9M)
 - [Principles for Success - Ray Dalio](https://www.principles.com/principles-for-success/)
 - [Write Code Every Day - John Resig](https://johnresig.com/blog/write-code-every-day/)
 - [Why Good Programmers Are Lazy and Dumb](http://blogoscoped.com/archive/2005-08-24-n14.html)
 - [The Feynman Technique: The Best Way to Learn Anything - Easy to Understand | Hard To Master](https://fs.blog/2012/04/learn-anything-faster-with-the-feynman-technique/)
 - [WaitButWhy - The Cook and the Chef: Musk’s Secret Sauce - Easy to Understand | Hard to Master](https://waitbutwhy.com/2015/11/the-cook-and-the-chef-musks-secret-sauce.html)
 - [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)
 - [The Ten Commandments of Egoless Programming](https://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/)
 - [What makes a good programmer?](http://www.techfounder.net/2009/07/22/what-makes-a-good-programmer/?subscribe=error#509)
 - [Self-Education: Teach Yourself Anything with the Sandbox Method](https://www.nateliason.com/blog/self-education)
 - [As 36 Estratégias Secretas Chinesas](https://ideiasesquecidas.com/2018/03/23/as-36-estrategias-secretas-chinesas/)
 - [The Twelve Factor App - Heroku](https://12factor.net/)
    - A aplicação doze-fatores é uma metodologia para construir softwares-como-serviço.
    - I. Base de Código
       - Uma base de código com rastreamento utilizando controle de revisão, muitos deploys
    - II. Dependências
       - Declare e isole as dependências
    - III. Configurações
       - Armazene as configurações no ambiente
    - IV. Serviços de Apoio
       - Trate os serviços de apoio, como recursos ligados
    - V. Build, release, run
       - Separe estritamente os builds e execute em estágios
    - VI. Processos
       - Execute a aplicação como um ou mais processos que não armazenam estado
    - VII. Vínculo de porta
       - Exporte serviços por ligação de porta
    - VIII. Concorrência
       - Dimensione por um modelo de processo
    - IX. Descartabilidade
       - Maximizar a robustez com inicialização e desligamento rápido
    - X. Dev/prod semelhantes
       - Mantenha o desenvolvimento, teste, produção o mais semelhante possível
    - XI. Logs
       - Trate logs como fluxo de eventos
    - XII. Processos de Admin
       - Executar tarefas de administração/gerenciamento como processos pontuais

## Communities

- [BrazilJS](https://braziljs.org/)
- [FrontEnd Br](https://github.com/frontendbr)
- [Training Center](https://github.com/training-center)
- [BackEnd Br](https://github.com/backend-br)
- [Comunidades Web](https://github.com/brasil-php/comunidades)
- [NodeJS Brasil - Facebook](https://www.facebook.com/groups/nodejsbrasil/about/)
- [Dev Translate](https://github.com/devtranslate)
- [CodamosClub](https://www.codamos.club/)
- [HashNode](https://hashnode.com/)
- [Mulheres na Computação](https://mulheresnacomputacao.com/)
- [Dev Newsletters](https://devnewsletters.github.io/)

## Podcasts

 - Technology & Arts & Games & Science 
    - Portuguese
       - [Dev Na Estrada](https://devnaestrada.com.br/)
       - [HipsterTech](https://hipsters.tech/)
       - [NerdTech](https://www.alura.com.br/podcast-nerdtech)
       - [LoopMatinal](http://www.loopmatinal.com/)
       - [Syntax](https://syntax.fm/)
       - [Sinapse](https://anchor.fm/sinapse)
       - [DataBase Cast](http://databasecast.com.br/wp/)
       - [Podprogramar](https://mundopodcast.com.br/podprogramar/)
       - [SudoCast](https://github.com/sudocast)
       - [OneBitCode](https://onebitcode.com/category/podcast/)
       - [QuebraDev](http://quebradev.com.br/)
       - [Zofe](https://zofe.com.br/)
       - [ElementCast](https://elemencast.github.io/#/episodios/6)
       - [Egermano](https://anchor.fm/egermano)
       - [Revolution](https://www.youtube.com/channel/UCRmG9ZyWxUenzxfoyatqp3A)
       - [SciCast](http://www.deviante.com.br/podcasts/scicast/)
       - [MeiaLua](http://www.deviante.com.br/podcasts/meialua/)
       - [Miçangas](http://www.deviante.com.br/podcasts/micangas/)
       - [TecnoCast](https://tecnoblog.net/categoria/podcast/)
       - [TricoTech](http://www.trico-tech.com/)
       - [GGDevCast](https://ggdevcast.com.br/)
       - [Por Trás dos Controles](https://www.radio.ufscar.br/shows/por-tras-dos-controles/)
       - [PixelsInk](https://www.cgmagonline.com/media/podcasts/pixels-ink/)
       - [DragoesDeGaragem](http://dragoesdegaragem.com/)
       - [Reloading](http://reloading.com.br/)
       - [RPGGuaxa](http://www.deviante.com.br/podcasts/rpguaxa/)
    - English
       - [CodeNewbie](https://www.codenewbie.org/)
       - [ShopTalk Show](https://shoptalkshow.com/)
       - [Learn To Code With Me](https://learntocodewith.me/podcast/)
       - [DeveloperTea](https://spec.fm/podcasts/developer-tea)
       - [Indie Hackers Podcast](https://www.indiehackers.com/podcast)
       - [FreeCodeCamp](https://freecodecamp.libsyn.com/)
       - [This Developers Life](http://thisdeveloperslife.com)
       - [CodingBlocks](https://www.codingblocks.net/)
       - [Changelog](https://changelog.com/podcast)
       - [FZDPodcast](http://fzdpodcast.com/)
       - [Programming Throwdown](https://www.programmingthrowdown.com/)
       - [Software Engineering Radio](http://www.se-radio.net/)
       - [GeekSpeak](https://geekspeak.org/)
       - [DevChat.TV](https://devchat.tv/)
       - [JavaScript Jabber](https://devchat.tv/js-jabber/)
       - [FullStack Radio](http://www.fullstackradio.com/)
       - [Twit.TV](https://www.twit.tv/)
       - [This Week In Tech](https://www.twit.tv/shows/this-week-in-tech)
       - [Security Now](https://www.twit.tv/shows/security-now)
       - [Floss Weekly](https://www.twit.tv/shows/floss-weekly)
       - [The Knowledge Project](https://fs.blog/the-knowledge-project/)
 - Entrepreneurship & Others
    - Portuguese
       - [GVCast](https://geracaodevalor.com/gvcast/)
       - [Heroes 12 minutos](https://soundcloud.com/heroes-12min-podcast)
       - [Like a Boss](https://www.likeaboss.com.br/)
       - [Decrepitos](https://decrepitos.com/)
       - [CarreiraSemFronteiras](https://www.carreirasemfronteiras.com.br)
       - [GunCast](https://blog.keeplearning.school/guncast)
       - [NerdCast](https://jovemnerd.com.br/nerdcast)
       - [PapriCast](http://paprica.org/categoria/papricast/)
       - [B9 Podcasts](https://www.b9.com.br/podcasts/)
       - [ResumoCast](https://www.resumocast.com.br/)
       - [AntiCast](http://anticast.com.br/)
       - [ChutandoAEscada](https://chutandoaescada.com.br/)
       - [DicasCurtas](https://dicascurtas.com.br/)
       - [EscribaCafe](https://escribacafe.com/tagged/podcast)
    - English
       - [Tim Ferris Podcast](https://tim.blog/podcast/)
       - [Masters Of Scale](https://mastersofscale.com/)
       - [Rework.FM](https://rework.fm/)
       - [MadeYouThinkPodcast](https://madeyouthinkpodcast.com/)

## Software Engineering Principles

 - [Adams Óbvio](https://www.amazon.com/dp/8562409189?tag=bizzi0d-20)
 - "Bad software that adds value > best software in the world that does not add value"
 - "Learn to say: I DONT KNOW"
 - "Premature Optimization: the Root of All Evil"
 - "Remember that dinosaurs are almost always the best references"
 - "Who thinks little, make more mistakes"
 - "In God we trust; All others must bring data"
 - "Lack of money is the root of all evil"
 - "Doesn't exist silver bullet"
 - "Make it Work > Make it Correct"
 - "Increase Revenue > Lower Costs"
 - "SaaS > PaaS > IaaS > In-House"
 - "You != Unicorn"
 - "Always try to understand what is happening under the hoods"
 - "Write code != programming != software engineering"
 - "Maintainability > Performance"
 - "No Metrics, No Optimization"
 - "NEVER EVER Stop Questioning"
 - "Software engineering is 80% thinking ABOUT the problem, and 20% thinking HOW to solve the problem"
 - "The more knowledge you have, the less you know. Ego = 1 / knowledge"
 - "Everyone should care about the quality"
 - "99% of good software code has been thrown away"
 - "2 + 2 is not 5, no matter how many people say it"
 - "Principles > Analogy"
 - "Talk and learn from people smarter than you"
 - "Always try to use Single Source of Truth"
 - "Do not reinvent the wheel"
 - "It is always good to study a tool deeply before using it in production"
 - "Modularization is everything"
 - "Good artists copy, great artists steal"
 - "Innovation only exists in a world of restraint and not of abundance"
 - "Always will have something to improve, done is better than perfect"


## School Of Life

 - A vida não é fácil, se acostume com isso. - Bill Gates
 - Se você colocar o Einstein para jogar basquete com Michael Jordan, o Jordan vai achar que o Einstein é incompetente. Se você colocar o Jordan para fazer física teórica com Einstein, o Einstein vai achar que o Jordan é incompetente. Quase tudo na vida é relativo. Nenhum ser humano consegue analisar todas as variáveis de uma situação subjetiva.
 - Meritocracia é um termo extremamente relativo, e na maioria das vezes, é uma idiotice que não existe.
 - A vida nunca foi, não é, e nunca será justa.
 - Se você é a pessoa mais inteligente da sala, você está na sala errada.
 - Existem gênios sem educação formal e idiotas com doutorado.
 - Se você quiser julgar o caráter de um ser humano, dê poder a ele. - Abraham Lincoln
 - Aprenda a gostar de estudar a história da humanidade, para não cometer os mesmos erros do passado.
 - Não sonhe o sonho dos outros.
 - Inteligente é quem aprende com os próprios erros, sábio é quem aprende com o erro dos outros.
 - Não existe almoço grátis, tudo tem um preço.
 - Você é livre para fazer o que quiser, mais sempre será escravo das consequências.
 - Toda ação, possui uma reação.
 - A melhor forma de vingança é a ignorância.
 - Você é a média das 5 pessoas que mais convive.
 - Se todos os seres humanos se cooperassem entre si, todos sairiam ganhando. (Teoria dos Jogos)
 - O mundo não deve nada a ninguém.
 - Se você acha que filosofia é inútil, você ainda não entendeu o que é filosofia.
 - Existem adultos com 15 anos e crianças com 25. Idade e experiência não necessariamente significa sabedoria e amadurecimento.
 - O homem não vive sem a mulher, e a mulher não vive sem o homem, não existe sexo melhor que o outro.
 - No leito de morte, dinheiro e bens materiais são irrelevantes. O que é viver se não um passatempo antes da morte?
 - A maioria das pessoas não vivem, apenas existem. Algumas por falta de oportunidades, outras por opção e alienação.
 - Todos os seres humanos tem o direito de serem felizes. Mas cada ser humano é responsável pela própria felicidade.
 - A melhor universidade do mundo se chama "Internet" e o melhor professor se chama "Google"
 - Se você criar uma águia no meio de galinhas, ela vai agir e pensar que é igual a elas. Autoconhecimento provavelmente é a coisa mais importante que um ser humano pode ter em sua vida.  
 - Tentar agradar ou ser amigo de todo mundo é um dos segredos para o fracasso e a infelicidade.
 - Justiça, ética e moral não existem, são apenas termos criados por seres humanos. Os animais e a natureza não se importam com isso. Mas não faça com os outros o que não gostaria que fizessem com você. 
 - Antes de ter, você tem que ser.
 - Nunca, jamais, venere ou idolatre outro ser humano.
 - O mundo e a sociedade não dão a mínima para o quão inteligente, bondoso, humilde ou esforçado você seja. Eles só se importam com o valor que você agrega a eles.
 - Lamentável o aprendiz que não ultrapasse seu mestre. - (Leonardo da Vinci). O mestre deve se esforçar para ensinar seu aprendiz a ser melhor do que ele, e o aprendiz deve se esforçar para ser melhor do que seu mestre. É assim que a humanidade evolui.
 - Nunca perca tempo discutindo com alguém que se acha dona da verdade absoluta.
 - O conhecimento sempre existiu, basta buscá-lo.
 - Não da para ter ou fazer tudo que quer durante a vida.
 - Nunca pare de questionar, principalmente as autoridades.
 - Nunca acredite 100% no que os outros dizem, principalmente as autoridades.
 - Nunca acredite em dogmas ou verdades absolutas.
 - A questão não é quem você é hoje, mais a pessoa que você poderá ser amanhã.
 - Aprenda a pensar por si mesmo. Busque por informações e tire suas próprias conclusões.
 - Ninguem inveja o feio e nem odeia o fraco.
 - Mar calmo nunca fez bom marinheiro.
 - Pessoas que não sentem medo, já morreram.
 - 80% dos resultados, vem de 20% dos esforços.
 - Tem coisas na vida que simplesmente levam tempo para acontecer. Não adianta apressar as coisas.
 - Monopólio nunca foi, é, ou será algo bom.
 - Um rei só é um rei porque todo seu povo concente com isso.
 - De centavo em centavo se chega a um milhão.
 - O povo não deve temer seu governo, o governo que deve temer seu povo. - V de Vingança 
 - Ser grato pela vida, pelo que tem e pelo que já conquistou.
 - Você precisa ver o macro, para entender muito bem o micro. 
 - Nenhum ser humano consegue mudar outro ser humano. Cada um é responsável pela própria mudança.
 - O mundo da voltas. Quem está por cima hoje, pode estar por baixo amanhã.
 - Quanto menos pessoas souberem da sua vida pessoal, melhor.
 - Conhecimento e ideias por si só são inutéis se não aplicados na prática.
 - Um dos maiores problemas dos seres humanos, é que eles não gostam de pensar.
 - A natureza não nos deu 2 ouvidos e apenas 1 boca atoa.
 - Investir em conhecimento sempre rende os melhores juros. - Benjamin Franklin
 - Se você acha que investir em conhecimento é caro, não queira conhecer o preço da ignorância.
 - Nem todo leitor é um líder, mas todo líder é um leitor. Porém ler muito por si só não significa nada, o que importa é o aprendizado prático que você tira da leitura. Nem todo livro deve ser lido por completo.
 - Nenhum ser humano é 100% bom ou 100% ruim.
 - Desconfie de seres humanos que dizem que nunca se arrependeram de nada.
 - Todo ser humano já mentiu, mente, ou vai mentir.
 - Se comparar com os outros é uma das piores coisas que um ser humano pode fazer em sua vida. Não queira ser igual os outros, seja você mesmo. O mundo seria muito chato se todos fossem iguais.
 - Ninguém é tão grande que não possa aprender, nem tão pequeno que não possa ensinar.
 - Um dia sem aprender algo novo, é um dia perdido.
 - Seja uma criança, mas não seja infantil.
 - O essencial é invisível aos olhos. - O Pequeno Príncipe.
 - Todo ser humano, em sua essência, é egoista.
 - Ninguém é melhor do que ninguém. No final, o buraco é o mesmo para todo mundo.
 - 99.99% do que acontece na vida não somos nós que controlamos. "Livre-Arbítrio" na maior parte da vida é uma ilusão. (Estoicismo, Rápido e Devagar, Teoria do Caos, etc)
 - Muitas pessoas gastam dinheiro que não tem, para comprar coisas que não precisam, para impressionar pessoas que não gostam.
 - Todo mundo é um gênio. Mas se você julgar um peixe por sua capacidade de subir em uma árvore, ele vai gastar toda a vida acreditando que é estúpido.
 - Não existe receita de bolo de como viver a vida. Cada ser humano vive sua própria filosofia de vida.
 - Não julgue a fé alheia. Ninguém realmente sabe o que existe além deste mundo.
 - O cérebro humano é a coisa mais complexa que existe no universo. Nunca acredite que você conhece realmente outro ser humano.
 - A força de vontade é a maior força que existe no universo.
 - Os homens perdem a saúde para juntar dinheiro, depois perdem o dinheiro para recuperar a saúde. A maioria das pessoas vivem como se nunca fossem morrer, e morrem como se nunca tivessem vivido.
 - O que sabemos é uma gota, o que ignoramos é um oceano. - Newton
 - Nenhum ser humano é "especial". É só estudar um pouco de Astronomia para entender isso.


## YouTube #StopWatchingTV

 - Technology
    - [Curso em Video](https://www.youtube.com/user/cursosemvideo)
    - [Fabio Akita](https://www.youtube.com/channel/UCib793mnUOhWymCh2VJKplQ)
    - [EstudoNauta](https://www.youtube.com/channel/UCJcWQ9MgPlHIFMx8uDWEYNg)
    - [Fábrica de Noobs](https://www.youtube.com/channel/UCGObNjkNjo1OUPLlm8BTb3A)
    - [COD3R CURSOS](https://www.youtube.com/channel/UCcMcmtNSSQECjKsJA1XH5MQ/featured)
    - [CodigoFonte TV](https://www.youtube.com/user/codigofontetv)
    - [BrasilJS](https://www.youtube.com/user/BrazilJS)
    - [FreeCodeCamp](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
    - [Papo Binário](https://www.youtube.com/channel/UCuQ8zW9VmVyml7KytSqJDzg)
    - [Baboo](https://www.youtube.com/user/baboo/videos)
    - [CodellabCode](https://www.youtube.com/channel/UCVheRLgrk7bOAByaQ0IVolg)
    - [CanalTech](https://www.youtube.com/user/canaltechbr)
    - [O Universo da Programação](https://www.youtube.com/channel/UCWrqsnPLl6aRX0ECUmPaZEw)
    - [UNIVESPTV](https://www.youtube.com/user/univesptv/playlists)
    - [Engenharia Reversa](https://www.youtube.com/channel/UCagV1LuB6C52fFtZwVywZYg)
    - [TheHardwareShow](https://www.youtube.com/channel/UCiXDLhXSFZdnu1OWxwGvPTw)
    - [DevNaEstrada](https://www.youtube.com/channel/UCtIygB7LtILSFWR0kxtZC-A/videos)
    - [RocketSeat](https://www.youtube.com/channel/UCSfwM5u0Kce6Cce8_S72olg/videos)
    - [Bóson Treinamentos](https://www.youtube.com/user/bosontreinamentos)
    - [ProgramadorBR](https://www.youtube.com/channel/UCrdgeUeCll2QKmqmihIgKBQ)
    - [Laboratório da Júlia](https://www.youtube.com/channel/UChfu9xWITOvsXYLKm7hieSQ)
    - [Bonieky Lacerda](https://www.youtube.com/channel/UCw9mYSlqKRXI6l4vH-tAYpQ)
    - [Rodrigo Souza](https://www.youtube.com/channel/UCdHcO3zYXVco91CIAk1u4PA)
    - [SoftBlue](https://www.youtube.com/user/softbluecursos)
    - [Computherpile](https://www.youtube.com/user/Computerphile)
    - [A história da Tecnologia - TecMundo](https://www.youtube.com/playlist?list=PL7cCKVGMzqmbyaouQulXxUJLdwW4qBMpp)
    - [Mayuko](https://www.youtube.com/user/hellomayuko/videos)
    - [Computer Science - CrashCourse](https://www.youtube.com/watch?v=tpIctyqH29Q&list=PL8dPuuaLjXtNlUrzyH5r6jN9ulIgZBpdo)
    - [Tecnologias do Futuro - The Enemy](https://www.youtube.com/watch?v=TLeTxzWbak8&list=PLTFO-hPawXIEYU16QavOFJvCFuruFq1Ps)
 - Talks
    - [Alura Cursos Online](https://www.youtube.com/user/aluracursosonline/videos)
    - [Tedx Talks](https://www.youtube.com/channel/UCsT0YIqwnpJCM-mx7-gSA4Q)
    - [iMasters](https://www.youtube.com/user/imasters)
    - [InfoQ Brasil](https://www.youtube.com/channel/UCjiSYWQhLi9a4znW2h5pCrg)
    - [Campus Party](https://www.youtube.com/channel/UCUendDl_o6qhA7GtHxH3PTA)
    - [Futuro Descentralizado](https://www.youtube.com/channel/UCwgs6fw_BSDG5MbEivaw05g/videos)
    - [Locaweb](https://www.youtube.com/channel/UCqHIy-SOkAgNU3b-PRUL8qA)
    - [Pagar.me Talks](https://www.youtube.com/channel/UCNhSCufrcOMeFvzEM7tt9Lw)
    - [Endeavor Brasil](https://www.youtube.com/user/endeavorbrasil/videos)
 - Science
    - [Nerdologia](https://www.youtube.com/channel/UClu474HMt895mVxZdlIHXEA)
    - [SpaceToday](https://www.youtube.com/channel/UC_Fk7hHbl7vv_7K8tYqJd5A)
    - [PeixeBabel](https://www.youtube.com/channel/UCqB90BBr6eNRaJl-kl30Xxw)
    - [TED-Ed](https://www.youtube.com/channel/UCsooa4yRKGN_zEE8iknghZA)
    - [Canal do Pirula](https://www.youtube.com/user/Pirulla25)
    - [Kurzgesagt – In a Nutshell](https://www.youtube.com/user/Kurzgesagt)
    - [Vsauce](https://www.youtube.com/user/Vsauce)
    - [PBS Space Time ](https://www.youtube.com/channel/UC7_gcs09iThXybpVgjHZ_7g/about)
    - [Ponto em Comum](https://www.youtube.com/channel/UCGo3vjM2Ll3XujL-zYT5SMg)
    - [Alimente o Cérebro](https://www.youtube.com/channel/UC3fBS89aQ7mt5G1TodU4HNg)
    - [Singularidade](https://www.youtube.com/channel/UCA6-1g_4e3iuT1qeXe6xNuA/videos)
    - [Minutos Psíquicos](https://www.youtube.com/channel/UCFiEI1kDHlO9UQtxx0wj-XA)
    - [CrashCourse Kids](https://www.youtube.com/user/crashcoursekids/videos)
    - [BigThink](https://www.youtube.com/user/bigthink)
    - [AsapSCIENCE](https://www.youtube.com/channel/UCC552Sd-3nyi_tk2BudLUzA)
    - [Ciência Todo Dia](https://www.youtube.com/user/CienciaTodoDia)
    - [Primata Falante](https://www.youtube.com/user/mrprimatafalante)
    - [Manual do Mundo](https://www.youtube.com/user/iberethenorio) 
    - [Thoughty2](https://www.youtube.com/user/Thoughty2/featured)
    - [MathGurl](https://www.youtube.com/channel/UC5RV_s1Jh-jQI4HfexEIb2Q)
    - [A Matemaníaca por Julia Jaccoud](https://www.youtube.com/channel/UCz4Zuqtj9fokXH68gZJmCdA)
 - Self Development & Philosophy & Psychology & History & Others
    - [NeuroVox](https://www.youtube.com/user/NeuroVoxConsultoria)
    - [Moporã](https://www.youtube.com/channel/UCZYCNT6OT4_cgt-ldtwGQJw)
    - [Arata Academy](https://www.youtube.com/channel/UCEdgNBcBybRtwv836C8El4g)
    - [Jacob Petry](https://www.youtube.com/channel/UCv79O7v-AHomNC7MB7cx6BA)
    - [Augusto Ollivieri](https://www.youtube.com/channel/UCfkmlovZdEmMzTsGwatkoIw)
    - [IlustradaMente](https://www.youtube.com/channel/UCNmO5NWNLQkOr76WmHEq-DQ)
    - [PhilosTV](https://philos.tv/)
    - [Gilberto de Souza](https://www.youtube.com/channel/UCMMbl7Tt6Zy5Ho3W2bw0BfQ)
    - [16 Personalities](https://www.16personalities.com/)
    - [The History Channel Brasil](https://www.youtube.com/watch?v=6bvc8TgeGUA)
    - [Canal do Moscoso](https://www.youtube.com/channel/UChVeSyoB200ALDpnTr1TOrg/videos)
    - [Canal Nostalgia](https://www.youtube.com/user/fecastanhari)
    - [MuriloGun](https://www.youtube.com/user/murilogun/videos)
    - [Ler Antes de Morrer](https://www.youtube.com/channel/UCTubbc8ei3JfOBbicSJYPfQ)
    - [Metaforando](https://www.youtube.com/channel/UCh7TUTXojlE8vRtb-EnuDzw)
    - [Canal do Por Quê?](https://www.youtube.com/channel/UCqWMwhpW-rggQZtfNXIqkrw)
    - [Meteoro Brasil](https://www.youtube.com/channel/UCk5BcU1rOy6hepflk7_q_Pw)
    - [Canal do Cortella](https://www.youtube.com/channel/UCyTS929PXJSUiBEFSzdypgg)
    - [Luiz Felipe Pondé](https://www.youtube.com/channel/UCW9jLtlONRp7W-AK9F8M66Q)
    - [NOVA ACRÓPOLE - Escola Internacional de Filosofia](https://www.youtube.com/channel/UCAMO_xP86YB4FSHD1Mi_GpA)
    - [Prazer, Karnal](https://www.youtube.com/channel/UC4O2eKb8vI4VlMeNp90asfg)
    - [Casa do Saber](https://www.youtube.com/channel/UCtvvTFp0XANyllOdmzZr9VQ)
    - [Saber Filosófico](https://www.youtube.com/channel/UCWdXgfpEIZIGzah9_yCL-Xw)
    - [Seja Uma Pessoa Melhor](https://www.youtube.com/channel/UCbG7_Agdb99rhG9-rhY8iTg/videos)
    - [Jordan Peterson](https://www.youtube.com/user/JordanPetersonVideos)
       - REGRA 1 – Costas eretas e ombros para trás
       - REGRA 2 – Cuide de si mesmo como cuidaria de alguém sob sua responsabilidade
       - REGRA 3 – Seja amigo de pessoas que queiram o melhor para você
       - REGRA 4 – Compare a si mesmo com quem você foi ontem, não com quem outra pessoa é hoje
       - REGRA 5 – Não deixe que seus filhos façam algo que faça você deixar de gostar deles
       - REGRA 6 – Deixe sua casa em perfeita ordem antes de criticar o mundo
       - REGRA 7 – Busque o que é significativo, não o que é conveniente
       - REGRA 8 – Diga a verdade. Ou pelo menos, não minta. Seja sincero e aprenda a dizer não!
       - REGRA 9 – Presuma que a pessoa com quem está conversando possa saber algo que você não sabe
       - REGRA 10 – Seja preciso no que diz
       - REGRA 11 – Não incomode as crianças quando estão andando de skate
       - REGRA 12 – Acaricie um gato ao encontrar um na rua
    - <strong>O Jeito Harvard de Ser Feliz: 7 Princípios</strong>
       - I – O benefício da felicidade
          - “Quando eu for bem sucedido, eu vou ser feliz.” - ERRADO
          - "Se eu sou feliz fazendo o que eu faço, terei sucesso." - CERTO
       - II. O ponto de apoio e alavanca
          -  Quanto mais você acredita na própria capacidade de sucesso, maiores são as suas chances de atingir esse sucesso.
       - III. O efeito Tetris
          - Algumas pessoas estão configuradas para identificar apenas padrões negativos, enquanto outros, positivos
       - IV. Encontre oportunidades na adversidade
       - V. O círculo do zorro
          - comece muito pequeno e vá aumentando.
       - VI. A regra dos 20 segundos
          - A Regra dos 20 segundos fala pra você eliminar os “cerca de 20 min” antes do novo hábito que você quer incorporar. Tire todas as barreiras antes de começar aquela atividade para deixá-la o mais fácil possível!
       - VII. Investimento social
          - rede social de apoio é o seu maior ativo.
    - <strong>7 Princípios de Leonardo da Vinci </strong>
       - <strong>1 - Curiosità</strong>: Instigue sua curiosidade
       - <strong>2 - Dimostrazione</strong>: Aprenda com a experiência
       - <strong>3 - Sensazione</strong>: Estimule sua percepção
       - <strong>4 - Sfumato</strong>: Enfrente a sombra
       - <strong>5 - Arte/Scienza</strong>: Busque o equilíbrio
       - <strong>6 - Corporalità</strong>: Integre corpo, mente e espírito
       - <strong>7 - Conessione</strong>: Realize a comunhão
    - <strong>O Tao do Jeet Kune Do - Bruce Lee</strong>
       - 1 - OBJETIVO
          - "Um objetivo nem sempre é para ser atingido, frequentemente serve apenas como algo a ser mirado."
       - 2 - FLEXIBILIDADE
          - "Limpe a sua mente e seja como a água, sem forma. Você coloca a água num copo e se torna o copo, coloca água em uma garrafa, se torna a garrafa. A água pode fluir ou colidir. Seja água, meu amigo."
       - 3 - TEMPO
          - "Se você ama a vida, não desperdice tempo, é de tempo que a vida é feita."
       - 4 - PROPÓSITO
          - "Viver de verdade é viver para os outros."
       - 5 - ACEITAÇÃO
          - "Não pense sobre quem está certo ou errado ou quem é melhor que o outro. Não seja nem a favor nem contra."
       - 6 - FOCO
          - "Eu não temo o homem que praticou 10.000 chutes diferentes, mas aquele que praticou o mesmo chute 10.000 vezes.”
       - 7 - SIMPLICIDADE
          - "Simplicidade é a chave para algo brilhante."
       - 8 - ENCONTRE O SEU CAMINHO
          - "Absorva o que lhe é útil, descarte o que não é, e adicione algo único."
       - 9 - EGO
          - "Artes-marciais são principalmente fonte de auto-conhecimento. Um soco ou um chute não é para arrancar os males do cara a sua frente, mas para arrancá-los seu próprio ego, medo e obstáculos."
       - 10 - COMECE AGIR
          - "Saber não é o suficiente, você tem que aplicar; querer não é o bastante, você tem que fazer."
    - <strong>Sun Tzu - A Arte da Guerra</strong>
       - <strong>1 - Alguns exércitos não devem ser enfrentados</strong>
       - <strong>2 - 5 fatores são determinantes para o sucesso</strong>
          - Clima
          - Território
          - Comando
          - Doutrina militar
          - Influência moral
       - <strong>3 - Gerenciamento</strong>:  Você não vai querer ser pego desprevenido bem no meio de uma missão, por isso faça as contas e gerencie os gastos.
       - <strong>4  Estratégia</strong>: prega que o vencedor da guerra era o estado que conseguia a rendição do inimigo sem que houvesse um combate. Para tanto seu conselho é que o ataque seja feito primeiro sobre a estratégia dos concorrentes, em segundo sobre suas alianças e, em terceiro sobre seus soldados, oferecendo melhores oportunidades e condições de trabalho.
       - <strong>5 - Tática</strong>: Se for mais forte que seu concorrente, ataque, se for mais fraco, se defenda, mas jamais seja previsível.
       - <strong>6 - Conheça a si mesmo e aos seus oponentes</strong>: "If you know the enemy and know yourself, you need not fear the result of a hundred battles. If you know yourself but not the enemy, for every victory gained you will also suffer a defeat. If you know neither the enemy nor yourself, you will succumb in every battle."
       - <strong>7 - Deixe espaço para realizar manobras</strong>: sempre haverá imprevistos, por isso não se prenda a uma única medida ou estratégia
       - <strong>8 - Tenha uma estrutura sólida</strong>: mantenha uma estrutura que lhe favoreça retornar ainda mais forte e consistente
       - <strong>9 - Use um ataque indireto</strong>
       - <strong>10 - Considere algumas razões de ataques estratégicos</strong>
          - Nunca ataque quando estiver por baixo: Certifique-se de que está a uma altura segura de modo que não seja alcançado depois de conceber o ataque.
          - Nunca ataque em terreno desconhecido: Avalie e estude o território de ataque para que a luta não seja desperdiçada. Alguns territórios não valem à pena ser conquistados.
          - Proteja-se em terrenos perigosos: Observe a maneira mais segura de atacar em território perigoso, protegendo-se, esquivando-se e garantindo um plano de fuga. Se tudo der errado, que atitude deverá tomar?
       - <strong>11 - Quando não houver alternativa, arrisque</strong>: quando já não há alternativas a melhor estratégia é arriscar. Quando estamos diante de um grande perigo, fazemos o impossível para superar os desafios e prosperar.
       - <strong>12 - Considere estes nove fatores previsíveis</strong>:  dispersivo, marginal, contencioso, aberto, convergente, difícil, crítico, cercado e desesperado.
       - <strong>13 - Conte com esta categoria de espiões para triunfar sobre o oponente no mercado</strong>
          - Espiões nativos: São os próprios criadores da empresa, sócios e investidores.
          - Espiões internos: Funcionários da empresa concorrente.
          - Espiões convertidos: São os espiões do inimigo que fornecem informações.
          - Espiões descartáveis: São espiões convertidos pelo inimigo.
          - Espiões indispensáveis: São aqueles que possuem respeito com o inimigo e fornecem informações confiáveis.
    - <strong>9 Mandamentos do Livro dos 5 Anéis - Miyamoto Musashi</strong>
       - 1 – Não faça nada desonestamente, evitar todo e qualquer pensamento perverso.
       - 2 – O Caminho está no treino.
       - 3 – Familiarize-se com todas as artes.
       - 4 – Compreender os mandamentos de todas as profissões.
       - 5 – Saiba distinguir entre vantagens e desvantagens em assuntos mundanos.
       - 6 – Desenvolva julgamento intuitivo e entendimento para tudo.
       - 7 – Perceba todas as coisas que não podem ser vistas.
       - 8 – Preste atenção aos menores detalhes.
       - 9 – Não faça nada que não tenha qualquer utilidade.
       - <strong>Outros Princípios</strong>
       - 1. Aceite tudo do jeito que é.
       - 2. Não procure prazer pelo seu próprio bem.
       - 3. Não, em hipótese alguma, dependa de um sentimento parcial.
       - 4. Pense levemente em si mesmo e profundamente do mundo.
       - 5. Seja desapegado do desejo por toda a sua vida.
       - 6. Não se arrependa do que você fez.
       - 7. Nunca seja ciumento.
       - 8. Nunca deixe-se entristecer por uma separação.
       - 9. O ressentimento e a queixa não são apropriados nem para si nem para os outros.
       - 10. Não se deixe guiar pelo sentimento de luxúria ou amor.
       - 11. Em todas as coisas não tem preferências.
       - 12. Seja indiferente aonde você mora.
       - 13. Não persiga o sabor da boa comida.
       - 14. Não segure as posses que você não precisa mais.
       - 15. Não aja seguindo as crenças costumeiras.
       - 16. Não colete armas ou pratique com armas além do que é útil.
       - 17. Não tenha medo da morte.
       - 18. Não procure possuir bens ou feudos para a sua velhice.
       - 19. Respeite o Buda e os deuses sem contar com a ajuda deles.
       - 20. Você pode abandonar seu próprio corpo, mas deve preservar sua honra.
       - 21. Nunca se desvie do caminho.
    - <strong>Diferença entre Objetivo e Meta</strong>
       - O objetivo é apenas uma vaga ideia daquilo que queremos. É o seu ponto de partida rumo a algo que você gostaria de ter, ser ou viver. Ou seja, a sua motivação.
          - "você se contenta em definir o objetivo, que é o que geralmente fazemos. Mas esquece de especificar a meta."
          - <strong>Portando OBJETIVO =  A descrição do seu desejo.</strong>
       - Meta nada mais é quem um objetivo com ações bem definidas.
          - Saiba que pessoas que escrevem suas metas tem 50% mais chances de realizá-las do que aqueles que não escrevem metas.
       - Daniel Pink, autor do livro Drive, sobre motivação, identificou três fatores-chave:
          - Autonomia: Nosso desejo de viver a vida que desejamos. Nossa vontade de ter a liberdade para fazer o que preferimos.
          - Maestria: Nosso senso de urgência para ser melhor em diversos sentidos, tanto profissional como pessoal.
          - Propósito: Nossa missão de vida. A intenção de fazer uma diferença no mundo, mesmo que relativamente pequena.
       - Meta SMART
          - S = Especific
             - O que exatamente (mais detalhes possíveis) você quer conquistar?
             - Onde?
             - Você precisará da ajuda de outras pessoas? Quais pessoas?
             - Existe uma alternativa para essa meta SMART que desejo alcançar que traria o mesmo grau de satisfação?
             - Do que você não abre mão para conquistar essa meta?
             - Quais são as suas limitações para conquistar essa meta?
             - Quais são as condições obrigatórias para conquistar essa meta?
          - M = Mensurable
             - Quais são os resultados mensais esperados?
             - Quanto tempo de dedicação será necessário para alcançar a meta?
          - A = Attainable
             - Quem já esteve na Lua já não tem mais metas na Terra. - Edwin Aldrin
          - R = Relevant
             - Refletir se isso é relevante na sua vida.
          - T = Time-Related
             - Colocar datas realistas
        - Exemplo de meta SMART: Eu vou ler 24 livros de desenvolvimento pessoal nos próximos 12 meses.
        - Um dos maiores segredos para o sucesso é a disciplina, a constância e a paciência.


<br><br>

<p align="center">
  "<strong>I am always ready to learn although I do not always like being taught."</strong><br><br> - Winston Churchill
    <br>
  </p>

<br><br>

<p align="center">
  "<strong>Don't confuse education with schooling. I didn't go to Harvard, but people who work for me did."</strong><br><br> - Elon Musk
    <br>
  </p>
