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

 - Most Recommended Book
    - [Algoritmos Teoria e Prática - Thomas H. Cormen](https://www.amazon.com.br/Algoritmos-Teoria-Pr%C3%A1tica-Thomas-Cormen/dp/8535236996)
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
        x = x - 1
      }
      ```
      - Example: classic merge sort -> divide-to-conquer
   - Quadratic time O(n²) :skull:
      - Nice To Avoid
      - The running time of an algorithm is directly proportional to the square of the size of the input.
      - Example: sum of matrizes
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

 - Sites
    - [Baboo](https://www.baboo.com.br/)
    - [Baboo Cursos](https://www.baboocursos.com.br/)
 - Tools
    - [Cmder](http://cmder.net/)

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
 - Software
    - [ERP - SigeLite](https://www.sigelite.com.br/)
    - [Audio - Audacity](https://www.audacityteam.org/)

## Online Courses

- [Udemy - Courses I'm enrolled](https://www.udemy.com/user/alex-galhardo-vieira/)
- [Coursera - Learning How to Learn: Powerful Mental Tools to Help You Master Tough Subjects](https://www.coursera.org/learn/learning-how-to-learn)

## Blogs

- [Medium - A LOT](https://medium.com/)
- [Quora - A LOT](https://quora.com/)
- [Akita on Rails - A LOT](http://www.akitaonrails.com/)
- [Reddit - A LOT](https://www.reddit.com)
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

 - [Teach Yourself Programming in Ten Years - Peter Norvig](http://norvig.com/21-days.html)
 - [Getting Real - the smarter, faster, easy way to build a sucesfull web application - BaseCamp](https://basecamp.com/books/getting-real)
 - [Sad Reality About Today's Modern World](https://www.youtube.com/watch?v=D2vV4SS3pWk)
 - [O que é propósito de vida - Mopora](https://mopora.com/artigos/o-que-e-proposito-de-vida/)
 - [The Invented History of 'The Factory Model of Education'](http://hackeducation.com/2015/04/25/factory-model)
 - [The Humble Programmer by Edsger W. Dijkstra](https://www.cs.utexas.edu/~EWD/transcriptions/EWD03xx/EWD340.html)
 - [Educação Clássica e Homeschooling](https://www.youtube.com/watch?v=LjJlus8oC9M)
 - [Principles for Success - Ray Dalio](https://www.principles.com/principles-for-success/)
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
 - [Write Code Every Day - John Resig](https://johnresig.com/blog/write-code-every-day/)
 - [Why Good Programmers Are Lazy and Dumb](http://blogoscoped.com/archive/2005-08-24-n14.html)
 - [The Feynman Technique: The Best Way to Learn Anything - Easy to Understand | Hard To Master](https://fs.blog/2012/04/learn-anything-faster-with-the-feynman-technique/)
 - [WaitButWhy - The Cook and the Chef: Musk’s Secret Sauce - Easy to Understand | Hard to Master](https://waitbutwhy.com/2015/11/the-cook-and-the-chef-musks-secret-sauce.html)
 - [Rob Pike's 5 Rules of Programming](http://users.ece.utexas.edu/~adnan/pike.html)
 - [The Ten Commandments of Egoless Programming](https://blog.codinghorror.com/the-ten-commandments-of-egoless-programming/)
 - [What makes a good programmer?](http://www.techfounder.net/2009/07/22/what-makes-a-good-programmer/?subscribe=error#509)
 - [Self-Education: Teach Yourself Anything with the Sandbox Method](https://www.nateliason.com/blog/self-education)

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

## YouTube #StopWatchingTV

 - Technology
    - [Curso em Video](https://www.youtube.com/user/cursosemvideo)
    - [Fábrica de Noobs](https://www.youtube.com/channel/UCGObNjkNjo1OUPLlm8BTb3A)
    - [COD3R CURSOS](https://www.youtube.com/channel/UCcMcmtNSSQECjKsJA1XH5MQ/featured)
    - [CodigoFonte TV](https://www.youtube.com/user/codigofontetv)
    - [BrasilJS](https://www.youtube.com/user/BrazilJS)
    - [EstudoNauta](https://www.youtube.com/channel/UCJcWQ9MgPlHIFMx8uDWEYNg)
    - [FreeCodeCamp](https://www.youtube.com/channel/UC8butISFwT-Wl7EV0hUK0BQ)
    - [Papo Binário](https://www.youtube.com/channel/UCuQ8zW9VmVyml7KytSqJDzg)
    - [Baboo](https://www.youtube.com/user/baboo/videos)
    - [CodellabCode](https://www.youtube.com/channel/UCVheRLgrk7bOAByaQ0IVolg)
    - [CanalTech](https://www.youtube.com/user/canaltechbr)
    - [William Oliveira](https://www.youtube.com/channel/UCWrqsnPLl6aRX0ECUmPaZEw)
    - [UNIVESPTV](https://www.youtube.com/user/univesptv/playlists)
    - [Engenharia Reversa](https://www.youtube.com/channel/UCagV1LuB6C52fFtZwVywZYg)
    - [DevNaEstrada](https://www.youtube.com/channel/UCtIygB7LtILSFWR0kxtZC-A/videos)
    - [RocketSeat](https://www.youtube.com/channel/UCSfwM5u0Kce6Cce8_S72olg/videos)
    - [Bóson Treinamentos](https://www.youtube.com/user/bosontreinamentos)
    - [ProgramadorBR](https://www.youtube.com/channel/UCrdgeUeCll2QKmqmihIgKBQ)
    - [Laboratório da Júlia](https://www.youtube.com/channel/UChfu9xWITOvsXYLKm7hieSQ)
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
    - [Fabio Akita](https://www.youtube.com/channel/UCib793mnUOhWymCh2VJKplQ)
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
    - O Jeito Harvard de Ser Feliz: 7 Princípios
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



<br><br>

<p align="center">
  "<strong>I am always ready to learn although I do not always like being taught."</strong><br><br> - Winston Churchill
    <br>
  </p>
