# Projeto de Compiladores 💻⚙️

Bem-vindo! Este repositório contém o código-fonte desenvolvido para a disciplina de Compiladores. O objetivo principal deste projeto é a construção, passo a passo, de um compilador completo ao longo do semestre.

## 🛠️ Tecnologias Utilizadas
* **Linguagem:** Java

## 📂 Fases do Compilador

O desenvolvimento do compilador está sendo dividido em módulos correspondentes a cada fase do processo de compilação. Abaixo está o acompanhamento do progresso:

- [x] **Analisador Léxico:** Lê o código-fonte (caractere a caractere) e o converte em uma sequência de *tokens* válidos para a linguagem. *(Ver pasta `Analisador Lexico`)*
- [ ] **Analisador Sintático:** Recebe os tokens e verifica se eles formam expressões válidas de acordo com a gramática da linguagem (gerando a Árvore de Sintaxe Abstrata - AST).
- [ ] **Analisador Semântico:** Verifica a consistência semântica do código, como checagem de tipos, escopo de variáveis e declarações prévias.
- [ ] **Geração de Código Intermediário / Final:** Tradução do código validado e otimizado para a linguagem alvo ou código de máquina.

## 🚀 Como executar

Como o projeto é desenvolvido em Java, certifique-se de ter o [JDK (Java Development Kit)](https://www.oracle.com/java/technologies/downloads/) instalado na sua máquina.

1. Clone este repositório:
   ```bash
   git clone [https://github.com/Marolowp/Projeto-de-Compiladores.git](https://github.com/Marolowp/Projeto-de-Compiladores.git)

👨‍💻 Autor
Marcos Cardoso - @Marolowp