#   Exercício 06
n = float(input('Informe um valor qualquer: '))
if (n % 2) == 0:
    s = n + 5
    print('o valor é par, por isso, somamos 5, a soma é: ', round(s,2))
elif (n % 2) == 1:
    s = n + 8
    print('o valor é impar, por isso, somamos 8, a soma é: ', round(s,2))
