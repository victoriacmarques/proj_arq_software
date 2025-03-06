# Repositório de Exercícios - Projeto e Arquitetura de Software

Este repositório contém os exercícios desenvolvidos na disciplina **Projeto e Arquitetura de Software**. Cada exercício pode conter um ou mais projetos, organizados em diretórios específicos.

## Objetivos

- Centralizar todos os exercícios desenvolvidos durante o semestre.
- Facilitar a organização e o acesso aos códigos implementados.
- Praticar o uso do **GitHub Codespaces** como ambiente de desenvolvimento.

## Requisitos

Para executar os projetos neste repositório:
- **Se estiver usando o GitHub Codespaces**, nenhuma instalação adicional é necessária, pois o ambiente já vem configurado com o JDK.
- **Se estiver executando localmente**, você precisará instalar:
- **Git** (opcional, apenas necessário se quiser clonar o repositório para rodar localmente)
- **Java Development Kit (JDK 17 ou superior)** ([Download](https://www.oracle.com/java/technologies/javase-downloads.html))
- **Uma IDE compatível**, como [VS Code](https://code.visualstudio.com/) ou [IntelliJ IDEA](https://www.jetbrains.com/idea/)

## Organização do Repositório

```
proj_arq_soft
 ┣ exercício01
 ┃ ┣ projeto1a
 ┃ ┃ ┣ arquivos do projeto
 ┃ ┃ ┗ README.md
 ┃ ┣ projeto1b
 ┃ ┃ ┣ arquivos do projeto
 ┃ ┃ ┗ README.md
 ┃ ┗ README.md (descrição geral do exercício)
 ┣ exercício02
 ┃ ┣ projeto2a
 ┃ ┣ projeto2b
 ┃ ┗ README.md
 ┣ README.md (documentação geral do repositório)
```

## Como Executar um Projeto

Independentemente de utilizar o GitHub Codespaces ou rodar localmente, os comandos para executar um projeto são os mesmos:

1. Navegue até o diretório do projeto desejado:
   ```sh
   cd exercicio01/projeto1a
   ```
2. Compile os arquivos Java:
   ```sh
   javac *.java
   ```
3. Execute o programa:
   ```sh
   java App
   ```

Isso funciona desde que:

- O arquivo principal se chame App.java.
- Ele esteja no pacote padrão (sem declaração package no topo).
- Não haja subpastas com outras classes.


## Observações
- Este repositório é público e será utilizado exclusivamente para exercícios de aula.
- Trabalhos e exercícios avaliativos serão desenvolvidos em repositórios específicos do **GitHub Classroom**, conforme indicado pelo professor.
