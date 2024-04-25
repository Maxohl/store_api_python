# TDD Project

## O que é TDD?
TDD é uma sigla para `Test Driven Development`, ou Desenvolvimento Orientado a Testes. A ideia do TDD é que você trabalhe em ciclos.

## Desafio 
Aprender na prática a implementação do TDD em uma aplicação utilizando FastAPI e o Pytest.

Detalhes do desafio:

 - Utilização do banco de dados Mongo.
 - Testes de CRUD na coleção "products".
 - Testes de Exceção (ID não existe).
 - Mapeamento de exceção caso dê algum erro de inserção e capturar na controller.
 - Método Patch foi modificado para retornar uma exceção de Not Found, quando o dado não é encontrado.
 - Quando um dado é alterado, o campo updated_at é atualizado com a data e horas atuais.
 - Aplica um filtro de preço, se não houver nenhum produto entre os preços 5000 e 8000, trata o erro.

## Preparar ambiente

Vamos utilizar Pyenv + Poetry, link de como preparar o ambiente abaixo:

[poetry-documentation](https://github.com/nayannanara/poetry-documentation/blob/master/poetry-documentation.md)

## Links uteis de documentação
[mermaid](https://mermaid.js.org/)

[pydantic](https://docs.pydantic.dev/dev/)

[validatores-pydantic](https://docs.pydantic.dev/latest/concepts/validators/)

[model-serializer](https://docs.pydantic.dev/dev/api/functional_serializers/#pydantic.functional_serializers.model_serializer)

[mongo-motor](https://motor.readthedocs.io/en/stable/)

[pytest](https://docs.pytest.org/en/7.4.x/)
