# Repositório git-test

Este repositório foi criado para praticar comandos Git e configurar a sincronização com o GitHub, seguindo as instruções do exercício da Aula 01. Nele, desenvolvi habilidades essenciais em Git, incluindo o uso de repositório local e remoto, controle de versão, e manipulação de commit.

## Objetivo do Exercício

Este exercício tem como objetivo:
- Configurar um repositório Git local e vinculá-lo a um repositório remoto no GitHub.
- Realizar commit com mensagem descritiva.
- Enviar (push) alteração para o repositório no GitHub.
- Clonar um repositório do GitHub para o ambiente local.
- Praticar comandos Git para desfazer alteração, como git restore e git reset.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:
- *README.md*: Arquivo de descrição do projeto, contendo o objetivo do exercício, passos realizados e instruções de uso.
- *experimento.txt*: Arquivo utilizado para realizar alteração e praticar comandos Git, como commit, restore e reset.

## Passos Realizados no Exercício

### 1. Configuração do Repositório Local
- Criei uma pasta chamada git-historico no ambiente local.
- Inicializei o repositório Git local com o comando:
  ```bash
  git init

	•	Criei o arquivo experimento.txt e adicionei conteúdo inicial.

2. Manipulação de Arquivo e Commit

	•	Adicionei experimento.txt ao repositório e realizei o primeiro commit:

git add experimento.txt
git commit -m "Adiciona conteúdo inicial em experimento.txt"


	•	Fiz uma modificação em experimento.txt, mas descartei essa alteração com git restore para reverter a alteração não comitada:

git restore experimento.txt


	•	Fiz uma nova modificação e um commit adicional, então usei git reset --hard para desfazer o último commit, retornando ao estado inicial:

git reset --hard



3. Configuração do Repositório Remoto no GitHub

	•	Criei um repositório remoto no GitHub chamado git-test.
	•	Vinculei o repositório local ao repositório remoto no GitHub com o comando:

git remote add origin https://github.com/lucasandare490/git-test.git


	•	Enviei o commit inicial para o GitHub com:

git push -u origin master



4. Clonagem do Repositório

	•	Para testar a clonagem, utilizei o comando abaixo para clonar o repositório git-test do GitHub em uma nova pasta local:

git clone https://github.com/lucasandare490/git-test.git



Como Usar Este Repositório

Clonar o Repositório

Para clonar este repositório e explorar os comandos praticados, execute:

git clone https://github.com/lucasandare490/git-test.git
cd git-test

Praticar Comandos Git

Depois de clonar, você pode:
	•	Modificar o arquivo experimento.txt.
	•	Usar comandos como git add, git commit, git push para enviar alteração ao repositório remoto.
	•	Experimentar git restore para descartar alteração não comitada e git reset para desfazer commit.

Conclusão

Este exercício me ajudou a aprender e praticar os seguintes aspectos do Git:
	•	Inicialização e configuração de repositório local e remoto.
	•	Manipulação e desfazer de alteração em arquivo e commit.
	•	Sincronização entre o repositório local e o remoto no GitHub.

Essas habilidades são fundamentais para o uso eficiente do Git em controle de versão e colaboração em projeto de desenvolvimento.

---
