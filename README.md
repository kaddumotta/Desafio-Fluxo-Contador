# Desafio Controle de Fluxo - Java

Este projeto foi desenvolvido como parte de um desafio para praticar **controle de fluxo**, **laços de repetição** e **tratamento de exceções customizadas** em Java.

---

## 📌 Descrição do Desafio

O sistema recebe **dois números inteiros via terminal** e realiza as seguintes ações:

- Calcula a quantidade de interações com base na diferença entre os dois números
- Imprime no console uma sequência incremental de mensagens
- Valida se os parâmetros são válidos, lançando uma **exceção customizada** quando necessário

---

## ⚙️ Regras de Negócio

1. O programa deve receber dois números inteiros:
   - `parametroUm`
   - `parametroDois`

2. Se `parametroUm` for **maior** que `parametroDois`:
   - O sistema deve lançar a exceção  
     `ParametrosInvalidosException`
   - Mensagem obrigatória:
     ```
     O segundo parâmetro deve ser maior que o primeiro
     ```

3. Caso contrário:
   - O sistema calcula:
     ```
     parametroDois - parametroUm
     ```
   - E imprime no console:
     ```
     Imprimindo o número 1
     Imprimindo o número 2
     ...
     ```

---

## 🗂️ Estrutura do Projeto

src
└── Contador
├── Contador.java
└── ParametrosInvalidosException.java


---

## 🧩 Classes do Projeto

### 🔹 Contador.java
Responsável por:
- Ler os dados do terminal
- Chamar o método de contagem
- Tratar a exceção customizada

### 🔹 ParametrosInvalidosException.java
- Exceção de negócio criada para validar os parâmetros
- Estende a classe `Exception`

---

## ▶️ Exemplo de Execução

### Entrada válida:
Digite o primeiro parâmetro:

12

Digite o segundo parâmetro:

30

### Saída:
Imprimindo o número 1

Imprimindo o número 2

...

Imprimindo o número 18


---

### Entrada inválida:
Digite o primeiro parâmetro:

30

Digite o segundo parâmetro:

12

### Saída:
O segundo parâmetro deve ser maior que o primeiro


---

## 🛠️ Tecnologias Utilizadas

- Java
- Scanner (entrada via terminal)
- Tratamento de exceções
- Controle de fluxo (`if`, `for`)

---

## 🚀 Objetivo do Projeto

Este projeto tem como objetivo reforçar conceitos fundamentais de Java, como:
- Estrutura de repetição
- Validação de regras de negócio
- Criação e uso de exceções customizadas
- Organização de código em packages

---

📚 Projeto desenvolvido para fins educacionais.
