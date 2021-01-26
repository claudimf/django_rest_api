# Blog com Django REST Framework API + Docker

👋 Olá, Seja Bem-vindo(a) ao Blog com Django REST Framework API + Docker.

# Exigências

**:warning: Atenção:** É necessário que os desenvolvedores usem o Docker no seu ambiente de desenvolvimento.

- **🛠 Modo Desenvolvimento Docker**
    - :computer: [Linux Ubuntu LTS](https://ubuntu.com/download/desktop)
    - 🐳 [Docker](https://docs.docker.com/engine/installation/) Deve estar instalado.
    - 🐳 [Docker Compose](https://docs.docker.com/compose/) Deve estar instalado.
    - **💡 Dica:** [Documentação do Docker](https://docs.docker.com/)

# Instalando

## 🐳 Modo Desenvolvimento com Docker

Após instalar o docker e docker-compose, estando na pasta raiz do projeto, execute:

```sh
docker-compose up
```

Para se certificar que os seus containers subiram corretamente, todos os containers deve estar com o status `UP`, execute:

```sh
docker-compose ps -a
```

Para acessar o container da aplicação, execute:

```sh
docker-compose run --rm web bash
```

Para acessar a instância do banco de dados, execute:

```sh
docker exec-it [nome do db] bash
```

Para derrubar e subir a instância do docker novamente, execute:

```sh
docker-compose down && docker-compose up
```

🚀 :clap: Para visualizar o sistema basta acessar no navegador no endereço: [localhost:8000](localhost:8000)

# Referências utilizadas

[1° Build and Deploy a REST API with Django and Docker — Part 1](https://medium.com/@vinodkv2511/build-and-deploy-a-rest-api-with-django-and-docker-part-1-3645e7a4d182/) 

[2° Build and Deploy a REST API with Django and Docker — Part 2](https://medium.com/@vinodkv2511/build-and-deploy-a-rest-api-with-django-and-docker-part-2-8c375cc5e89f/) 

[3° Criar aplicação com Django + Docker](https://github.com/claudimf/django-docker/)  
