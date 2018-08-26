dicionario={'nome':"lucas",'telefone':"112212",'email':"lucas@" }
#exercicio1
class contato:
    def __init__(self,_nome,_telefone,_email):
        self.nome=_nome
        self.telefone=_telefone
        self.email=_email
    
    def imprime(self): 
        return('suas informaçoes sao:==>nome:{}--telefone:{}--email:{}').format(self.nome,self.telefone,self.email)

    def reset(self):
        self.nome=None
        self.telefone=None
        self.email=None

chama=contato(dicionario['nome'], dicionario['telefone'], dicionario['email'])
print(chama.imprime())


#exercicio2
def def conta_elementos(dicionario):
    return len(dicionario)
print(dicionario2(dicionario))
#exercicio3
def dicionario (dicionario,chave):
    if chave in dicionario 
        return true
    return false
    print(verifica_presenca(dicionario,'Marcos')) 
#exercicio4
def insere (dicionario,chave,objeto):
    if chave not in dicionario and objeto not in dicionario:
        dicionario[chave]=objeto
        print(dicionario)
        return True
    return False 
print(insere(dicionario,'Marcos','100'))
