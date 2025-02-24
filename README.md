# 🚀 Desafio Controle de Fluxo

Este projeto implementa um contador numérico baseado na entrada do usuário, praticando conceitos de **controle de fluxo** em Java. Ele recebe dois números inteiros via terminal e imprime uma sequência de números com base na diferença entre eles.

---

## 📌 **Regras do Programa**
- O usuário insere **dois números inteiros**.
- O programa calcula a **quantidade de interações** necessárias e imprime os números sequencialmente.
- Se o **primeiro número for maior que o segundo**, o programa lança uma exceção personalizada (`ParametrosInvalidosException`).

---

## 🛠 **Tecnologias Utilizadas**
- **Java 17+**
- **Scanner (Entrada de Dados)**
- **Exceções Personalizadas**

---

## 📥 **Como Executar o Programa**
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/desafio-controle-fluxo.git
   cd desafio-controle-fluxo
   ``` 
2. Compile o código:
   ```sh
   javac Contador.java ParametrosInvalidosException.java
   ```

3. Execute o programa:
 Compile o código:
   ```sh
   java Contador
   ```

---

## 🔢 **Exemplo de Uso**

### ✅ Entrada:

```bash
Digite o primeiro parâmetro: 
5
Digite o segundo parâmetro: 
10
```

### 📌 Saída:
```bash
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```

## 🚨 Exemplo de Erro:

### ❌ Entrada:
```bash
Digite o primeiro parâmetro:
10
Digite o segundo parâmetro:
5
```
### ⚠️ Saída:
```bash
O segundo parâmetro deve ser maior que o primeiro.
```
## 📂 Estrutura do Projeto

```📁 desafio-controle-fluxo
 ┣ 📜 Contador.java
 ┣ 📜 ParametrosInvalidosException.java
 ┗ 📜 README.md
 ```

## 📝 Créditos

Desenvolvido por Larissa Albuquerque como parte do Desafio Controle de Fluxo da dio.me, para praticar estruturas condicionais e exceções em Java. 🚀