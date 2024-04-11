# Treinamento Git e GitHub

Repositório para armazenar comandos do Git e GitHub do curso de Versionamento de Código com Git e GitHub.

[Digital Innovation One](https://web.dio.me/)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc) 
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Comandos do Git

### Configurar o Git
| Comandos | Descrição |
|----------|-----------|
|`git config --global user.name "(nome de usuario git)"`|Configurar o usuário Git|
|`git config --global user.email "(email do usuario git)"`|Configurar o email do Git|
|`git config init.defaultBranch`|Verifical a branch padrão|
|`git config --global init.defaultBranch main`|Mudar a branch padrão para **main**|
|`git config --global --list`|Verificar as informações de Configuração|
|`git config --global --unset user.name`|Remover o nome de usuário Git|
|`git config --global --unset user.email`|Remover o email do Git|

### Criar ou Clonar Repositório
| Comandos | Descrição |
|----------|-----------|
|`git clone (URL)`| Clonar um repositório Main ou Master|
|`git clone (URL) --branch (branch) --single-branch`|Clonar apenas a **branch** de um repositório|
|`git init`|Transformar o projeto em um repositório Git|
|`git remote add origin (URL)`|Conectar um repositório local com o remoto|
|`git branch -M main`|Transformar o repositório **master** em **main**|
|`git push -u origin main`|Enviar alterações do repositório local para o remoto e setar o repositório local como upstream|

### Salvar e Desfazer Alterações
| Comandos | Descrição |
|----------|-----------|
|`git add (arquivo)`|Adicionar as alterações de um arquivo|
|`git add .`|Adicionar as alterações de todos os arquivos|
|`git commit -m"(commit)"`|Salvar as Alterações|
|`git push origin main`|Salvar as alterações no repositório remoto|
|`git restore (arquivo)`|Voltar ultima alteração salva do arquivo|

### Trabalhar com Branches
| Comandos | Descrição |
|----------|-----------|
|`git checkout -b (branch)`|Criar e alterar para uma nova branch|
|`git checkout (branch)`|Alterar a branch sendo utilizada|
|`git branch`|Verificar branches existente|
|`git branch -v`|Verificar ultimos commit de cada branch|
|`git merge (branch)`|Mesclar a branch selecionada para a branch **main**|
|`git branch -d (branch)`|Excluir a branch|

> [!NOTE]
> Em caso de conflito de merge, utilizar `git pull` / `git add .` / `git push origin main` 

### Extras
| Comandos | Descrição |
|----------|-----------|
|`git status`|Verificar se o projeto possui alterações|
|`git log`|Verificar o histórico de commit do projeto|

## 👨‍💻 Comandos CMD
| Comandos | Descrição |
|----------|-----------|
|`mkdir (pasta)`|Criar um pasta|
|`cd (local)`|Alterar local do powershell ou gitBash|
|`ls`|Lista itens da pasta|
|`cat .git`|Verificar conteudo do arquivo .git|
|`clear`|Limpar os comandos no powershell ou gitBash|
|`touch README.md`|Criar um arquivo .md|
|`rm -rf .git`|Deletar arquivo .git|
|`echo (local) > .gitignore`|Inserir pasta no .gitignore (para arquivos que não devam ser salvos)|
|`touch (local).gitkeep`|Inserir .gitkeep (para arquivos que devem ser salvos)
