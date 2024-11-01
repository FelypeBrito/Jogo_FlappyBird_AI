
# 🐦 Flappy Bird AI 🧠

Este projeto é uma implementação do clássico jogo Flappy Bird com uma IA usando a biblioteca **NEAT** e **Pygame** para treinar e testar o desempenho de uma rede neural que controla o pássaro. Quando habilitada, a IA aprende a jogar o Flappy Bird ajustando suas decisões conforme avança no jogo! 

## 📂 Estrutura do Projeto
- **config.txt**: Arquivo de configuração para o algoritmo NEAT.
- **main.py**: Código principal do jogo, onde toda a lógica e funcionalidades do Flappy Bird com IA estão implementadas.

## 🚀 Como Instalar e Executar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/FelypeBrito/Jogo_FlappyBird_AI
   cd Jogo_FlappyBird_AI
   ```

2. **Instale as dependências**:
   Certifique-se de ter o **Python** instalado. É recomendável usar um ambiente virtual.
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # ou .venv\Scripts\activate no Windows
   pip install -r requirements.txt
   ```

3. **Execute o jogo**:
   ```bash
   python FlappyBird.py
   ```

## 🎮 Modo de Jogo

- **Modo IA**: Por padrão, a IA controla o pássaro e aprende automaticamente com o NEAT.
- **Modo Manual**: Desative o modo IA (defina `ai_jogando = False`) para controlar o pássaro usando a barra de espaço.

## 🛠️ Funcionalidades
- **Movimento do Pássaro**: Ajusta a velocidade e ângulo conforme o pássaro se movimenta na tela.
- **Detecção de Colisão**: Verifica colisões entre o pássaro e os canos.
- **Algoritmo NEAT**: Treina o pássaro a cada geração, aumentando sua **fitness** conforme sobrevive.

## 📈 Treinamento e Aprendizagem da IA
A IA ajusta seus movimentos com base no desempenho. Pontuações são atribuídas conforme o pássaro progride no jogo, e a geração é automaticamente ajustada a cada nova execução.

## 📑 Referências
- [NEAT-Python Documentation](https://neat-python.readthedocs.io/en/latest/)
