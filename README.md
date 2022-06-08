# Multi-Stack-Back-Java
Checklist do projeto back-end Spring da Semana Multi-stack TreinaWeb.

💻 [Repositório - GitHub](https://github.com/treinaweb/workshop-multistack-adote-um-pet-java)

## Checklist do Ambiente

- [ ]  Instalar JDK 17
    - 📥 [Download](https://jdk.java.net/java-se-ri/17)
- [ ]  Instalar Maven
    - 📥 [Download](https://maven.apache.org/download.cgi)
- [ ]  Instalar VS Code
    - 📥 [Download](https://code.visualstudio.com/download)
- [ ]  Instalar Insomnia
    - 📥 [Download](https://insomnia.rest/download)

🔗 [](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-windows/)[Instruções de configuração - Windows](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-spring-boot-no-windows)

🔗 [](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-linux/)[Instruções de configuração - Linux](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-spring-boot-no-linux)

🔗 [](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-macos/)[Instruções de configuração - macOS](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-spring-boot-no-macos)

## Checklist da Criação do Projeto

- [ ]  Criar o projeto com o [Spring Initializr](https://start.spring.io/) ou com o VS Code
- [ ]  Iniciar o servidor
    
    `mvn spring-boot:run`
    

## Checklist do Desenvolvimento - Segundo Dia

- [ ]  Criar o model de Pet
- [ ]  Criar o repository de Pet
- [ ]  Criar o controller de Pet
- [ ]  Criar a action de listagem de Pets
- [ ]  Criar DTOs e Mappers de Pet
- [ ]  Criar model de Adoção
- [ ]  Criar repository de Adoção
- [ ]  Criar DTOs e Mappers de Adoção
- [ ]  Criar controller de Adoção
- [ ]  Criar action de cadastro de Adoção
- [ ]  Configurar o CORS

## Checklist do Desenvolvimento - Quarto Dia

- [ ]  Refatorar o código
    - [ ]  Criar um exception especifica para Pet não encontrado
    - [ ]  Utilizar Stream API em PetRepository e em PetController
    - [ ]  Utilizar padrão Builder nos Mappers
- [ ]  Criar camada de service
- [ ]  Adicionar validação
- [ ]  Criar Exception Handler
- [ ]  Validar id do Pet no cadastro de Adoção
- [ ]  Criar action de listagem de Adoção
- [ ]  Criar action de cadastro de Pets