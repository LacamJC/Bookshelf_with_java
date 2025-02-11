# 📚 Bookshelf_with_java

Projeto em **Java** para a criação de um sistema de gerenciamento de bibliotecas.

## 📂 Estrutura do Projeto
```plaintext 
   lacamjc-bookshelf_with_java/
   ├── README.md
   ├── META-INF/
   │   └── MANIFEST.MF
   └── src/
   ├── Main.java
   ├── models/
   │   ├── Biblioteca.java
   │   ├── Controller.java
   │   └── Livro.java
   └── out/
   ├── artifacts/
   │   └── bookshelf_with_java_jar/
   │       └── livrosAll.json
   └── production/
   └── bookshelf_with_java/
   ├── README.md
   ├── livrosAll.json
   ├── .gitignore
   └── META-INF/
   └── MANIFEST.MF
```


## 🚀 O que é este projeto?

Este é um sistema básico para gerenciar livros em uma biblioteca. Ele permite visualizar informações sobre os livros cadastrados, filtrá-los por categoria ou autor e exibir estatísticas da biblioteca.

## ▶️ Como Rodar

Este projeto inclui um executável em Java para você poder testar.

Certifique-se de ter o Java Runtime Environment (JRE) instalado para executar o .jar.

1. Acesse a pasta `artifacts` dentro de `src/out/artifacts`.
2. Abra o terminal dentro dela.
3. Execute o seguinte comando para iniciar o projeto:
   ```sh
   java -jar bookshelf_with_java.jar
   ```

## 🛠️ Como usar para alterações

### Pré-requisitos:
- Java instalado (JDK 8 ou superior)
- Um terminal ou IDE para execução do código

### Executando o projeto:
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/lacamjc-bookshelf_with_java.git
   ```
2. Acesse o diretório do projeto:
   ```sh
   cd lacamjc-bookshelf_with_java
   ```
3. Compile os arquivos Java:
   ```sh
   javac -d bin src/models/*.java src/Main.java
   ```
4. Execute o programa:
   ```sh
   java -cp bin Main
   ```

## ✨ Funcionalidades
- 📖 Cadastrar e visualizar livros na biblioteca
- 🔍 Filtrar livros por **categoria**
- 🖊️ Buscar livros por **autor**
- 📊 Exibir estatísticas gerais da biblioteca

## 📜 Licença
Este projeto está sob a licença **MIT**. Você pode usá-lo, modificá-lo e distribuí-lo livremente.

---

Feito por [LacamJC](https://github.com/LacamJC) 

