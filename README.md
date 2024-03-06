# curso-python
import os

def finalizar_app():
    os.system('cls')  # Use 'clear' for Mac/Linux
    print('Finalizando o app\n')

def cadastrar_restaurante():
    # Lógica para cadastrar restaurante
    print('Cadastrando restaurante...')

def opcao_um():
    # Lógica para a opção 1
    print('Opção 1 selecionada.')

def opcao_dois():
    # Lógica para a opção 2
    print('Opção 2 selecionada.')

def opcao_tres():
    # Lógica para a opção 3
    print('Opção 3 selecionada.')

def main():
    while True:
        print('1 - Opção 1')
        print('2 - Opção 2')
        print('3 - Opção 3')
        print('4 - Sair')

        opcao_escolhida = input('Escolha uma opção: ')

        if opcao_escolhida == '1':
            opcao_um()
        elif opcao_escolhida == '2':
            opcao_dois()
        elif opcao_escolhida == '3':
            opcao_tres()
        elif opcao_escolhida == '4':
            finalizar_app()
            break
        else:
            print('Opção inválida. Tente novamente.')

if __name__ == "__main__":
    main()
