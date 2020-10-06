
# Jogo do Nim


![Botão de Versão](https://img.shields.io/badge/Version-1.0-blue)
 
No Jogo do NIM,  **n**  peças são inicialmente dispostas numa mesa ou tabuleiro. Dois jogadores jogam alternadamente, retirando pelo menos 1 e no máximo  **m**  peças cada um. Quem tirar as últimas peças possíveis ganha o jogo.

![ScreenShot do jogo do Nim](https://github.com/joao-lucasilva/Jogo-do-Nim/blob/master/assets/screenshot.JPG)

Tabela de conteúdos
=================
   * [Sobre](#sobre)
   * [Como funciona](#como-funciona)
   * [Como usar](#como-usar)
   * [Tecnologias](#tecnologias)
   * [Autores](#autores)
 
## Sobre
O programa permite um usuário jogar o NIM contra o computador. Com  **n**  sendo o número de peças inicial e  **m**  o número máximo de peças que é possível retirar em uma rodada. 

Existe uma estratégia para ganhar o jogo que é muito simples: ela consiste em deixar sempre múltiplos de  **(m+1)**  peças ao jogador oponente.
 
Uma vez iniciado o jogo, o computador seguira a estratégia descrita acima para ganhar, que consiste em deixar sempre um número de peças que seja múltiplo de  **(m+1)**  ao jogador. Caso isso não seja possível, o computador irá retirar o número máximo de peças possíveis.
## Como Funciona
-  A função  computador_escolhe_jogada  recebe, os números  **n**  e  **m**  o valor correspondente à próxima jogada do computador de acordo com a estratégia vencedora.
-   A função  usuario_escolhe_jogada recebe os mesmos parâmetros, solicita que o jogador informe sua jogada e verifica se o valor informado é válido. 
-   A função  partida solicita ao usuário que informe os valores de  **n**  e  **m**  e inicia o jogo, alternando entre jogadas do computador e do usuário.
- A função campeonato realiza três partidas seguidas do jogo e, ao final, mostra o placar dessas três partidas e indicar o vencedor do campeonato.
## Como Usar
Faça o download do zip ou clone este repositório:
> git clone https://github.com/joao-lucasilva/Jogo-do-Nim

Execute o arquivo jogo_nim.py em seu ambiente Python. 

## Tecnologias
Neste projeto foi utilizado:
	* [Python3](https://www.python.org/);

## Autor
Desenvolvido por João Lucas da Silvano Curso Introdução a Ciência da Computação com Python da USP.
Entre em contato comigo:
 [![Linkedin Badge](https://img.shields.io/badge/-JoaoLucas-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/tgmarinho/)]([https://www.linkedin.com/in/joaolucassilva-812819165/](https://www.linkedin.com/in/joaolucassilva-812819165/)) | [![Gmail Badge](https://img.shields.io/badge/-joao.lsilva1198@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:tgmarinho@gmail.com)](mailto:joao.lsilva1198@gmail.com)
