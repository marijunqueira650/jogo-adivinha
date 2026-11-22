# 🎯 Jogo: Adivinhe o Número

Um jogo simples no navegador em que a CPU sorteia um número entre **1 e 100** e você tenta adivinhar qual é.

🔗 **Jogue agora:** [marijunqueira650.github.io/jogo-adivinha](https://marijunqueira650.github.io/jogo-adivinha/)

---

## 📖 Como jogar

1. A CPU sorteia um número secreto entre 1 e 100.
2. Digite seu palpite no campo de texto.
3. Clique em **Enviar** (ou pressione **Enter**).
4. O jogo informa se o seu palpite está acima ou abaixo do número secreto.
5. Continue tentando até acertar. O contador mostra quantas tentativas você já fez.

## 🕹️ Controles

| Botão | O que faz |
|-------|-----------|
| **Enviar** | Confirma o palpite digitado (também funciona com Enter) |
| **Limpar** | Limpa o campo de entrada |
| **Novo jogo** | Sorteia um novo número e zera as tentativas |
| **Revelar número** | Mostra o número secreto |

Depois de acertar, é possível jogar outra partida clicando em **Jogar novamente** ou **Novo jogo**.

## ✨ Funcionalidades

- Número secreto gerado aleatoriamente a cada partida
- Contador de tentativas
- Dicas a cada palpite
- Suporte ao teclado (Enter para enviar)
- Opção de revelar o número
- Várias partidas seguidas, sem recarregar a página
- Layout responsivo, que funciona em celular e computador

## 🛠️ Tecnologias

- HTML5
- CSS3
- JavaScript (puro, sem bibliotecas ou frameworks)

## 📁 Estrutura do projeto

O projeto é composto por um único arquivo, que reúne HTML, CSS e JavaScript:

```
jogo-adivinha/
├── index.html   (HTML, CSS e JavaScript em um único arquivo)
└── README.md
```

## 💻 Como executar localmente

```bash
# Clone o repositório
git clone https://github.com/marijunqueira650/jogo-adivinha.git

# Entre na pasta
cd jogo-adivinha

# Abra o arquivo index.html no navegador
```

Não é necessário instalar nada: basta abrir o `index.html` em qualquer navegador moderno.

## 🚀 Ideias para o futuro

- [ ] Escolher o nível de dificuldade (intervalo maior ou menor)
- [ ] Limite de tentativas
- [ ] Ranking com as melhores pontuações
- [ ] Modo escuro
- [ ] Separar o código em `style.css` e `script.js`

## 👩‍💻 Autora

Feito por [@marijunqueira650](https://github.com/marijunqueira650).

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
