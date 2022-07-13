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
