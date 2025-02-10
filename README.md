Estudo de Caso em Java com Spring Boot e JPA

Este repositório apresenta um estudo de caso para implementação de um modelo conceitual utilizando Java, Spring Boot e JPA. O objetivo é demonstrar como um modelo UML pode ser implementado de forma prática com boas práticas de programação orientada a objetos.

🛠️ Ferramentas Utilizadas

* Java JDK 8: Para execução da aplicação.
* Spring Boot: Framework para simplificar a criação de aplicações Java.
* Spring Data JPA: Para persistência de dados.
* Banco de Dados H2: Banco de dados em memória para testes.
* Git: Controle de versão.
* Postman: Teste de APIs REST.
* STS (Spring Tool Suite): IDE para desenvolvimento com Spring Boot.

***

📑 Funcionalidades Implementadas

* CRUD de Categorias, Clientes e Pedidos.
* Associação entre entidades (um para muitos, muitos para muitos).
* Serialização de dados JSON.
* Tratamento de exceções.
* API REST com endpoints básicos:


|Endpoint           | Descrição                             |
|---|---|
|/categorias/{id}	| Retorna categoria e seus produtos     |
|/clientes/{id}     | Retorna cliente, telefones e endereços|
|/pedidos/{id}	    | Retorna pedido, itens e entrega       |


***

🛠️ Passo-a-passo para Instalação e Execução

Pré-requisitos

* Java JDK 8
* STS (Spring Tool Suite)
* Git
* Postman

Instalação e Execução

1. Clone o repositório:
\
git clone https://github.com/David-Simas/Java-Spring.git

2. Configurar o Java:
\
Certifique-se de ter a versão correta (Java 8, 64 bits).

3. Abra o projeto no STS:

* Vá em File -> Import -> Maven -> Existing Maven Projects.
* Selecione o diretório do projeto e clique em Finish.

4. Configurar Banco H2:
\
Certifique-se de que o arquivo application.properties está configurado com:

* spring.h2.console.enabled=true
* spring.h2.console.path=/h2-console
* spring.datasource.url=jdbc:h2:file:~/test
* spring.datasource.username=sa
* spring.datasource.password=
* spring.datasource.driver-class-name=org.h2.Driver
* spring.jpa.show-sql=true
* spring.jpa.properties.hibernate.format_sql=true

5. Executar a aplicação:
\
Clique com o botão direito no projeto > Run As > Spring Boot App.

6. Testar os endpoints:
\
Utilize o Postman para acessar os endpoints REST mencionados anteriormente.

***

🤝 Contribuição
\
Sinta-se à vontade para abrir issues e enviar pull requests.

📜 Licença
\
Este projeto está licenciado sob a licença MIT.

***

Se precisar de algum ajuste no conteúdo, é só avisar!
