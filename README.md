# Desenvolvimento de um Compilador para a Linguagem C-
--------------

Apresentado à Universidade Federal de São Paulo como parte dos requisitos para aprovação na disciplina de Compiladores.   
Docente: Prof. Dr. Rodrigo Colnago Contreras

## Discentes  
<p>
Ana Luiza Antonio Feitosa (RA: 168517)  <br>
Larissa Martins Sá (RA: 168949)  <br>
Marcella Fernandes Moraes (RA: 170982)  <br>
  </p>

# Desenvolvimento de um Compilador para a Linguagem C−

Apresentado à Universidade Federal de São Paulo como parte dos requisitos para aprovação na disciplina de **Compiladores**.  
**Docente:** Prof. Dr. Rodrigo Colnago Contreras

## Discentes

- **Ana Luiza Antonio Feitosa** (RA: 168517)  
- **Larissa Martins Sá** (RA: 168949)  
- **Marcella Fernandes Moraes** (RA: 170982)

---

## Resumo

Este repositório apresenta o desenvolvimento de um compilador para a linguagem **C−**, uma versão simplificada da linguagem C. O objetivo do projeto é aplicar os conceitos fundamentais estudados na disciplina de Compiladores, abordando as principais etapas do processo de compilação:

- **Análise léxica**
- **Análise sintática**
- **Construção da Árvore Sintática Abstrata (AST)**
- **Gerenciamento da tabela de símbolos**
- **Análise semântica**
- **Geração de código intermediário**

A linguagem **C−** foi escolhida por sua simplicidade, permitindo a implementação incremental dos módulos do compilador, conforme proposto por **Louden (2004)**. Este projeto visa consolidar o entendimento teórico dos algoritmos e das estruturas de dados envolvidas, além de proporcionar experiência prática no desenvolvimento de software de sistemas.

---

## Estrutura do Projeto

A estrutura do projeto é composta pelas seguintes etapas e módulos:

- **Analisador Léxico:** responsável pela identificação de tokens da linguagem.  
- **Analisador Sintático:** verifica a conformidade sintática dos tokens.  
- **Árvore Sintática Abstrata (AST):** representação hierárquica do programa.  
- **Tabela de Símbolos:** armazena as variáveis e funções definidas no código.  
- **Analisador Semântico:** verifica a consistência semântica do código.  
- **Geração de Código Intermediário:** produz uma representação intermediária do código.  

---

## Estrutura do Projeto

---

## Como Executar

### Pré-requisitos

- Compilador C/C++ compatível (exemplo: `gcc`, `g++`, `clang`)
- Sistema operacional Windows, Linux ou macOS

### Execução

No terminal, navegue até a pasta do projeto e execute:

```bash
mingw32-make
```
ou 
```bash
make
```
A'pos isso, para rodar um arquvo com teste de exemplo, execute:
```bash
./cminus.exe ./nome_do_arquivo_teste.cm
```

