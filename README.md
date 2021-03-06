### Born2BeRoot #42Rio

# :ledger:Info:
> :clipboard:O objetivo deste projeto é criar um servidor por meio da ferramenta chamada <a href="https://www.virtualbox.org/">Virtual Box</a>. O Virtual Box serve para criar <a href="https://www.penso.com.br/o-que-e-maquina-virtual-e-para-que-serve/?utm_source=google&utm_medium=cpc&utm_campaign=Performance-Suporte&utm_term=_&pht=10091517607840771&adwgroup=&gclid=EAIaIQobChMI4MOtr7Xf-AIVPRXUAR0aEwTGEAAYAiAAEgKRpPD_BwE">Máquinas Virtuais.</a> Para entender e executar este projeto é preciso entender como funciona a ferramenta Virtual Box e o que é uma máquina virtual.
>
> :white_check_mark:Para este projeto é aprender sobre alguns deteerminados temas importantes para execução, estes são:
> - :computer:<a href="https://www.penso.com.br/o-que-e-maquina-virtual-e-para-que-serve/?utm_source=google&utm_medium=cpc&utm_campaign=Performance-Suporte&utm_term=_&pht=10091517607840771&adwgroup=&gclid=EAIaIQobChMI4MOtr7Xf-AIVPRXUAR0aEwTGEAAYAiAAEgKRpPD_BwE">O quê é uma máquina virtual.</a>
> - :floppy_disk:<a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Passo%20a%20passo.md">Entender o quê são LVMs.</a>
> - :file_folder:<a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Infos.md">Quais as diferenças entre apt e aptitude.</a>
> - :closed_lock_with_key:<a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Passo%20a%20passo.md">Como configurar e entender como funciona o protocolo SSH.</a>
> - :bookmark:<a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Passo%20a%20passo.md">Criar admin e usuários no servidor.</a>
> - :key:<a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Passo%20a%20passo.md">Instalar e configurar *sudo* na máquina virtual, seguindo esta configuração:</a>
>   - A autenticação via sudo deve ser limitada a 3 tentativas de senha incorreta.
>   - Uma mensagem de erro deve ser exibida em caso de senha incorreta enquanto está usando sudo.
>   - Cada ação via sudo deve ser arquivada em um arquivo de log no local: /var/log/sudo/ .
>   - O modo TTY deve ser habilitado por questões de segurança.
>   - Por questões de segurança também, os caminhos que podem ser usados pelo sudo devem ser limitados a: /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin
>
>
> - :no_entry_sign:Criar uma política de senhas rígida. Sendo:
>   - A senha deve expirar em 30 dias.
>   - Modificações de senhas permitidas apenas depois de 2 dias após a última alteração.
>   - A senha deve ter pelo menos 10 caracrteres e precisa ter pelo menos 1 letra maiuscula e números. Também não pode ter mais de três caractéres iguais em sequencia.
>   - A senha não pode conter o nome do usuário.
>   - A senha não pode conter 7 caractéres que fizeram parte da senha aterior.
> 
>
> - :pager:É preciso criar um script chamado *monitoring.sh*, que deve ser desenvolvido em bash. Toda vez que o servidor iniciar, este script irá mostrar algumas informarções (listadas abaixo) em todos os terminais a cada 10 minutos. Nenhum erro pode ser visível.
>
> - :memo:O script deve mostrar as seguintes informações:
>   - A arquitetura do seu sistema operacional e sua versão do kernel.
>   - O número de processadores físicos. O número de processadores virtuais.
>   - A RAM disponível atual em seu servidor e sua taxa de utilização como porcentagem.
>   - A memória atual disponível em seu servidor e sua taxa de utilização como porcentagem.
>   - A taxa de utilização atual de seus processadores como uma porcentagem.
>   - A data e hora da última reinicialização.
>   - Se o LVM está ativo ou não.
>   - O número de conexões ativas.
>   - O número de usuários usando o servidor.
>   - O endereço IPv4 do seu servidor e seu endereço MAC (Media Access Control).
>   - O número de comandos executados com o programa sudo.
____

### Sabendo dessas informarções, agora podemos dar inicio ao <a href="https://github.com/BrunoBGDev/Born2BeRoot/blob/main/Passo%20a%20passo.md">passo a passo</a> para realizar o projeto!
