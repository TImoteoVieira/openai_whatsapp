# Projeto ChatBot OpenAI usando whatsapp

### Em desenvolvimento

1. Crie um arquivo .env com a atribuição correta das variaveis descritas em .env.example

2. Execute o comando:
``` 
    npm i
    node index.js
```
3. Conecte seu whatsapp no qrcode


### Em container

1. Crie um arquivo .env com a atribuição correta das variaveis descritas em .env.example

2. Execute o comando:
``` 
    docker-compose up --build -d
```
3. Use o comando abaixo para verificar o qrcode que será gerado e conectar-se a ele.
```  
    docker logs chat_bot
``` 
