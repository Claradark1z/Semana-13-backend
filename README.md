# Semana-13-backend
# main.py
from fastapi import FastAPI
app = FastAPI()

tarefas = [{"titulo": "Dar aula de backend",
            "descicao": "semana 13 aula 2"}]

@app.get("/tarefa/{id_tarefa}")
async def ListarTarefaPorID(id_tarefa):
    return tarefas in tarefas
if tarefa ["id_tarefa"]== id_tarefa:


@app.get("/tarefas")
async def root():
    return tarefas

@app.post("tarefa")
def CadastrarTarefa(titulo,descricao):
    tarefas.append({"titulo" : titulo, "descricao" : descricao})
    
    # @app.delete ("/tarefa")
    # def DeletarTarefa(titulo):
