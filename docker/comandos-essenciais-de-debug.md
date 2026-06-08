# Comandos Essenciais de Debug no Docker

Quando um contêiner apresenta falhas ou teima em ignorar edições no código-fonte, é preciso utilizar os comandos corretos para diagnosticar, reiniciar ou forçar a reconstrução do ambiente.

# 1. Diagnóstico: Lê a saída de erros em tempo real
```bash
docker-compose logs -f web

# 2. Tentativa Rápida: Apenas reinicia a imagem atual (não lê código novo)
```bash
docker-compose restart web

# 3. Atualização Padrão: Constrói uma nova imagem com os arquivos alterados
```bash
docker-compose up --build -d

# 4. Força Bruta: Reconstrói do zero absoluto, sem usar cache
```bash
docker-compose build --no-cache web
