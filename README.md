# Sistemas-Operacionais

 18/09 - apresentacao
 
 25/09 - ap1 - trabalho 1 ponto / prova 9 pontos 

 Trabalho - instalar a distribuição linux arch na maquina virtual - apresentar a instalação no note do ibmec- entregar relatorio tecnico descrevendo a instalação.
 OBS:
 
 *Bibliografia
 
 *Nao usar figura
 
 *Comandos apenas importantes
 
 *Nao usar itens
 
 *Como se fosse uma redacao
 
 13/11 - AC - Apresentação

 27/11 - ap2

 Aula 1 - 
 
 *Software que tem a função de funcionar como interface entre o usuario e o computador
 
 *tem como objetivo facilitar o gerenciamento dos recursos do hardware

 * a diferença entre o sistema operacional e os outros aplicativos e que ele é assincrono

 * funções do sistema operacional - controlar interrupções , escalomnamento, gerenciar processos e theridos, gerenciar memória, gerenciar sistemas de arquivos, auditoria e segurança, conexão de redes
 
 Aula 2 - Tipos de Sop

 *Sistemas monotarefas - gerenciam uma tarefa de cada / simples / antigo / menos probabilidade de erro

 *Sistemas multitarefas - gerenciam varias tarefas - São divididos em Batch(chamados de jobs, eram submetidos para execução através de cartões perfurados e armazenados em disco ou fita, onde aguardavam para serem processados.), Tempo compartilhados(fatia de tempo para cada tarefa), Tempo Real (prioridade)

 *Sistemas multiprocessados(varias cpu)- gerenciam varios processadores se divide em 
 
 Fortemente acoplado(cpu e memoria compartilham mesmo barramento, 1 computador):

 -SMP: Multiprocessamento simétrico / as cpus possuem a mesma "distância" de memória / cada cpu executa 1 tarefa diferente

 -NUMA: Acesso a memoria nao uniforme / as cpus possuem parte da memoria acessados preferencialmente
 
 Fracamente acoplado(cpu e memoria sao independentes "multicomputadores" , conexao é através de rede 

 SOR: Sistema operacional de rede

 Cluster: Servidores acessam o "HD", Vantagens: Balanceamento de carga, tolerância a falhas 

 Sistema Distribuído: cada participante faz parte do "trabalho"

 Classficados quanto a quantidade de usuários 

 *Monousuario - 

 *Multiusuario - 

 Aula 3 - comandos linux:

 todos os cd - pwd - whoami - date - rmdir - mkdir - ls  - touch - rm - file - mv - stat 

 rm - apaga arquivo

 rmdir - apaga diretorio

 IPC mover / renomear = mv

 cd ~ - vai para o diretorio de trabalho do usuário

 diferença de exit e logout

 caminho absoluto - inicia na raiz
 
 /root - /home/virtual

caminho relativo - nao começa na raiz:

../ - vai para o diretorio pai 
./ - acessa o mesmo diretorio

criar arquivo com ponto oculta os arquivos ex .aula
para ver ls -a

Tipos de arquivos 
-  - regular
-  D diretorio
-  L atalho
- c/b dispositivos caracteres ou blocos

  Aula 4 -

  inode- numéro que identifica o arquivo

  stat - verifica o conteúdo do inode

  ln - cria atalho

  ls *arq - apenas aqueles q tem conteúdo antes do arq
  ls *arq* - arquivos com conteúdo antes e depois

   rm* - remove todos arquivos no diretorio

  IPC ls * - é usado para representar qualquer caracter inclusive nenhum

  ls arquivo? - apenas 1 caracter após a palavra arquivo

  ls arquivo [34] ou [3,4]

  [] - representa q elemento único no grupo

  ls *[1-3]

  [ - ] esse traço é até, no caso de cima 1 até 3


