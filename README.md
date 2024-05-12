# Projeto
def aventura():
    print("Você está em uma densa floresta. À sua esquerda, você vê uma trilha estreita e sinuosa. À sua direita, avista uma caverna escura.")
    escolha = input("Você quer seguir pela trilha (T) ou entrar na caverna (C)? ").upper()
    
    if escolha == "T":
        print("Você segue pela trilha e encontra uma antiga cabana. Dentro dela, você descobre um mapa do tesouro!")
    elif escolha == "C":
        print("Você entra na caverna e encontra um dragão adormecido. Por sorte, você consegue escapar ileso.")
    else:
        print("Escolha inválida. Tente novamente.")
        aventura()

aventura()
