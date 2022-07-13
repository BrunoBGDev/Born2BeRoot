## :exclamation:Informações importantes sobre o projeto.:exclamation:

> Para este projeto é importante ter conhecimento sobre algumas coisas específicas. Por exemplo é preciso saber a diferença entre apt-get e apititude. Ter esses conhecimentos irá ajudar você a entender melhor o objetivo do projeto. Aqui você pode encontrar essas informações!
>
> #### :white_check_mark:Para começar:
>
> * ## Qual a diferença entre apt-get e apititude?
>>      Ambos são gerenciadores de pacote muito úteis para realizar a configuração da máquina. É por meio deles que
>>      podemos fazer a instalação de ferramentas como git, vim, ssh, instalar sudo entre muitos outros recursos.
>>      
>>      Então qual a diferença?
>>      
>>      O apititude é superior em relação ao apt-get porquê ele contém muito mais funcionalidades, além de ser capaz
>>      de fazer tudo o que o apt-get faz. Enquanto o apt-get lida com toda a instalação e atualização de pacotes,
>>      atualização do sistema, limpeza de pacotes, resolução de dependências etc. 
>>      
>>      O Aptitude lida com muito mais coisas do que o apt, incluindo funcionalidades do apt-mark e apt-cache, ou seja,
>>      procurar um pacote na lista de pacotes instalados, marcar um pacote para ser instalado automáticamente ou de 
>>      forma manual, manter um pacote indisponível para atualização e assim, por diante.
>
> * ## O quê é SELinux e Apparmor? 
> >     São sistemas de segurança que oferecem ferramentas para isolar aplicações que foram comprometidas por um ataque
> >     de outras aplicações para evitar que a invasão se alastre para o resto do sistema. Existe algumas diferenças
> >     entre eles. Essas são:
> >     
> >     -> SELinux: Os conjuntos de regras do SELinux são incrivelmente complexos, mas com essa complexidade você tem 
> >     mais controle sobre como os processos são isolados. A geração dessas políticas pode ser automatizada. Um ataque
> >     contra este sistema de segurança é muito difícil de verificar de forma independente.
> >     
> >     -> AppArmor: AppArmor (e SMACK) é muito simples. Os perfis podem ser escritos à mão por humanos ou gerados
> >     aa-logprof. O AppArmor usa controle baseado em caminho, tornando o sistema mais transparente para que possa
> >     ser verificado de forma independente.”
>
> * ## O quê é UFW?
>>      UFW(Uncomplicated Firewall) é um Firewall muito utilizado em sistemas baseados em linux. Como o próprio nome
>>      sugere, ele é bem simples de ser utilizado. Usando comandos simples via sudo no terminal, é possível habilitar
>>      portas de conexão, ips, ssh's entre outros tipos de configurações. É uma ótima escolha manter o sistema seguro.
>
> * ## Quais as diferenças entre CentOS e Debian?
>>      Debian: 
>>      -> É um sistema operacional Open Source baseado em Unix que é mantido por um grupo de pessoas que fazem
>>      parte do "Debian Project". 
>>      -> Ele tem suporte para multiplas arquiteturas. 
>>      -> O ciclo de atualizações dele é a cada 2 anos, tendo assim tempo suficiente para resolver bugs.
>>      -> Ele pode ser atualizado de forma simples para outra versão estável.
>>      -> Ele possui uma interface de usuário amigável.
>>      -> Debian usa apt-get como seu gerenciador de pacotes.
>>      -> Ele possui uma vasta quantidade de pacotes em seu repositório padrão para fazer diversas coisas.
>>      
>>      CentOS: 
>>      -> É um sistema operacional Open Source que é distribuído pela Red Hat Enterprise Linux que tem uma grande
>>      comunidade. 
>>      -> Ele não vêm com suporte para multiplas arquiteturas.
>>      -> As atualizações normalmente levam algum tempo, tornando ele estável.
>>      -> É melhor instalar um novo CentOS do que atualizar uma versão antiga por ser uma tarefa dificil.
>>      -> Ele possui uma interface de usuário complicada.
>>      -> CentOS usa YUM como seu gerenciador de pacotes.
>>      -> Ele possui uma quantidade limitada de pacotes.
>      
> * ## O que é cron?
> >     O cron é uma ferramenta de linha de comando presente em sistemas baseados em Unix. Ele funciona como um job
> >     scheduler(agendador de trabalhos), que tem como objetivo executar tarefas definidas pelo usuário. Ele é capaz
> >     de criar programação de horários para executar comandos ou shell scripts. Essa ferramenta é muito útil quando
> >     se precisa fazer alguma tarefa com certa frequência(Como o script que criamos no projeto).
>
> * ## O que é SUDO?
>       Sudo é um programa para sistemas baseados em Unix que possibilita os usuários executarem programas com
>       privilégios de segurança de outro usuário. A configuração de usuários para receberam esses privilégios
>       deve ser feita em (/etc/sudoers), e outras configurações sudo.
