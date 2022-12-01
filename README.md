
### Oie devs 👋

Sou Ingrid, e estou inciando no mundo de programação.

<img align="right" width="300" src="https://i2.wp.com/allhtaccess.info/wp-content/uploads/2018/03/programming.gif?fit=1281%2C716&ssl=1" />

```python
    def test_tarefa():
    cliente = TestClient(app)
    tarefa_esperada = {"titulo": "titulo", "descricao": "descricao"}
    resposta = cliente.post("/tarefas", json=tarefa_esperada)
    tarefa_criada = resposta.json()
    assert tarefa_criada["titulo"] == tarefa_esperada["titulo"]
    assert tarefa_criada["descricao"] == tarefa_esperada["descricao"]
    TAREFAS.clear()

