# 🕵‍♂ Jogo do Número Secreto (Reconhecimento de Voz)

Um jogo interativo em *JavaScript* que desafia você a adivinhar um número secreto entre 0 e 1000 usando *reconhecimento de voz*, com dicas visuais para orientar seus chutes.

---

## 🧠 Como funciona

1. Ao carregar a página, a aplicação gera aleatoriamente um número entre *0 e 1000*.
2. O reconhecimento de voz é ativado automaticamente — o navegador solicitará permissão para usar o microfone.
3. Você fala um número (em voz alta) e, se for um número válido:
   - O jogo confirma se você acertou;
   - Se não acertar, mostra se seu chute foi *maior* ou *menor*;
   - Em seguida, você pode tentar novamente.
4. Quando você acertar:
   - A interface celebra o acerto;
   - Um botão surge para você reiniciar e jogar novamente.

---

## 🛠 Tecnologias utilizadas

- *HTML5* – estrutura da página  
- *CSS3* – estilização responsiva e visual agradável  
- *JavaScript (vanilla)* – lógica do jogo  
- *Web Speech API* – reconhecimento de voz embutido nos navegadores modernos

---

## 🚀 Como executar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/marcoexpedito/jogo-do-numero-secreto.git
