# Descobrir-idade
#Informações pessoais
nome = "Matheus"
ano  = 2007
mes  = 9
dia  = 25

#Dados atuais
ano_atual = 2024
mes_atual = 10
dia_atual = 25
mes3 = ...
 
#Meses do ano
if  mes  == 1:
    soma_idade = (ano_atual - 0)   - ano
    mes3 = "janeiro"
  
elif mes == 2:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Fevereiro"
   
elif mes == 3:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Março"
   
elif mes == 4:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Abril"

elif mes == 5:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Maio"
    
elif mes == 6:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Julho"
   
elif mes == 7:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Junho"
    
elif mes == 8:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Agosto"
    
elif mes == 9:
    soma_idade = (ano_atual - 0) - ano
    mes3 = "Setembro"
    
elif mes == 10:
    soma_idade = (ano_atual - 1) - ano
    mes3 = "Outubro"

elif mes == 11:
    soma_idade = (ano_atual - 1) - ano
    mes3 = "Novembro"
    
elif mes == 12:
    soma_idade = (ano_atual - 1) - ano
    mes3 = "Dezembro"
    
else:
    print("Essa mês não existe");

#informacão das variaveis   
informacao = f"Seu nome é {nome}, nasceu no ano de {ano}, no mês {mes3}, no dia {dia}, e voce tem {soma_idade} anos\n"

print(informacao)
