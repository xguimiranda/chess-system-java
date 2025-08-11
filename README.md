# ♟️ Sistema de Jogo de Xadrez em Java

Este é um jogo de xadrez em console desenvolvido em Java, criado como projeto prático para aplicar os conceitos de **Programação Orientada a Objetos (POO)** aprendidos ao longo do curso “Java OOP” (Prof. Nélio Alves).  
O objetivo principal do projeto é consolidar conhecimentos sobre POO, tratamento de exceções, estruturas de dados e práticas de código limpo construindo um jogo de xadrez totalmente funcional que roda no terminal.

---

## 🚀 Funcionalidades

- ✅ Jogo completo de xadrez jogável no terminal  
- ✅ Regras implementadas, incluindo:
  - ✔️ Xeque  
  - ✔️ Xeque-mate  
  - ✔️ Roque (pequeno e grande)  
  - ✔️ En passant  
  - ✔️ Promoção de peão  
- ✅ Controle de turnos alternando jogadores  
- ✅ Visualização do tabuleiro com distinção de peças brancas/pretas  
- ✅ Exibição dos movimentos possíveis da peça selecionada  
- ✅ Registro de peças capturadas  
- ✅ Programação defensiva com exceções personalizadas  
- ✅ Limpa a tela entre os turnos para melhor experiência  

---

## 🏗️ Design Orientado a Objetos

### ✔️ Conceitos Aplicados:
- Classes e Objetos  
- Encapsulamento  
- Herança  
- Polimorfismo  
- Abstração (classes e métodos abstratos)  
- Tratamento de exceções (exceções personalizadas)  
- Arquitetura em camadas (UI, camada de xadrez, camada de tabuleiro)

---

## 🎯 Visão Geral das Classes

### 📄 Pacote **boardgame**
- `Position`: Representa coordenadas do tabuleiro (linha e coluna)  
- `Board`: Gerencia peças, posições e regras de uso do tabuleiro  
- `Piece`: Superclasse genérica de peça  
- `BoardException`: Exceções para operações inválidas relacionadas ao tabuleiro  

### ♟️ Pacote **chess**
- `ChessMatch`: Classe principal que controla a lógica e o fluxo do jogo  
- `ChessPiece`: Extende `Piece` com comportamento específico de xadrez  
- `ChessPosition`: Converte entre notação de xadrez (ex.: e4) e posição matricial  
- `ChessException`: Exceções específicas do domínio de xadrez  

#### Peças Implementadas
- `King` (inclui lógica de roque)  
- `Queen`  
- `Rook`  
- `Bishop`  
- `Knight`  
- `Pawn` (com promoção e en passant)  

---

## 🖥️ Como Executar

### ✔️ Pré-requisitos
- Java JDK 11 ou superior  
- IDE (IntelliJ / Eclipse / NetBeans) ou apenas terminal com Java configurado  

### ✔️ Passos
1. Clonar o repositório:
   ```bash
   git clone https://github.com/xguimiranda/chess-system-java.git
   ```
2. Entrar na pasta:
   ```bash
   cd chess-system-java
   ```
3. Compilar:
   (exemplo simples – ajuste conforme estrutura real)
   ```bash
   javac -classpath src -d bin $(find src -name "*.java")
   ```
4. Executar:
   ```bash
   java -cp bin application.Program
   ```

---

## 🎨 Cores no Terminal

- Peças brancas → letras maiúsculas  
- Peças pretas → letras minúsculas (podem aparecer com cor distinta dependendo do terminal)

> Observação: Em alguns terminais Windows antigos as cores podem não aparecer corretamente. Use Git Bash ou Windows Terminal / Linux / macOS para melhor resultado.

---

## 🚧 Regras Implementadas

| Regra                | Status |
|----------------------|--------|
| Validação de movimentos | ✅ |
| Turnos e jogadores      | ✅ |
| Detecção de xeque       | ✅ |
| Detecção de xeque-mate  | ✅ |
| Roque                   | ✅ |
| En passant              | ✅ |
| Promoção                | ✅ |
| Exibição de capturas    | ✅ |

---

## 📚 Conceitos Abrangidos

- ✅ POO (Encapsulamento, Herança, Polimorfismo, Abstração)  
- ✅ Tratamento de Exceções (BoardException, ChessException)  
- ✅ Programação Defensiva  
- ✅ Estruturas de Dados (Matriz, Listas)  
- ✅ Princípios de Código Limpo  
- ✅ Arquitetura em Camadas  

---

## ⚠️ Aviso

Projeto desenvolvido para fins educacionais como parte do curso de Programação Orientada a Objetos em Java (Prof. Nélio Alves). Roda totalmente em console e prioriza a aplicação de conceitos de programação em vez de interface gráfica.

---
