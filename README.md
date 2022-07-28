# Desenvolva-um-c-digo-que-utilize-as-seguintes-caracter-sticas-de-um-ve-culo-
rodas  =  int ( input ( 'Quantas rodas tem o veículo?' ))
peso  =  float ( input ( 'Qual o peso do veiculo?' ))
capacidade_pessoas  =  int ( input ( 'Qual a capacidade de pessoas?' ))

se  rodas  ==  2  ou  rodas  == 3 :
    print ( 'O veículo é categoria A' )

elif  rodas  ==  4  e  peso  <=  3500  e  capacidade_pessoas  <= 8 :
    print ( 'O veículo é categoria B' )

elif  rodas  >=  4  e  capacidade_pessoas  > 8 :
    print ( 'O veículo é de classe D' )

elif  rodas  >= 4  e  peso  >  6000 :
    print ( 'O veículo é de classe E' )

elif  rodas  >=  4  e ( peso  >=  3500  <=  6000 ):
    print ( 'O veículo é de classe C' )

mais :
    print ( 'Veículo não é de nenhuma categoria' )
