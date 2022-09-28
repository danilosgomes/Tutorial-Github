### INTRODUÇÃO

  A princípio, o que é o Github? De modo simplificado, trata-se de uma plataforma onde você pode armazenar seus códigos(via commit), servindo de repositório. Quando criado e commitado os arquivos, você pode acessar de qualquer lugar, e pode ser acessado por qualquer pessoa. Muito bom para trabalhar em equipe.

  ##

### COMO COMMITAR

  Será necessário a utilização do Git, um outro software que vinculado com o Github funcionam de maneira excepcional.

  - A princípio, iremos abrir a pasta desejada clicando com o botão direito e abrindo em Git Bach.

  - Segundamente, vamos criar um repositório da nossa pasta no Git, com o comando 'git init'
    Comando 'git init' -> É incializado um repositório git vazio;

  - Vamos mandar o arquivo para a área de Standing(em espera), com o camando 'git add <nome do arquivo>'
    Comando 'git add <nome do arquivo>' -> É adicionado um arquivo em espera para ser comitado;
    Comando 'git add .' -> É adicionado todos os arquivos que estão na pasta em espera para ser comitado;

  - Utilizamos o comando 'git status' para verificar os arquivos em espera.
    Comando 'git status' -> É mostrado quais arquivos estão prontos para serem comitados;

  - Agora vamos fazer o committ utilizando o comando 'git commit -m <nome do commit>'
    Comando 'git commit -m <nome do commit>' -> É commitado os arquivos que estavam em Standing;
  
  - Podemos alterar o nome da nossa Branch (Pasta de repositório, pode-se criar várias para realizar mudanças sem afetar a principal). O nome padrão atual é "master", porém o Git está migrando para a alteração "main". Para alterar, usamos o comando 'git branch -M "main"'.
    Comanddo 'git branch -M <nome desejado>' -> Altera o nome da Branch que você está;

  - Agora partindo para o Github, vamos criar um nome repositório com as configurações desejadas.

  - Após criado copiamos o link do reposítorio.

  - Abrimos novamente o Git em Git Bach e coloaremos o comando 'git remote add origin <link do repositório>' (usamos o 'Ctrl+Shift+INS' para colar).
    Comando 'git remote add origin <link do repositório>' -> Faz uma linkagem do seu repositório git com o do github/Nesta etapa pode ocorrer de nao conseguir linkar por conta de não estar logado, com isso, basta logar com email e user.

  - Por fim, vamos fazer de fato o commit com o comando 'git push -u origin main' (main - apenas se você tiver mudado o nome da sua branch).
    Comando 'gut push -u origin main' -> Empurramos os arquivos que estão no repositório local para o remoto que criamos.
  
  - Irá abrir uma aba para vincular, com login, o git e github.

  ##

### ALTERANDO ARQUIVOS

  - Abrindo o Git Bach, vamos serguir os primerios 4 passos do "COMO COMMITAR".

  - Segundamente damos um 'git add -m <nome do commit>'

  - Após, utilizamos o comando 'gut push origin main', sem o '-u' pois ja foi criada a comunicação.
