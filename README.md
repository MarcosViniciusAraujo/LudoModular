# Projeto Ludo - Grupo 6 - INF1301
Daniel Guimarães    
Henrique Soares    
João Vitor Santana    
Marcos Vinicius Araujo

----
## Build 4 - 16/11
### Entrega estabelecida
* Jogo completo

### Conteudos da Build
* Jogo completo e funcionando

----
### Requerimentos
* [**Python 3**](https://python.org) 

* [**Pygame**](https://www.pygame.org/wiki/GettingStarted) Com o Python instalado, é possivel instalar o PyGame através do comando:
`pip install pygame` ou `python -m pip install pygame`
* [**MySQL**](https://dev.mysql.com/downloads/installer/) e [**Connector**](https://dev.mysql.com/downloads/connector/python/):
Durante a instalação do MySQL, é possível instalar o Connector direto no instalador, ou instalado posteriormente
  através do comando `pip install mysql-connector` ou `python -m pip install mysql-connector`. Além disso, será necessário anotar o usuário
  e senha que foi cadastrado durante a instalação.

Os demais módulos utilizados já estão instalados na distribuição padrão do Python: 
**xml**, **json**, **os**, **tkinter**, **random**, **datetime**, **unittest** e **time**.

----
### Como jogar
Para iniciar o jogo, é preciso executar o arquivo `main.py`

Ao executar o programa, ele abrirá uma tela de menu. Nesta tela, é possível criar uma partida de dois a quatro jogadores ou carregar uma partida anterior.
 Também é possível configurar a conexão com a base de dados, essencial ao funcionamento do jogo. Para isso, é necessário acessar a tela de configuração, que permite
 configurar o usuário, senha e servidor de conexão com a base de dados.

Ao iniciar ou carregar uma partida, a tela de menu será fechada, e abrirá uma tela com o jogo. As cores dos jogadores são pré-selecionadas.

Durante o jogo, é possível desabilitar os efeitos sonoros, assim como a música, através dos botões a esquerda.

Para interagir no jogo, é preciso utilizar o mouse para selecionar qual peão mover, ou para jogar o dado.

O jogo pode ser interrompido em qualquer momento ao fechar a tela de jogo. Ele poderá ser recuperado a partir da última rodada jogada.

Ao finalizar uma partida, será exibido o placar dos vencedores, e o jogo será fechado automaticamente.

----
### Testes
O arquivo de testes está em `testes/teste.py`. Ao executar, ele fará todos os testes dos jogos automaticamente.

----
### Créditos
* **Música**: *Glass House - UTAH*
* **Efeitos sonoros**: *Chess.com*
* **Imagens**: *Feitos por Daniel e Marcos, através do programa **Inkscape***
* **Logo**: *Feito por Henrique*
