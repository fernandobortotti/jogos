# nome: jokenpo
# versão: 1.0
# autor: Fernando Bortotti
# email: fernandobortotti@gmail.com
#****************Descrição do jogo:**************************
# esse é um programa simples de jokenpo, o usuário escolhe  *
# [0] para pedra                                            *
# [1] tesoura.                                              *
# [2] para papel                                            *
# para jogar contra o pc                                    *
#************************************************************
# 

import random
numero_aleatorio = random.randint(0,2)
jogador = int(input("Digite 0 para pedra. Digite 1 tesoura. Digite 2 para papel"))

if jogador != numero_aleatorio:
    if jogador == 2:
        if (jogador - 1 == numero_aleatorio):
            print("Você perdeu")
        else:
            print("Você ganhou")
    elif (jogador + 1 <= 2):
        if (jogador + 1 == numero_aleatorio):
            print("Você ganhou")
        else:
            print("Você perdeu")
    
else:
    print("Empatou")
