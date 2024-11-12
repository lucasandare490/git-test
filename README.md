# git-test

Este repositório foi criado para praticar comandos Git e configurar a sincronização com o GitHub. O objetivo é desenvolver habilidades em Git, incluindo o uso de repositórios locais e remotos, e a aplicação de comandos essenciais para controle de versão.

## Objetivos

Ao trabalhar neste repositório, aprendemos a:
- Configurar um repositório local e vincular a um repositório remoto no GitHub.
- Realizar commits com mensagens claras e descritivas.
- Enviar (push) alterações do repositório local para o GitHub.
- Clonar repositórios do GitHub para o ambiente local.
- Desfazer alterações e commits com `git restore` e `git reset`.
  
## Estrutura do Repositório

O repositório contém os seguintes arquivos:

- **README.md**: Este arquivo, que descreve o propósito e as instruções do repositório.
- **experimento.txt**: Arquivo de exemplo utilizado para praticar comandos Git, com alterações feitas e desfeitas como parte do exercício.
  
## Passos Realizados

1. **Configuração do Repositório Local**:
   - Criamos uma pasta local chamada `git-historico` e inicializamos o repositório Git com `git init`.
   - Criamos o arquivo `experimento.txt` e realizamos um commit inicial.

2. **Manipulação de Arquivo e Commits**:
   - Adicionamos e comitamos o arquivo `experimento.txt` com conteúdo inicial.
   - Realizamos alterações e as revertimos usando `git restore` para praticar o descarte de modificações não comitadas.
   - Fizemos mais alterações, comitamos, e usamos `git reset --hard` para desfazer um commit, restaurando o arquivo ao estado anterior.

3. **Configuração do Repositório Remoto no GitHub**:
   - Criamos um repositório no GitHub chamado `git-test` e vinculamos o repositório local a ele usando `git remote add origin <URL-do-repositório>`.
   - Usamos `git push -u origin master` para enviar o commit inicial ao repositório remoto.

4. **Clonagem do Repositório**:
   - Para testar a clonagem, clonamos o repositório `git-test` de volta para uma nova pasta em nosso ambiente local com `git clone <URL-do-repositório>`.

## Como Usar Este Repositório

1. **Clonar o Repositório**:
   ```bash
   git clone https://github.com/lucasandare490/git-test.git
   cd git-test
