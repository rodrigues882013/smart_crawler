# Considerações

O desafio foi feito em duas branchs, em uma está simplesmente a tarefa de conversão parse do xml (master), já a outra branch reune
as features de extras (webservice). 

Para o extra foi implementado um microserviço em flask, esse texto exemplifica como executar e testar o webservice  


## Requerimentos

    python 3.5

## Instalação
Primeiro crie um ambiente virtual e ative-o

    python3 -m venv .env
    source .env/bin/active
    
    
Instale as dependencias
    
    pip install -r requirements.txt
   
Rode o programa

    python3 main.py
        
## Testes
Execute os testes unitários

    python3 -m unittest