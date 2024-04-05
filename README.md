# Treinamento Git e GitHub

Repositório para armazenar comandos do Git e GitHub do curso de Versionamento de Código com Git e GitHub.

[Digital Innovation One](https://web.dio.me/)

## 📚 Documentação
- [Documentação Git](https://git-scm.com/doc) 
- [Documentação GitHub](https://docs.github.com/pt)

## 💻 Comandos do Git

### Criar ou Clonar Repositório
| Comandos | Descrição |
|----------|-----------|
|`git clone (URL)`| Clonar um repositório Main ou Master|
|`git clone (URL) --branch (nome da branch) --single-branch`|Clonar apenas a **branch** de um repositório|
|`git init`|Transformar o projeto em um repositório Git|
|`git remote add origin (URL)`|Conectar um repositório local com o remoto|
|`git branch -M main`|Transformar o repositório **master** em **main**|
|`git push -u origin main`|Enviar alterações do repositório local para o remoto e setar o repositório local como upstream|

### Salvar e Desfazer Alterações
| Comandos | Descrição |
|----------|-----------|
|`git add (Nome do arquivo)`|Adicionar as alterações de um arquivo|
|`git add .`|Adicionar as alterações de todos os arquivos|
|`git commit -m"(Nome do commit)"`|Salvar as Alterações|
|`git push origin main`|Salvar as alterações no repositório remoto|
|`git restore (Nome do arquivo)`|Voltar ultima alteração salva do arquivo|

### Trabalhar com Branches
| Comandos | Descrição |
|----------|-----------|
|`git checkout -b (Nome da branch)`|Criar e alterar para uma nova branch|
|`git checkout (Nome da branch)`|Alterar a branch sendo utilizada|
|`git branch`|Verificar branches existente|
|`git branch -v`|Verificar ultimos commit de cada branch|
|`git merge (Nome da branch)`|Mesclar a branch selecionada para a branch **main**|
|`git branch -d (Nome da branch)`|Excluir a branch|

> [!NOTE]
> Em caso de conflito de merge, utilizar `git pull` / `git add .` / `git push origin main` 

### Extras
| Comandos | Descrição |
|----------|-----------|
|`git status`|Verificar se o projeto possui alterações|
|`git log`|Verificar o histórico de commit do projeto|