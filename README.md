# 💻 Final Work - Orientação a Objetos (UFJF)

Trabalho final da disciplina de **Orientação a Objetos** da **Universidade Federal de Juiz de Fora (UFJF)**.

* **Professor:** Marcelo de Oliveira Costa Machado
* **Tecnologias:** Java, Maven

---

## 📋 Sobre o Projeto

> *[description project]*

### Conceitos Aplicados
* Encapsulamento, Herança e Polimorfismo
* Classes Abstratas e Interfaces
* Tratamento de Exceções
* Coleções e Manipulação de Dados

---

## 🛠️ Boas Práticas e Padrões do Repositório

Para manter a qualidade, legibilidade e organização do código, toda a equipe deve seguir rigorosamente as diretrizes abaixo:

### 1. Commits Semânticos (em Inglês)
Todas as mensagens de commit devem estar em **inglês** e seguir o padrão [Conventional Commits](https://conventionalcommits.org):
* `feat:` nova funcionalidade (ex: `feat: insert user registration function`)
* `fix:` correção de bug (ex: `fix: resolve null pointer exception on login`)
* `refactor:` refatoração de código sem alterar comportamento (ex: `refactor: simplify payment calculation logic`)
* `docs:` alterações na documentação (ex: `docs: update README instructions`)
* `test:` adição ou ajuste de testes (ex: `test: add unit tests for account class`)
* `chore:` tarefas de configuração, build ou dependências (ex: `chore: update maven dependencies`)

### 2. Fluxo de Branches
* **Criação de branches:** Cada nova tarefa, funcionalidade ou correção deve ser desenvolvida em uma **branch separada**, criada a partir da `developer` e seguindo o prefixo semântico:
    * `feat/nome-da-funcionalidade`
    * `fix/nome-do-erro`
    * `refactor/nome-da-refatoracao`
      *(Exemplo: `git checkout -b refactor/MinhaBranch`)*
* **Regra de Merge (Homologação):** Todo merge deve ser feito **primeiramente na branch `developer`**. Somente após testar e garantir que o código está funcionando e não quebrou nada, as alterações podem ser integradas à branch `main`.
  ```text
  feature/sua-branch ──▶ developer (testes/validação) ──▶ main (versão estável)
  ```



### 3. Clean Code e Padrão de Nomenclatura
* **Idioma do código:** Todos os nomes de **classes, atributos, métodos, variáveis e pacotes** devem ser escritos em **inglês**, exceto aqueles que já foram previamente definidos pela especificação do trabalho.
* **Nomes de variáveis:** Devem ser sugestivos e representativos, deixando claro o que armazenam (evite abreviações como `aux`, `x`, `temp`).
* **Nomes de métodos:** Devem ser verbos ou frases verbais em inglês que digam por si só o que o método faz (ex: `calculateNetSalary()`, `validateDocument()`).
* **Comentários:** Utilize apenas quando estritamente necessário. O código deve ser autoexplicativo por meio de boa estruturação e nomenclatura clara.


---

## 🚀 Como Executar o Projeto

### Pré-requisitos
* **Java JDK** (versão 21 ou superior recomendada)
* **Maven** (ou utilize o Maven Wrapper `./mvnw` incluso no projeto)

### Passo a passo
1. Clone o repositório:
   ```bash
   git clone https://github.com
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd final-work-oop
   ```
3. Compile e execute via Maven:
   ```bash
   ./mvnw clean install
   ./mvnw exec:java -Dexec.mainClass="com.seu.pacote.Main"
   ```
   *(Ou abra o projeto diretamente no **IntelliJ IDEA**, **Eclipse** ou **VS Code** e execute a classe principal `Main`).*

---

## 👥 Autores

* **Gabriel Passos** - [GitHub](https://github.com/GabrielPassos-Dev)
* **Lucas Nascimento** - [GitHub](https://github.com/lucasns7)
* **Daniel Behrensdorf** - [GitHub](https://github.com/DanielBehrensdorfMello)
