# Preparação de Ambiente
### Vamos preparar o ambiente para desnvolvimento de aplicações
 
#### Neste ambiente iremos instalar e configurar os seguintes recursos:
 - Marquina Virtual(Virtualbox)
 -Distribuição Linux (Ubuntu serve)
 Nasm
 - Compilador da limguagem C
 - configurar o ip e a porta de comunicação entre a máquina real e a virtual
 - Configurar o acesso via SSH entre o VScode e o ServidorLinux
 -Instalar as extensões: Material Icon, Nasm, SSH e Linguagem C/C++


### Máquina Virtual (Virtualbox)

!["Logo VirtualBox"](Virtualbox.svg)



Máquina Virtual é uma ferramenta que permite a criação de novos "computadores" e a Instalação de sistemas operacinais, para estudos ou trabalho.

Para o nosso estudo iremos usar o Virtualbox, da Oracle.
Para instalar, basta fazer download no link a seguir:
<a href="https://www.virtualbox.org/wiki/Downloads" target= "_blank">Virtualbox</a>

##### Criando a maquina Virtual para o nosso estudo

- Configuração:
  > - Nome da Máquina: Servidor
  > - Memória 4GB: (4096)
  > - Processador: (2)
  > - Disco: 100GB
  > - IP e Porta do Host: 127.0.0.1 e 22
  > - IP e Porta do Convidado: 10.0.2.15 e 22


  - Tela Inicial de configuração

  <img src=telaconfigvb1.png width=500 height=250>

  
  
  - Tela Inicial de configuração do Hardware

  <img src=telaconfigvb2.png width=500 height=250>



  - Tela Inicial de configuração do Disco

  <img src=telaconfigvb3.png width=500 height=250>

  
  - Tela Inicial de configuração do Disco

  <img src=telaconfigvb4.png width=500 height=250>


  - Tela Inicial de configuração do Disco

  <img src=telaconfigvb5.png width=500 height=250>

  
  - Tela Inicial de configuração do Disco

  
<img src=telaconfigvb6.png width=500 height=250>
  
  #### Distribuição Ubuntu Server
  Para o nosso estudo iremos utilizar uma distribuição Linux para servidores chamada Ubuntu.
  acompanhe o processo de Intalação:

  Link Do Download do Ubuntu:
  <a href=" https://ubuntu.com/download/server"target= "_blank"> Ubuntu Server </a>

   <img src=ubuntu.png width=500 height=250>


   - Acompanhe a Instalação

   - Tela de Inicio de instalação
<img src=tela1.png width=500 height=250>
   
   - Tela de Inicio de Idioma

   <img src=tela2.png width=500 height=250>
   - Tela de Inicio de Teclado

   <img src=tela3.png width=500 height=250>
   - Tela de tipo de Instalação

   <img src=tela4.png width=500 height=250>
   - Tela de Configuração de rede

   <img src=tela5.png width=500 height=250>
   - Tela Configuração do proxy

   <img src=tela6.png width=500 height=250>
   - Tela pacotes de atualização

   <img src=tela7.png width=500 height=250>
   - Tela Configuração do disco

   <img src=tela8.png width=500 height=250>
   
   - Tela Configuração do usuario
<img src=tela9.png width=500 height=250>
   
   - Tela Configuração do SSH 

   <img src=tela10.png width=500 height=250>
   - Tela do fim da instalação
<img src=tela11.png width=500 height=250>
   
   
   
   #### Atualização do sistema

   Para a correta instalação do Ubuntu que acabamos de instalar, será necessário realizar a atualização so sistema.

   Execute o comando a baixo:

   ```
   sudo apt update -y && sudo apt upgrade -y
   ```

  reínicie o seu servidor  usando o comando abaixo:
  
   ```
   reboot
   ```
   
   #### Instalação do compilador NASM

   O compilador do Nasm é uma ferramento que nos permite programar em Assmbly. Assim é possivel criar programas que manipulam dados que estão nos registradores  do processador.

   para instalar o NASM NO Ubuntu, usamos o comando:

   ```
   sudo apt install nasm -y
   ```


   #### Instalação do compilador de Linguagem C 

   Em Linux, o compilador de linguagem C é o GCC. Ele é uma ferramenta importante para do desenvolvimento de programas em C.

   Para instalar use o Comando:

   ```
   sudo apt install gcc -y
   ```

   #### Conexão Servidor e VSCode via SSH

   Precisamos instalar uma extensão no VSCode para acessar o nosso servidor de forma remota.

!["Extensao SSH"](extensaossh.png)


Configuração do acesso remoto.

!["Configuração](configuraextensao.png)





  









