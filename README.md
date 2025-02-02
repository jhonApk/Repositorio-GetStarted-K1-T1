
# _Git - Sistema de Controle de Versão_

O Git é um sistema de controle de versão distribuído amplamente utilizado por desenvolvedores de software. Ele permite que você acompanhe as alterações no código, colabore com outros desenvolvedores e gerencie o histórico do seu projeto de maneira eficiente.
.
### 1. **Instalando o Git**
Antes de começar a usar o Git, é necessário instalá-lo. Você pode fazer isso seguindo as instruções no [site oficial do Git](https://git-scm.com/).

## Configuração Inicial

Após a instalação, é recomendável configurar seu nome de usuário e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

## Comandos Básicos

### 1. Inicializando um Repositório Git
Para começar a usar o Git em um diretório, inicialize um repositório:
```bash
git init
```

### 2. Verificando o Status
Veja o status dos arquivos no repositório (arquivos modificados, não versionados, etc.):
```bash
git status
```

### 3. Adicionando Arquivos
Adicione um arquivo específico ao estágio de preparação para commit:
```bash
git add nome-do-arquivo
```

Ou adicione todos os arquivos:
```bash
git add .
```

### 4. Fazendo um Commit
Depois de adicionar os arquivos, faça o commit das mudanças com uma mensagem explicativa:
```bash
git commit -m "Mensagem do commit"
```

### 5. Visualizando o Histórico
Para ver o histórico de commits:
```bash
git log
```

### 6. Criando um Branch
Crie um novo branch para trabalhar em uma nova funcionalidade:
```bash
git branch nome-do-branch
```

### 7. Mudando de Branch
Troque para um branch existente:
```bash
git checkout nome-do-branch
```

Ou crie e mude para um novo branch em um único comando:
```bash
git checkout -b nome-do-branch
```

### 8. Mesclando Branches
Para mesclar alterações de outro branch no branch atual:
```bash
git merge nome-do-branch
```

### 9. Enviando Alterações para o Repositório Remoto
Após os commits, envie suas alterações para um repositório remoto (como GitHub, GitLab, Bitbucket):
```bash
git push origin nome-do-branch
```

### 10. Obtendo Alterações do Repositório Remoto
Para baixar as últimas alterações do repositório remoto:
```bash
git pull
```

### 11. Clonando um Repositório
Para clonar um repositório remoto em sua máquina local:
```bash
git clone https://url-do-repositorio.git
```

## Fluxo de Trabalho Básico

1. **Clone** o repositório remoto (se necessário).
2. Crie um **branch** para sua funcionalidade.
3. **Faça alterações** nos arquivos.
4. **Adicione** e **faça commit** das alterações.
5. **Puxe** as alterações do repositório remoto (caso outras pessoas tenham feito modificações).
6. **Envie** suas alterações para o repositório remoto.
7. **Mescle** suas alterações com o branch principal (geralmente `main`).

## Recursos Adicionais

- [Documentação oficial do Git](https://git-scm.com/doc)
- [Pro Git Book (em português)](https://git-scm.com/book/pt-br/)

