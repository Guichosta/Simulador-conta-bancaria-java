# Simulador de Conta Bancária em Java

Uma aplicação simples de **console desenvolvida em Java** que simula operações básicas de uma conta bancária. O projeto foi desenvolvido como um exercício prático para aplicar conceitos fundamentais de programação em Java, como variáveis, estruturas condicionais, estruturas de repetição, entrada de dados e operações matemáticas.

## 📌 Sobre o Projeto

A aplicação representa uma conta bancária e disponibiliza ao usuário um menu com diferentes operações:

* Consultar o saldo atual da conta
* Transferir dinheiro
* Receber dinheiro
* Sair da aplicação

O programa funciona inteiramente pelo **terminal/console** e utiliza a classe `Scanner` para receber os dados informados pelo usuário.

## ⚙️ Funcionalidades

### Informações da Conta

Ao iniciar a aplicação, são exibidas informações como:

* Nome do cliente
* Tipo da conta
* Saldo atual

### Consulta de Saldo

O usuário pode consultar o saldo disponível na conta a qualquer momento.

### Transferência de Dinheiro

O usuário pode informar o valor que deseja transferir. A aplicação verifica se existe saldo suficiente antes de realizar a operação.

### Recebimento de Dinheiro

O usuário pode informar um valor para receber, que será adicionado ao saldo atual da conta.

### Validação de Entrada

A aplicação trata opções inválidas do menu e impede que uma transferência seja realizada quando o valor solicitado é maior que o saldo disponível.

## 🛠️ Tecnologias Utilizadas

* **Java**
* **Scanner**
* **Text Blocks**
* **Conceitos fundamentais de Programação Orientada a Objetos**
* **Interface via linha de comando (CLI)**

## 📂 Estrutura do Projeto

```text
java-bank-account-simulator/
│
├── src/
│   └── Desafio.java
│
└── README.md
```

## ▶️ Como Executar

### 1. Clone o repositório

```bash
git clone https://github.com/SEU-USUARIO/java-bank-account-simulator.git
```

### 2. Acesse o diretório do projeto

```bash
cd java-bank-account-simulator
```

### 3. Compile o arquivo Java

```bash
javac src/Desafio.java
```

### 4. Execute a aplicação

```bash
java -cp src Desafio
```

## 💻 Exemplo de Execução

Ao iniciar a aplicação, as informações da conta e as operações disponíveis são apresentadas:

```text
****************************************

Nome do Cliente: Clark Kent
Tipo conta: Corrente
Saldo Atual: 1599.99

****************************************

** Digite sua opção**
1 - Consultar saldo
2 - Transferir valor
3 - Receber valor
4 - Sair
```

O usuário pode selecionar uma operação digitando o número correspondente.

## 🎓 Objetivos de Aprendizagem

Este projeto foi desenvolvido para praticar conceitos fundamentais da linguagem Java, incluindo:

* Variáveis e tipos de dados
* Utilização da classe `Scanner`
* Estruturas condicionais `if / else`
* Estruturas de repetição `while`
* Operações matemáticas
* Manipulação de Strings
* Saída de dados no console
* Validação básica de entradas

## 🚀 Possíveis Melhorias

Em versões futuras, o projeto poderia incluir:

* Cadastro de múltiplas contas bancárias
* Sistema de login e autenticação
* Histórico de transações
* Simulação de pagamentos via PIX
* Criação de novas contas
* Validação de dados mais completa
* Arquitetura baseada em Programação Orientada a Objetos
* Persistência de dados

## 📄 Licença

Distribuído sob a licença MIT. Veja LICENSE para mais detalhes.
