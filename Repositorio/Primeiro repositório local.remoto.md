##  Git e GitHub:computer:



### Criando Repositório Local, Comandos Básicos :newspaper:

- **ls**  - Lista todas as pastas na unidade.

- **ls -a** - pastas ocultas.

- **ctrl l** - limpa o terminal.

- **git status** - mostra o status  sobre o arquivo (unmodified, modifiel...).

- **mv** - comando para mover.

- **git init** - da início ao repositório.

- **git config --global** - comando para inserir informações sobre quem está criando o arquivo.

  _ex_: 

  git config --global user.name "NOME"

  git config --global user.email "EMAIL"

- **git config --global --unset **- comando para corrigir/alterar informações de quem criou ou editou o arquivo.

  ex_:

  git config --global --unset  user.email

- **git config --list** - mostra todas as configurações que estão no git.

  

### Fazendo Commit​ ​ :file_folder:

- **git add** * - adiciona todas as modificações feita no diretório de trabalho para staged área.

- **git commit -m "mensagem sobre o commit"** - aqui foi criado o commit no repositório local.

  

### Trabalhando com Repositório Remoto (GitHub) :globe_with_meridians:

- **git remote add origin (inserir o link da pagina gerado no github)**  -

  **OBS**: o nome **origin** é um nome usado por convenção para servir como atalho do link gerado pelo github.

- **git remote -v** - lista de repositório remoto cadastrado.

- **git push origin master** -  empurra o arquivo para o repositório remoto.

- **git pull origin master** - puxa o arquivo do repositório remoto quando o mesmo possui um versão diferente do repositório local.





#### Conceito básico do funcionamento:

- **Untracked** - o git ainda não sabe do arquivo.

- **Tracked** - o git já sabe que o arquivo existe.

- **Unmodified** - o arquivo ainda não foi modificado.

- **Modified** - o arquivo foi modificado.

- **Staged** - o arquivo está sendo preparado para um commit.

- **Commit** - o arquivo foi finalizado. 

  

#### Comando básicos para Markdown.

- (# )  - aumenta a fonte do texto.
- (** Negrito **) 
- (_  Itálico _) 
- (: nome do emoji) 
- (-)











