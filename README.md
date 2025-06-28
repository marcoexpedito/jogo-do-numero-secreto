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

2. Acesse a pasta do projeto:

bash
Copiar
Editar
cd jogo-do-numero-secreto
Abra o arquivo index.html no seu navegador. É importante permitir o uso do microfone quando solicitado.

🎯 Objetivos de aprendizado
Estudar Web Speech API e aplicar reconhecimento de voz em aplicativos web;

Aprender criar lógica de validação e interação com o usuário usando JavaScript;

Praticar boas práticas de desenvolvimento e interface simples e intuitiva.

💡 Possíveis melhorias
🌐 Compatibilidade com navegadores que não suportam a Web Speech API (com fallback de entrada manual);

💬 Suporte a múltiplos idiomas, tornando o jogo acessível internacionalmente;

🧩 Design responsivo mais refinado para diversos tamanhos de tela;

🏆 Pontuação / leaderboard: acompanhar o número de tentativas;

🔊 Adicionar feedback de voz usando sintetizadores de fala (Speech Synthesis API).

🤝 Contribuições
Contribuições são bem-vindas! Se tiver sugestões, correções ou quiser adicionar algo novo, siga estes passos:

Faça um fork do projeto.

Crie uma branch com sua feature ou correção:
git checkout -b feature/meu-recurso

Realize as alterações e commit:
git commit -m "Adiciona recurso X"

Envie para a origin:
git push origin feature/meu-recurso

Abra um Pull Request explicando seu propósito.

👨‍💻 Sobre o autor
Marco Expedito

Desenvolvedor entusiasta de front-end e APIs web.

⚖ Licença
Este projeto está sob a licença MIT — sinta-se à vontade para usar, modificar e compartilhar.

Boa adivinhação — e divirta-se treinando reconhecimento de voz! 🎉
