# Recebe a entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um conceito e retornar sua respectiva descrição.
def descrever_conceito(conceito):
  if conceito == "ls":
    return "Lista o conteúdo do diretório atual"
  
  # Preenchendo os outros comandos conforme descrito na entrada
  elif conceito == "mkdir":
    return "Cria um novo diretório"
  
  elif conceito == "rm":
    return "Remove um arquivo ou diretório"
  
  elif conceito == "cd":
    return "Navega para outro diretório"

# Imprime a descrição do conceito recebido na "entrada" através da função "descrever_conceito". 
print(descrever_conceito(entrada))
