# MicroServiço de Pagamentos com Java e Springboot

**Fazendo conexão com o seu Banco de Dados SQL**
- abrir o arquivo application.properties dentro da pasta resources(se não tiver criar)
-  adicionar o seguinte código
       spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
        spring.datasource.url=dbc:mysql://ENDERECODOSV/NOMEDODB?createDatabaseIfNotExist=true
        spring.datasource.username=NOMEDOUSER
        spring.datasource.password=SENHADOUSER
        spring.jpa.show-sql=true
        spring.jpa.show-sql=true

Trocar **ENDERECODOSV**  pelo endereco do servidor e porta, por exemplo localhost:3606
Trocar **NOMEDODB** pelo nome do banco de dados que quer criar
Trocar **NOMEDOUSER** pelo nome do usuario do banco de dados
Trocar **SENHADOUSER** pela senha do usuário do banco de dados


*projeto em andamento!*
