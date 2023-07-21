# Exercicio077.py

palavra = ('python','java','beckand',
           'frontand','linux','windons'
           'joao','maria','persefhone')
for p in palavra:
    print(f'\nNa palavra {p.upper()} temos ',end='')
    for letra in p:
        if letra.lower() in 'aeiou':
            print(letra,end=' ')
