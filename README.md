# Teste fullstack

O objetivo deste desafio é avaliar o domínio do candidato no desenvolvimento fullstack. Será avaliado boas práticas de code style, organização do projeto, criação de APIs, conhecimento de frameworks e tecnologias.

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) e envie um email com o título `[Teste Fullstack] Finalizado` junto com sua pretensão salarial para contato@wi-id.com

## Missão backend

Desenvolver uma **API JSON RESTful** em **Laravel PHP** ou **Node framework a sua escolha**, que utilize todos os métodos (`GET`, `POST`, `PUT`, `PATCH`, `DELETE`).  

### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
updated:   datetime
```

Utilize **MySQL** ou **PostgreSQL** para armazenar os dados que a **API** irá consumir.

### API endpoints

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos/find`

Retorna os veículos de acordo com o termo passado parâmetro `like`

---

`GET /veiculos/{id}`

Retorna os detalhes do veículo

---

`POST /veiculos`

Adiciona um novo veículo

---

`PUT /veiculos/{id}`

Atualiza os dados de um veículo

---

`PATCH /veiculos/{id}`

Atualiza apenas alguns dados do veículo

---

`DELETE /veiculos/{id}`

Apaga o veículo


## Missão frontend

Desenvolver uma **UI (User Interface)** de acordo com o desenho que está na pasta [layout](https://github.com/workinideas/teste-fullstack/tree/main/layout)

### Especificação
- Faça Interface utilizado ReactJS ou VueJS (Bônus :star:)
- Consumir **API** criada acima
- Criar uma tela que tenha...
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos

### Dica

Utilize algum framework para auxiliar no desenvolvimento da interface, por exemplo:

- https://getmdl.io/
- http://getbootstrap.com/
- https://vuematerial.io/
- https://bootstrap-vue.org/
- https://material-ui.com/pt/
- https://react-bootstrap.github.io/

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Fullstack] O assunto que vc deseja` para contato@wi-id.com
