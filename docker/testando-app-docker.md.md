# Testando App Docker no GitHub Codespaces

Após configurar o Docker, é necessário inicializar os serviços (como banco de dados e API) e acessar a aplicação visualmente usando o ambiente do GitHub Codespaces.

Para subir os contêineres em segundo plano, construindo as imagens e rodando migrações automaticamente:

```bash
docker-compose up --build -d