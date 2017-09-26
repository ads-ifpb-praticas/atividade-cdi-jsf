# Atividade Prática - Injeção de Dependências e Contextos/Programação Baseada em Eventos

A atividade prática para os módulos de Injeção de Dependência e Contextos e Programação Baseada em Eventos consiste em implementar um sistema de catalogação de produtos simples. Os requisitos do sistema serão descritos abaixo.

- O sistema deve cadastrar produtos dentro de categorias e contendo os seguintes atributos: Nome, Nº de Identificação (pode ser gerado automaticamente), Foto, Descrição, Preço unitário, Marca.
	- A marca deve ser inserida em um campo em branco. Porém, ao cadastrar um produto em uma determinada marcada, a mesma deve estar disponível para ser sugerida nos próximos produtos (em uma espécie de auto-complete)
	- As categorias podem ser cadastradas previamente ou no momento do cadastro de um produto. Do mesmo modo da marca, também deve ser sugerido uma das categorias cadastradas previamente.
- O sistema deve ter uma página para exibir todos os produtos cadastrados e ter os seguintes filtros:
	- Filtro por categoria
	- Filtro por faixa de preço (min-máx)

## Requisitos técnicos

A atividade deve ser desenvolvida utilizando as tecnologias vistas em sala de aula (CDI e JSF). Nem todos os requisitos desta atividade estão contemplados nos exemplos vistos em sala ou submetidos ao Github, sendo assim, é necessário pesquisar e compreender como implementar estes aspectos.

## Data de Entrega

A atividade deve ser submetida a um repositório na organização da disciplina no Github, com o nome "atividade-cdi-jsf-<nome>", onde <nome> deve ser o nome do aluno que desenvolveu a atividade. O prazo máximo é 10/10/2017.
