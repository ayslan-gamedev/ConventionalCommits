# 🚀 Padrão de Commits com Emojis e Conventional Commits
<a href="https://github.com/Ayslan-gamedev/ConventionalCommits/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ayslan-gamedev/ConventionalCommits?color=blue&style=flat-square"></a>

Este repositório demonstra um padrão de commits que combina emojis e o estilo Conventional Commits para mensagens de commit mais descritivas e informativas.

De acordo com a documentação do Conventional Commits, Commits Semânticos são uma convenção simples para ser utilizada nas mensagens de commit. Essa convenção define um conjunto de regras para criar um histórico de commit explícito, o que facilita a criação de ferramentas automatizadas.

## ⚙️ Configuração Inicial

  Siga os passos abaixo para configurar e começar a usar esse padrão de commits no seu projeto:
  
  ### 1. Inicialize um Repositório Git
  
  Se você ainda não tem um repositório Git, inicie um com o seguinte comando:
  
       ```bash
       git init
       ```
  
  ### 2. Instale as Dependências
  
  Instale as dependências necessárias para trabalhar com esse padrão de commits:
  
       ```bash
       npm install --save-dev commitizen cz-customizable
       npm install --save-dev commitizen
       ```

  ### 3. Adicione os Arquivos de Configuração
  Adicione os arquivos .czrc e .cz-config.js ao seu projeto. Você pode encontrar esses arquivos diretamente nesse repositório nas releases.

  ### 4. Atualize o package.json
  No arquivo package.json, adicione a seguinte seção aos seus scripts:

       ```package.json
       "scripts": {
         "test": "echo \"Error: no test specified\" && exit 1",
         "commit": "npx git-cz"
       }
       ```
  Agora, você está pronto para começar a usar o padrão de commits!

## 🛠️ Como Usar
Para criar commits seguindo esse padrão, siga essas etapas:

Execute o comando de commit personalizado:

    ```bash
    npx git-cz
    ```
    
Você será apresentado com uma série de perguntas interativas. Preencha as informações solicitadas, como o tipo de commit, uma descrição concisa e opcionalmente um corpo mais detalhado.
Após responder às perguntas, o commit será gerado automaticamente com a formatação adequada, incluindo emojis e um formato Conventional Commits.

## 🙏 Agradecimentos

Este padrão de commits foi inspirado pelo trabalho de [Holivane](https://github.com/Holivane) e seu repositório [padroes-de-commit](https://github.com/Holivane/padroes-de-commit). Agradecemos a Holivane pela sua contribuição à comunidade de desenvolvimento e por compartilhar seu conhecimento sobre boas práticas de commits.

A documentação detalhada sobre como usar as mensagens de commit está disponível no repositório de Holivane. Certifique-se de conferir [aqui](https://github.com/Holivane/padroes-de-commit) para obter mais informações sobre a formatação das mensagens de commit.

Este projeto é uma evolução baseada no excelente trabalho iniciado por Holivane.
