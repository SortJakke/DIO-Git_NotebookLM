# Caderno Temático - Git & GitHub

## Contexto e Objetivos

### Tema escolhido

O tema deste caderno temático é **Git & GitHub**, duas das principais ferramentas utilizadas no desenvolvimento de software para controle de versão, colaboração entre equipes e gerenciamento de projetos.

O objetivo deste material é construir uma base sólida sobre o funcionamento do Git, compreender sua história, dominar seus principais comandos e avançar para conceitos mais complexos utilizados no ambiente profissional.

### Objetivos de estudo

- Compreender a origem e a evolução do Git.
- Entender o papel do GitHub dentro do ecossistema de desenvolvimento.
- Aprender os conceitos fundamentais de controle de versão.
- Dominar os principais comandos do Git.
- Estudar fluxos de trabalho (workflows) utilizados em equipes.
- Aprender recursos avançados

---

## Curadoria de Fontes

As seguintes fontes foram selecionadas para compor a base de conhecimento utilizada no NotebookLM.

### Vídeos

1. Entendendo GIT - Fabio Akita
   - https://www.youtube.com/watch?v=6Czd1Yetaac

2. Git & GitHub Crash Course for Beginners - FreeCodeCamp.org
   - https://www.youtube.com/watch?v=mAFoROnOfHs

3. Usando Git Direito - Fabio Akita
   - https://www.youtube.com/watch?v=6OokP-NE49k

4. Git for Professionals Tutorial - FreeCodeCamp.org
   - https://www.youtube.com/watch?v=Uszj_k0DGsg

### Documentação

5. Git Cheat Sheet (Documentação Oficial)
   - https://git-scm.com/cheat-sheet

6. Livro Pro Git (PDF)
   - progit.pdf

---

## Engenharia de Prompt e "Cicatrizes"

Durante os estudos, diferentes estratégias de prompts foram utilizadas para extrair respostas cada vez mais úteis do NotebookLM.

### Prompt 1

> Faça um resumo da história do Git. Estou estudando Git e GitHub e acredito que a base do conhecimento é entender o proposito da ferramenta, por que ela foi criada? em qual contexto? por quem? e outras perguntas do gênero. Quero que você faça um resumo objetivo, relatando os dados realmente relevantes.

#### Técnicas de Prompt

- Instrução Clara
- Contextualização
- Repetição de instrução

#### Resultado

Atráves desse prompt o NotebookLM resumiu a história do Git em tópicos relevantes, como:

- O que era utilizado antes da criação do Git;
- Quem criou o Git, quando e por quê;
- Quais foram os diferenciais que Torvalds estabeleceu; e
- O que é o GitHub e quando foi criado.

---

### Prompt 2

> Crie um roadmap detalhado de aprendizado Git & GitHub para completos iniciantes.

#### Técnica de Prompt

Não segui nenhuma técnica avançada de prompt, somente uma instrução clara. O objetivo foi entender como ele usaria as referências fornecidas.

#### Resultado

Uma plano de estudos dividido em 6 fases, indicando uma ordem de conceitos que um iniciante deveria aprender. Não houve instruções especificas de como usar um comando ou algo do tipo, somente uma orientação de ordem de aprendizado.

---

### Prompt 3

> Liste os conhecimentos necessários para ser um profissional em Git & GitHub.

#### Técnicas de Prompt
Novamente não usei nenhuma técnica avançada, e tão pouco dei uma instrução clara, deixando a critério da IA definir o que seriam conhecimentos profissionais.

#### Resultado
A IA retornou a lista de conhecimentos necessarios subdivididos em 5 catégorias principais:
* Arquitetura e funcionamento interno
* Ramificação (Branching) e integração Avançada
* Manipulação e Limpeza de Histórico
* Colaboração Profissional no GitHub
* Configuração e Automação

---

### Prompt 4

> Explique detalhadamente como funcionam Branch, Merge e Rebase utilizando diagramas mentais em texto.

#### Técnica de Prompt
* Instrução Clara
* Formato da saída

#### Resultado

A IA retornou uma explicação clara e objetivas sobre cada tópico, fazendo o uso de diagramas, conforme especificado. Além disso retornou, também, um pequeno resumo comparativo ao final.

---

### Prompt 5

> Simule um projeto profissional utilizando Git desde a criação até o deploy.

#### Técnica de Prompt
Novamente nenhuma técnica especial, somente uma instrução básica para entender como a IA usaria as referências nessa situação.

#### Resultado

A IA apresentou um fluxo completo envolvendo:

- Preparação e configuração inicial
- Ciclo de Desenvolvimento (trabalho em equipe)
- Sincronização e Colaboração
- Integração e Deploy
- Manutenção e Limpeza

---

# Miniguia de Estudos

## 1. Resumo Estruturado

### O que é Git?

Git é um sistema de controle de versão distribuído que registra alterações em arquivos ao longo do tempo, permitindo recuperar versões anteriores e colaborar com outras pessoas.

---

### O que é GitHub?

GitHub é uma plataforma online que hospeda repositórios Git e oferece recursos para colaboração, revisão de código e gerenciamento de projetos.

---

### História do Git

- Criado em 2005.
- Desenvolvido por Linus Torvalds.
- Surgiu após problemas com o sistema BitKeeper.
- Tornou-se o sistema de controle de versão mais utilizado no mundo.

---

### Conceitos Básicos

- Repositório
- Commit
- Branch
- Merge
- Clone
- Pull
- Push
- Fetch
- Status
- Log

---

### Conceitos Avançados

- Rebase
- Cherry-pick
- Stash
- Tags
- Git Flow
- Squash
- Fast Forward
- Detached HEAD
- Hooks
- Resolução de conflitos

---

# Glossário

| Conceito   | Definição                                            |
| ---------- | ---------------------------------------------------- |
| Repository | Local onde o projeto é armazenado.                   |
| Commit     | Registro permanente das alterações.                  |
| Branch     | Linha paralela de desenvolvimento.                   |
| Merge      | União entre branches.                                |
| Rebase     | Reorganização do histórico de commits.               |
| Clone      | Cópia completa de um repositório remoto.             |
| Push       | Envia alterações para o repositório remoto.          |
| Pull       | Atualiza o repositório local com alterações remotas. |
| Fetch      | Busca alterações remotas sem aplicá-las.             |
| HEAD       | Referência para o commit atual.                      |
| Origin     | Repositório remoto principal.                        |
| Tag        | Marca uma versão específica do projeto.              |

---
