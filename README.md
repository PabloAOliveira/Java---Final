# Projeto Final em Java 🚀

Este repositório contém os projetos finais desenvolvidos em Java. Eles implementam conceitos avançados de desenvolvimento, como microservices, registro e descoberta de serviços, comunicação entre APIs e muito mais, utilizando tecnologias modernas e práticas recomendadas.

## 📂 Estrutura dos Projetos

1. **api-gateway-service**  
   - Um **API Gateway** que atua como ponto de entrada único para os microservices.  
   - Funções: roteamento, segurança, autenticação e controle de tráfego.

2. **cambio-service**  
   - Serviço responsável pela conversão de moedas.  
   - Exemplo de integração com serviços externos e cálculos dinâmicos.

3. **config-service**  
   - Serviço centralizado de gerenciamento de configurações.  
   - Baseado no **Spring Cloud Config**, permite a configuração de todos os serviços a partir de um repositório central.

4. **configs/saudacao-service**  
   - Serviço responsável por fornecer saudações personalizadas.  
   - Exemplo de configuração modular.

5. **eureka-service**  
   - Serviço de registro e descoberta de microservices.  
   - Baseado no **Netflix Eureka**, facilita a comunicação entre os serviços sem a necessidade de endpoints fixos.

6. **produto-service**  
   - Serviço de gerenciamento de produtos.  
   - Exemplo de CRUD completo com persistência e comunicação com outros serviços.

7. **saudacao-service**  
   - Serviço responsável por fornecer mensagens de saudação.  
   - Exemplo de microservice autônomo.

## 🛠️ Tecnologias Utilizadas

- **Java**: Linguagem principal para todos os serviços.  
- **Spring Boot**: Framework para criar aplicações robustas e escaláveis.  
- **Spring Cloud**: Para implementação de padrões de microservices.  
- **Netflix OSS**: Eureka e outros componentes para resiliência e comunicação.  
- **Docker**: Para containerização dos serviços.  
- **Postman**: Para testes de API.
