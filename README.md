# Desafio Controle de Fluxo

Este projeto é a solução para um desafio de controle de fluxo em Java, proposto para exercitar conceitos como laços de repetição (`for`), tratamento de exceções e validação de parâmetros.

---

### 🚀 Sobre o Projeto

O programa foi desenvolvido em Java e tem como objetivo principal receber dois números inteiros via terminal. A partir deles, o sistema realiza as seguintes ações:

1.  Calcula a diferença entre o segundo e o primeiro parâmetro para determinar o número de iterações.
2.  Utiliza um laço `for` para imprimir no console os números de 1 até o valor da diferença.
3.  Caso o primeiro parâmetro seja **maior** que o segundo, uma exceção customizada (`ParametrosInvalidosException`) é lançada com a mensagem de erro apropriada.

---

### 🛠️ Tecnologias Utilizadas

* **Java 11+**
* **Controle de Fluxo** (`if`, `for`, `try-catch-finally`)
* **Tratamento de Exceções** (Criação de exceção customizada)
* **Classes e Métodos**

---

### 📁 Estrutura de Arquivos

O projeto consiste em duas classes principais:

* `Contador.java`: Contém a lógica principal do programa, incluindo a entrada de dados do usuário e a chamada para o método de contagem.
* `ParametrosInvalidosException.java`: Uma exceção de negócio customizada, criada para lidar com a situação em que os parâmetros fornecidos são inválidos.

---

### 💻 Como Executar

Para rodar o projeto, siga estes passos:

1.  Certifique-se de ter o **Java JDK** instalado em sua máquina.
2.  Compile as classes no terminal:
    ```bash
    javac Contador.java ParametrosInvalidosException.java
    ```
3.  Execute o programa a partir da classe `Contador`:
    ```bash
    java Contador
    ```
4.  O programa solicitará que você digite os dois parâmetros.

#### Exemplo de uso:

* **Entrada válida:**
    ```
    Digite o primeiro parâmetro
    12
    Digite o segundo parâmetro
    30
    ```
* **Saída esperada:**
    ```
    Imprimindo o número 1
    Imprimindo o número 2
    ...
    Imprimindo o número 18
    ```
* **Entrada inválida:**
    ```
    Digite o primeiro parâmetro
    30
    Digite o segundo parâmetro
    12
    ```
* **Saída esperada:**
    ```
    O segundo parâmetro deve ser maior que o primeiro
    ```

---

### ✍️ Autor

* [JoaoVilarue](https://github.com/JoaoVilaruel)
