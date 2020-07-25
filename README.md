# murilopf-frm-mvc-restapi

# Rotas disponíveis

    | GET|HEAD  | api/pets         | pets.index       
    | POST      | api/pets         | pets.store     
    | GET|HEAD  | api/pets/{pet}   | pets.show        

    | GET|HEAD  | api/users        | users.index     
    | POST      | api/users        | users.store      
    | GET|HEAD  | api/users/{user} | users.show     

# Exemplos de post para pet e dono

### Dono/Usuário

{
	"name": "Murilo",
	"cep": "17450000",
	"number": "331"
}


### Pet

{
	"name": "Dara",
	"description": "",
	"age": "12",
	"user_id": 1
}

OBS: Para criar um pet, é necessário possuir ao menos um Dono/Usuário criado.



