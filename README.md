# 🧟 Zombie Survival CSS

Um jogo de sobrevivência simples e divertido criado **exclusivamente** com HTML e CSS. Este projeto foi desenvolvido para demonstrar o poder dos seletores CSS e a lógica de "checkbox hack" para criar interatividade sem JavaScript.

## 🎮 Como Jogar
1. Clona este repositório ou descarrega os ficheiros.
2. Abre o ficheiro `index.html` em qualquer navegador moderno.
3. O objetivo é clicar em todos os zumbis que aparecem no ecrã antes que eles desapareçam.
4. Quando eliminares todos, a mensagem de vitória aparecerá!

## 🚀 Tecnologias Utilizadas
- **HTML5**: Estruturação dos elementos e dos checkboxes.
- **CSS3**: Animações (`@keyframes`), posicionamento e lógica de estados (`:checked`).

## 🧠 Como Funciona? (A "Magia" do CSS)
O jogo não utiliza JavaScript para detetar os cliques. Em vez disso, utiliza uma técnica chamada **Checkbox Hack**:
- Cada zumbi é um `label` associado a um `input type="checkbox"`.
- Quando clicas no zumbi, o checkbox fica marcado.
- Através do seletor CSS `input:checked + .zumbi`, escondemos o zumbi que foi clicado.
- Usamos seletores combinados para verificar se todos os checkboxes estão ativos e exibir a mensagem final.

## 📸 Demonstração
![Screenshot do Jogo](caminho-para-uma-imagem-ou-gif.gif)

## 🛠️ Possíveis Melhorias
- [ ] Adicionar mais níveis com velocidades diferentes.
- [ ] Criar um cenário de fundo mais detalhado.
- [ ] Adicionar efeitos sonoros (exigiria um pouco de JS).

## ✒️ Autor
* **O Teu Nome** - [Teu GitHub](https://github.com/teu-utilizador)
