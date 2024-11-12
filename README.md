# Repositório git-test

## Objetivos e Resultados

Neste exercício, aprendi a:
- Configurar um repositório on-line como repositório remoto para o repositório Git local.
- Enviar (fazer push) dos commits para o repositório on-line.
- Clonar um repositório Git on-line para o computador.

## Passos Realizados no Exercício

### 1. Configuração do Repositório Git On-line no GitHub

1. *Criar uma conta no GitHub*:
   - Registrei uma conta no [GitHub](https://github.com) para poder armazenar o repositório on-line.

2. *Criar o Repositório no GitHub*:
   - No GitHub, criei um repositório chamado git-test.
   - Anotei a URL do repositório: https://github.com/lucasandare490/git-test.git.

### 2. Configuração do Repositório Local

1. *Criar a Pasta do Repositório Local*:
   - No VS Code, criei uma pasta chamada git-historico para usar como repositório local.

2. *Inicializar o Repositório Git Local*:
   - No terminal do VS Code, naveguei até a pasta git-historico e executei:
     bash
     git init
     
   - Esse comando inicializou o repositório Git local.

3. *Criar o Arquivo de Exemplo*:
   - Criei o arquivo experimento.txt com um conteúdo inicial para praticar comandos Git.

4. *Adicionar o Arquivo e Fazer o Commit Inicial*:
   - No terminal do VS Code, adicionei o arquivo experimento.txt à área de preparação e fiz o commit inicial:
     bash
     git add experimento.txt
     git commit -m "Adiciona conteúdo inicial em experimento.txt"
     

### 3. Vinculação do Repositório Local ao Repositório On-line

1. *Definir o Repositório Remoto*:
   - No terminal do VS Code, usei o seguinte comando para definir o repositório Git on-line como remoto do repositório local:
     bash
     git remote add origin https://github.com/lucasandare490/git-test.git
     

2. *Enviar os Commits para o Repositório On-line*:
   - Enviei o commit inicial do repositório local para o GitHub usando o comando:
     bash
     git push -u origin master
     

### 4. Clonagem do Repositório Git On-line

1. *Testar a Clonagem do Repositório*:
   - Para confirmar que o repositório foi configurado corretamente, fiz uma clonagem para um novo diretório.
   - No terminal, usei o comando:
     bash
     git clone https://github.com/lucasandare490/git-test.git
     
   - Esse comando baixou uma cópia completa do repositório git-test do GitHub para o ambiente local.

### 5. Manipulação de Arquivo e Testes de Comandos Git

1. *Modificações no Arquivo experimento.txt*:
   - Editei o arquivo experimento.txt para praticar o comando git restore.
   - Após a modificação, usei o comando:
     bash
     git restore experimento.txt
     
   - Esse comando reverteu as alterações não comitadas no arquivo.

2. *Testando o Comando git reset*:
   - Fiz mais uma modificação em experimento.txt, adicionei a alteração e fiz um commit.
   - Para desfazer o commit, usei:
     bash
     git reset --hard
     
   - O comando restaurou o arquivo experimento.txt ao estado do commit anterior.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:
- *README.md*: Documentação do exercício, incluindo os passos realizados.
- *experimento.txt*: Arquivo utilizado para praticar comandos Git.

## Como Usar Este Repositório

1. *Clonar o Repositório*:
   - Para clonar este repositório, execute:
     bash
     git clone https://github.com/lucasandare490/git-test.git
     cd git-test
     

2. *Praticar Comandos Git*:
   - Depois de clonar, é possível modificar experimento.txt, adicionar novas alterações e praticar comandos como git add, git commit, git push, git restore e git reset.

