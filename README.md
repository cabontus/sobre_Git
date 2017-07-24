# Teste de comandos do Git
### Criar diretório
<p>Comando:</p>
<p>pwd (identifica a pasta em que estou alocada) </p>
<p>cd (volta uma pasta no diretório)</p>
<p>mkdir nome_pasta (cria uma pasta através do terminal)</p>
<p>cd nome_pasta (mostra a pasta atual)</p>
> É possível completar o nome da pasta ou arquivo automaticamente: digite uma parte do nome e tecle "tab"

### Listar arquivos e pastas
<p>ls</p>
<p>ls -1 (lista os arquivos dentro da pasta, na vertical)</p>
<p>ls -1a(lista os arquivos dentro da pasta, inclusive os *ocultos*)</p>

### Criar arquivos
<p>touch file.txt (cria um arquivo vazio)</p>
<p>start file.txt (abre o arquivo vazio)</p>
> use "start file.txt" para windows e "open file.txt" para MAC e Linux

### Clear
<p>clear (limpa a tela e mostra apenas o que preciso ver, mas não apaga do histórico)</p>


# Git
### Clonar arquivo do Github
<p>git clone https://github.com/seuusuario/nomedoarquivo</p>

### Primeiros comandos antes de qualquer modificação no arquivo
<p> git status (mostra o status atual do projeto)</p>
<p> git pull ("puxa" as modificações para o meu repositório) </p>

### Adicionar modificações na Staging Area
<p> git add . </p>

### Adicionar modificações da Staging Area para meu Git Local com descrição
<p> git commit -m "sua descrição aqui" </p>

### Adicionar modificações do meu Git Local para a Origem
<p> git push </p>

### Listar as modificações
<p> git diff (modificações "unstaged", ou seja, não add ainda) <p>

### Detalhar os commits
<p>git log </p>
>No caso de ficar preso dentro do git log (em modo visualização), basta clicar "q"> 

### Excluir alterações incorretas ou desnecessárias
<p>git checkout (exclusão irreversível; apaga definitivamente todas as alterações realizadas)</p>
<p>git reset (exclusão reversível)</p>

### Resumão
<p>git status (mostra o status atual do projeto)</p>
<p>git pull (puxa as modificações feitas por terceiros para o meu repositório)</p>
<p>git add . (adiciona as modificações do meu diretório para a staging area, possivel commit)</p>
<p>git commit -m "descrição"(adiciona as modificações para meu git local)</p>
<p>git push (adiciona as modificações para a origem, para o repositório remoto)</p>
<p>git pull ("puxa" as modificações para meu diretório)</p>

### Dúvida com algum comando?
<p>https://explainshell.com/explain?cmd=%7E</p>
<p>https://git-scm.com/docs</p>




