# joga-moeda
Cara ou Coroa?


# Pedra, papel, tesoura
Para mudar o programa para pedra, papel, tesoura:
    
    from random import random


    def ppt():
        if random() <= 0.3:
            return 'Pedra'
        elif random() > 0.3 or random() == 0.6:
            return 'Papel'
        return 'Tesoura'


    print(ppt())
    
