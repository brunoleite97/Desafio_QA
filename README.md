# Desafio de Teste de Software para Estagiário de QA

Olá, candidato(a)! Boas-vindas ao nosso desafio de Quality Assurance.

Este teste foi projetado para avaliarmos suas habilidades em análise, documentação e execução de testes de software. Queremos entender como você pensa e estrutura seu trabalho ao explorar uma nova aplicação.

## Objetivo

O principal objetivo deste desafio é realizar testes exploratórios na aplicação "Seu Barriga", documentar suas descobertas e reportar os problemas encontrados. Você terá a liberdade de explorar a aplicação como um usuário final, buscando entender suas funcionalidades e possíveis falhas.

## Aplicação para Testes

A aplicação a ser testada está disponível no seguinte endereço:
**URL:** `https://seubarriga.wcaquino.me/login`

**Credenciais para acesso:**
Para começar, você precisará criar um novo usuário diretamente na aplicação.

## Sua Missão

Você deverá realizar as seguintes tarefas:

1.  **Exploração e Análise:** Navegue pela aplicação para entender suas principais funcionalidades. Crie uma conta, faça login, explore as seções de "Contas", "Movimentação" e "Resumo Mensal". Tente realizar as operações que um usuário comum faria.

2.  **Plano de Testes:** Crie um documento simples de plano de testes. Este documento deve conter, no mínimo:
    * O objetivo dos testes.
    * O escopo (o que será testado e o que **não** será testado).
    * A estratégia de teste que você irá adotar (ex: quais tipos de teste você focará).

3.  **Cenários de Teste em Gherkin:** Escreva os cenários de teste para as funcionalidades que você considerou mais críticas. Utilize a sintaxe Gherkin (Dado, Quando, Então).
    * **Exemplo:**
        ```gherkin
        # language: pt

        Funcionalidade: Autenticação de Usuário
        Como um usuário cadastrado
        Eu quero poder me autenticar no sistema
        Para acessar minhas informações financeiras

        Cenário: Login com sucesso
          Dado que eu esteja na tela de login
          E eu informe o email "usuario@teste.com"
          E eu informe a senha "123456"
          Quando eu clicar no botão "Entrar"
          Então eu devo ser redirecionado para a tela principal
          E a mensagem "Bem vindo, [Seu Nome]!" deve ser exibida
        ```

4.  **Documentação da Funcionalidade:** Descreva de forma clara e objetiva como as principais funcionalidades do sistema operam, com base no que você observou. O que o sistema faz? Quais são os principais fluxos?

5.  **Relatório de Bugs:** Documente todos os bugs (erros, falhas de usabilidade, comportamentos inesperados) que encontrar. Cada bug deve ser reportado com as seguintes informações:
    * **Título:** Um resumo claro e conciso do problema.
    * **Passos para reproduzir:** O passo a passo detalhado para que outra pessoa consiga encontrar o mesmo problema.
    * **Resultado Esperado:** O que deveria ter acontecido.
    * **Resultado Atual:** O que de fato aconteceu.
    * **Evidências:** Se possível, anexe screenshots ou GIFs.
    * **Severidade:** Classifique o impacto do bug (ex: Crítica, Alta, Média, Baixa).

## O que será avaliado?

Nós avaliaremos os seguintes pontos:

* **Clareza e Organização:** A estrutura e a clareza dos documentos que você criar.
* **Capacidade de Análise:** Sua habilidade para entender o sistema e identificar os fluxos mais importantes para teste.
* **Qualidade da Documentação:** A qualidade da escrita dos cenários de teste e dos relatórios de bugs.
* **Atenção aos Detalhes:** Sua capacidade de encontrar bugs válidos, incluindo não apenas erros funcionais, mas também problemas de usabilidade e de texto.

## Como Entregar

Para nos enviar seu desafio finalizado, você pode escolher uma das duas opções abaixo:

**Opção 1: Repositório Git**
Envie-nos o link para um repositório público (GitHub, GitLab, etc.) contendo os seguintes arquivos:
* `PLANO_DE_TESTES.md`
* `RELATORIO_DE_BUGS.md`

**Opção 2: Arquivos Diretos**
Se preferir, você pode compilar todos os documentos solicitados em arquivos (por exemplo, em formato **PDF**) e nos enviá-los diretamente. Os arquivos devem ser nomeados da seguinte forma:
* `PLANO_DE_TESTES.pdf`
* `RELATORIO_DE_BUGS.pdf`

Boa sorte! Estamos ansiosos para ver seu trabalho.
