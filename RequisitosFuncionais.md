| ID   | Requisito | Descrição                                      | Entrada                                                | Resultado Esperado                           |
|:----:|:---------:|:----------------------------------------------:|:------------------------------------------------------:|:------------------------------:              |
| CT01 | RF01      | Cadastro de Usuário sem preencher o campo nome | email, senha, data de nascimento válidos -> falta nome | Sistema deve impedir o cadastro              |
| CT02 | RF02      | Cadastrar usuário com id duplicado             | id ja existente                                        | Sistema deve impedir cadastro                |
| CT03 | RF03      | Cadastro sem email                             | o campo "email" deve ser preenchido                    | Sistema deve impedir o cadastro              |
| CT04 | RF04      | Cadastro só com nome                           | o campo "nome" deve ser preenchido com o nome completo | Sistema deve impedir o cadastro              |
| CT05 | RF05      | Cadastro preenchendo o campo "nome" com apelido| o campo "nome" deve ser preenchido com o nome completo | Sistema deve impedir o cadastro              |
| CT06 | RF06      | Cadastro sem email                             | o campo "email" deve ser preenchido                    | Sistema deve impedir o cadastro              |
